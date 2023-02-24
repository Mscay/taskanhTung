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
