# Illumination
Tải file về và giải nén theo pass: hackthebox.

Sau khi giải nén thì có 1 file ẩn ".git". Nhưng sẽ dùng "cat" để xem nội dung 2 file config.json và bot.js trước:

<img width="767" alt="Screenshot_20230301_103927" src="https://user-images.githubusercontent.com/72620926/222041157-ddfaf72c-cb1b-4fe6-b5d9-7cb3493722fe.png">

<img width="945" alt="Screenshot_20230301_104016" src="https://user-images.githubusercontent.com/72620926/222041184-132418e7-f73a-40c2-b3a1-02d6ad992414.png">

Giải mã base64 phần username "Red Herring, read the JS carefully".

Dùng lệnh "git log" để xem commit logs

<img width="825" alt="image" src="https://user-images.githubusercontent.com/72620926/222042128-4dc9a59c-11a4-4e70-b1b6-67a7907442cf.png">

Để ý thấy ở commit 47241a47f62ada864ec74bd6dedc4d33f4374699 có nói rằng "Thanks to contributors, I removed the unique token as it was a security risk. Thanks for reporting responsibly!", mà ở file config.json có nhắc đến, nên dùng lệnh "git show 47241a47f62ada864ec74bd6dedc4d33f4374699" để xem token.

<img width="818" alt="image" src="https://user-images.githubusercontent.com/72620926/222043560-a568b707-eec6-4f58-b76f-445a0aece0dd.png">

giải mã token với base64 và ra được flag.
> flag: HTB{v3rsi0n_c0ntr0l_am_I_right?}

# Emo
Lấy mã Hash của file emo.doc để search trên virustotal

<img width="400" alt="image" src="https://github.com/Mscay/taskanhTung/assets/72620926/f2c51d1d-f9f6-4871-94e8-9fec3500d89f">
