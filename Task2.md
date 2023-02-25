# Matryoshka doll
> Tải file dolls.jpg về, sau đó dùng "binwalk -e dolls.jpg"
<img width="848" alt="Screenshot_20230223_113542" src="https://user-images.githubusercontent.com/72620926/220982224-9e51235c-4185-4c6a-b4b2-db7962b58579.png">

> Từ đó thấy được có thêm file ảnh thứ 2 trong base_image sau khi extract. Thế nên phải chuyển qua file dolls.jpg đã được extract "cd _dolls.jpg.extracted/"

<img width="845" alt="Screenshot_20230223_113606" src="https://user-images.githubusercontent.com/72620926/220983275-df5ba60e-d10e-448f-8c82-746b1f2f116c.png">

> Lại tiếp tục chuyến sang base_images để binwalk file 2_c.jpg. Cứ như vậy, lặp đi lặp lại cho đến khi tìm được flag.

<img width="854" alt="Screenshot_20230223_113627" src="https://user-images.githubusercontent.com/72620926/220983593-f8aef290-b06e-43cb-b9b2-ba7afdc13b33.png">
<img width="846" alt="Screenshot_20230223_113643" src="https://user-images.githubusercontent.com/72620926/220983645-8a092319-775c-4d13-a868-305ec51f897b.png">

> Thấy được file flag.txt. Cat file này để đọc nội dung.

<img width="856" alt="Screenshot_20230223_113710" src="https://user-images.githubusercontent.com/72620926/220983823-ceb4ae8a-6561-4492-a178-487753a23bd5.png">

> flag: picoCTF{96fac089316e094d41ea046900197662}
# Glory of the Garden
> Tải file ảnh về "garden.jpg". Dùng "strings garden.jpg" sẽ thấy flag ở cuối.
<img width="403" alt="image" src="https://user-images.githubusercontent.com/72620926/220985318-091e0e63-f176-47e4-92be-b9da3e918689.png">

> flag: picoCTF{more_than_m33ts_the_3y33dd2eEF5}
# Packets Primer
> Tải file về sau đó mở bằng wireshark. xem từng tập tin và tìm được flag ở góc dưới bên phải
<img width="947" alt="image" src="https://user-images.githubusercontent.com/72620926/221141316-431f8119-7e3a-4d9c-88aa-ad1c2709eeb5.png">

> flag: picoCTF{p4ck37_5h4rk_ceccaa7f}
# Wireshark doo dooo do doo...
> Tải file về sau đó mở bằng wireshark. Analyze -> follow -> TCP stream.
<img width="735" alt="image" src="https://user-images.githubusercontent.com/72620926/221165792-b168d397-fef8-4250-aece-cfffcb06cd0e.png">

> Tìm được dòng: Gur synt vf cvpbPGS{c33xno00_1_f33_h_qrnqorrs} trông nguy hiểm phết nên đi giải mã. (ROT-13)
> Sau khi giải mã: The flag is picoCTF{p33kab00_1_s33_u_deadbeef}
# Wireshark twoo twooo two twoo...
> Tải file về và mở bằng wireshark

> Thấy có 1 ip destination 18.217.1.57, lọc ip "ip.dst == 18.217.1.57", sau đó thấy có protocol dns là có trao đổi flag, nên lọc thêm dns "ip.dst == 18.217.1.57 && dns".
> 
<img width="960" alt="image" src="https://user-images.githubusercontent.com/72620926/221345735-f474e090-eff3-45df-83b4-8e26099d3957.png">

> Chú ý phần info sẽ thấy có dãy kí tự đặc biệt sau chữ A, ghép lại sẽ ra 1 chuỗi được mã hóa base64, giải mã và ra được flag

> flag: picoCTF{dns_3xf1l_ftw_deadbeef}
# Trivial Flag Transfer Protocol
Tải file về và mở bằng wireshark. File -> export objects -> TFTP. Hiện ra cửa sổ mới với 6 file, chọn save all để lưu các file này vào 1 folder nào đó trong máy.

Mở file "instruction.txt", nội dung là: GSGCQBRFAGRAPELCGBHEGENSSVPFBJRZHFGQVFTHVFRBHESYNTGENAFSRE.SVTHERBHGNJNLGBUVQRGURSYNTNAQVJVYYPURPXONPXSBEGURCYNA

Giải mã ROT-13: TFTPDOESNTENCRYPTOURTRAFFICSOWEMUSTDISGUISEOURFLAGTRANSFER.FIGUREOUTAWAYTOHIDETHEFLAGANDIWILLCHECKBACKFORTHEPLAN

> TFTP DOESNT ENCRYPT OUR TRAFFIC SO WE MUST DISGUISE OUR FLAG TRANSFER.FIGURE OUT AWAY TO HIDE THE FLAG AND I WILL CHECK BACK FOR THE PLAN.

Mở file plan, có nội dung là :  VHFRQGURCEBTENZNAQUVQVGJVGU-QHRQVYVTRAPR.PURPXBHGGURCUBGBF

Sau khi giải mã ROT-13: IUSEDTHEPROGRAMANDHIDITWITH-DUEDILIGENCE.CHECKOUTTHEPHOTOS

> I USED THE PROGRAM AND HID IT WITH-DUE DILIGENCE.CHECK OUT THE PHOTOS
