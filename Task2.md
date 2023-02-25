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

Giờ sẽ đi check mấy cái ảnh, dùng câu lệnh này cho từng bức ảnh 1, và bức ảnh thứ 3 thì cho thấy 1 file flag.txt được nhúng.

>  steghide info picture3.bmp
<img width="391" alt="image" src="https://user-images.githubusercontent.com/72620926/221360910-630314fd-5238-4dc1-a6ec-62082a6dd4af.png">

>  steghide extract -sf picture3.bmp , nội dung từ tệp flag.txt gốc sẽ được trích xuất từ tệp picture3.bmp và được lưu trong thư mục hiện tại.
<img width="437" alt="image" src="https://user-images.githubusercontent.com/72620926/221361297-667de410-6a45-45cf-afdb-ebb84d122c4f.png">

> Dùng strings để đọc dữ liệu trong file flag.txt và nhận được flag.
<img width="345" alt="image" src="https://user-images.githubusercontent.com/72620926/221361365-8934fec4-f1ac-497d-b76a-fe0c3727bc7e.png">

> flag: picoCTF{h1dd3n_1n_pLa1n_51GHT_18375919}
# What Lies Within
Dựa theo gợi ý là "There is data encoded somewhere... there might be an online decoder." nên dùng Steganography Online để decode ảnh và đây là kết quả:

<img width="882" alt="image" src="https://user-images.githubusercontent.com/72620926/221364733-5ca8f9eb-eec0-46a1-8e2d-5bd90ef172ec.png">

> flag: picoCTF{h1d1ng_1n_th3_b1t5}
# Investigating Windows
***Whats the version and year of the windows machine?***

Mở windows powershell và chạy lệnh "systeminfo" để xem thông tin máy. Chú ý dòng OS name.

> answer: windows server 2016

***Which user logged in last?***

Mở windows powershell và chạy lệnh "net user USER_NAME" đẻ biết thời gian đang nhập cuối cùng của từng user.

<img width="374" alt="Screenshot_20230225_111132" src="https://user-images.githubusercontent.com/72620926/221370341-c7cd2dd2-b406-4240-9eb6-2c90f8d7271e.png">

Người đăng nhập cuối cùng là mình (administrator)
> answer: Administrator.

***When did John log onto the system last?***

<img width="244" alt="Screenshot_20230225_111343" src="https://user-images.githubusercontent.com/72620926/221370436-e07bd77c-e91e-4b8d-aaae-e967f0d361ff.png">

Chú ý dòng last logon.
> answer: 03/02/2019 5:48:32 PM

***What IP does the system connect to when it first starts?***

> answer: 10.34.2.3

***What two accounts had administrative privileges (other than the Administrator user)?***

computer management > local users and groups > user, nhấn xem từng user một xem ai có quyền admin ngoài Administrator.

<img width="440" alt="Screenshot_20230226_120801" src="https://user-images.githubusercontent.com/72620926/221370611-ae530322-73ce-4581-82c1-3b9c6031f88a.png">

<img width="421" alt="Screenshot_20230226_120815" src="https://user-images.githubusercontent.com/72620926/221370616-7af87332-5c7f-47e5-9b6d-d7e5cc74d509.png">

> answer: Jenny, guest

***Whats the name of the scheduled task that is malicous.***
Vẫn trong computer management, chọn task scheduler > task scheduler library, task clean file system có lẽ là task độc trong số các task đang có.
> answer: clean file system

***What file was the task trying to run daily?***

Trong task "clean file system" được chạy mỗi ngày, chọn vào phần action, chú ý phần details, có file "nc.ps1"

<img width="295" alt="image" src="https://user-images.githubusercontent.com/72620926/221371413-d58d6b3e-6faa-4442-a1dc-12a21233433f.png">

> answer: nc.ps1

***What port did this file listen locally for?***

Câu trả lời có trong phần ảnh của câu trên (trong phần details của action).
> answer: 1348

***When did Jenny last logon?***

Chạy lệnh "net user Jenny" sẽ thấy câu trả lời.
> answer: never

***At what date did the compromise take place?***

Tìm kiếm trong ổ C và thấy 1 thư mục khả nghi "TMP" và nó được tạo vào ngày 03/02/2019

<img width="473" alt="image" src="https://user-images.githubusercontent.com/72620926/221372994-ac839cf3-1bcb-45dc-85bf-7569ffc528b2.png">

> answer: 03/02/2019

***At what time did Windows first assign special privileges to a new logon?***




