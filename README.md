# taskanhTung
# Introductory Researching
## Task 2 - Example Research Question
### In the Burp Suite Program that ships with Kali Linux, what mode would you use to manually send a request (often repeating a captured request numerous times)?
<img width="574" alt="cau1" src="https://user-images.githubusercontent.com/72620926/219309734-f9c1e9a7-daf6-457d-901f-58d184d42a3d.png">

### What hash format are modern Windows login passwords stored in?
<img width="579" alt="cau2" src="https://user-images.githubusercontent.com/72620926/219309889-381e0006-1b65-40ad-8cdb-f08a64c66549.png">

### What are automated tasks called in Linux?
<img width="563" alt="cau3" src="https://user-images.githubusercontent.com/72620926/219309989-de5a74c4-261d-4981-8810-0d8129aa1507.png">

### What number base could you use as a shorthand for base 2 (binary)?
<img width="557" alt="cau4" src="https://user-images.githubusercontent.com/72620926/219310093-d590dce3-9351-44a8-8d9f-34048e6c3aec.png">

### If a password hash starts with $6$, what format is it (Unix variant)?
<img width="521" alt="cau5" src="https://user-images.githubusercontent.com/72620926/219310262-0e6dc462-1adb-4112-88cb-d806046c7e98.png">

## Task 3 - Vulnerability Searching
### What is the CVE for the 2020 Cross-Site Scripting (XSS) vulnerability found in WPForms?
<img width="932" alt="cau1" src="https://user-images.githubusercontent.com/72620926/219311040-d2f0d6c7-c396-4447-8aa9-cc8f61c58c5e.png">

### There was a Local Privilege Escalation vulnerability found in the Debian version of Apache Tomcat, back in 2016. What's the CVE for this vulnerability?
<img width="920" alt="cau2" src="https://user-images.githubusercontent.com/72620926/219311197-a8ac51a1-0167-4381-a455-1ec6637f2085.png">

### What is the very first CVE found in the VLC media player?
<img width="955" alt="cau3" src="https://user-images.githubusercontent.com/72620926/219311422-2fcdad5d-77e6-442a-9be4-2f9795c5ea46.png">

### If you wanted to exploit a 2020 buffer overflow in the sudo program, which CVE would you use?
<img width="931" alt="cau4" src="https://user-images.githubusercontent.com/72620926/219311518-12cc0cfb-ca9f-425f-9146-948b0468628c.png">

## Task 4 - Manual Pages
### SCP is a tool used to copy files from one computer to another. What switch would you use to copy an entire directory?
<img width="545" alt="cau1" src="https://user-images.githubusercontent.com/72620926/219312154-bfa06f42-b9a0-498e-a532-d59c1c84357d.png">

### fdisk is a command used to view and alter the partitioning scheme used on your hard drive. What switch would you use to list the current partitions?
<img width="680" alt="cau2" src="https://user-images.githubusercontent.com/72620926/219312310-b6f34398-28e8-424a-b826-18464a293002.png">

### nano is an easy-to-use text editor for Linux. There are arguably better editors (Vim, being the obvious choice); however, nano is a great one to start with. What switch would you use to make a backup when opening a file with nano?
<img width="623" alt="cau3" src="https://user-images.githubusercontent.com/72620926/219312450-933f6d78-b7c7-4546-9b9b-3f868e87006b.png">

### Netcat is a basic tool used to manually send and receive network requests. What command would you use to start netcat in listen mode, using port 12345?
<img width="598" alt="cau4" src="https://user-images.githubusercontent.com/72620926/219312619-3f584f2f-c30b-4a82-b779-8e72fd72fd8b.png">

# linuxfundamentalspart1
## Task 2 - A Bit of Background on Linux
### Research: What year was the first release of a Linux operating system?
<img width="520" alt="cau1" src="https://user-images.githubusercontent.com/72620926/219313277-2b3735f3-e515-4ad7-9adb-4cabbbc4ac21.png">

## Task 4 -  Running Your First few Commands
### If we wanted to output the text "TryHackMe", what would our command be? 
### and
### What is the username of who you're logged in as on your deployed Linux machine?
<img width="886" alt="cau1va2" src="https://user-images.githubusercontent.com/72620926/219313848-c37c0205-8404-4356-ae04-ad6bbf83398b.png">

## Task 5 - Interacting With the Filesystem!
### On the Linux machine that you deploy, how many folders are there?
<img width="281" alt="Screenshot_20230218_041236" src="https://user-images.githubusercontent.com/72620926/219794428-73c7efe6-ac95-4903-a3e6-5de2e5eefc17.png">

<img width="909" alt="image" src="https://user-images.githubusercontent.com/72620926/219794549-3522273f-5d6b-4830-9076-0ac93cb3072c.png">

### Which directory contains a file? 
thử lệnh "ls" cho cả 4 folders, xem folder nào chứa file.
<img width="902" alt="image" src="https://user-images.githubusercontent.com/72620926/219794747-e5ac14d6-e0f7-4924-9cbd-546d4ad4c7b0.png">

### What is the contents of this file?
Dùng lệnh "cat folder4/note.txt" để chuyển sang folder4 và đọc file note.txt trong folder4.
<img width="247" alt="Screenshot_20230218_041703" src="https://user-images.githubusercontent.com/72620926/219795188-9130056b-326f-4311-8e12-78d7b430f52a.png">

<img width="914" alt="image" src="https://user-images.githubusercontent.com/72620926/219795497-59ec71a2-7fea-4f16-94fc-0b2728fada50.png">

### Use the cd command to navigate to this file and find out the new current working directory. What is the path?
Nhập lệnh "cd folder4" để chuyển sang folder4 và dùng lệnh "pwd" để xem đường dẫn.
<img width="215" alt="image" src="https://user-images.githubusercontent.com/72620926/219795645-c0656b32-e700-4ec1-bebc-4395b1aa12af.png">

<img width="921" alt="image" src="https://user-images.githubusercontent.com/72620926/219795854-09ff118a-9be3-41ea-8194-f45fda0e22c2.png">

## Task 6 - Searching for Files
### Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag?
<img width="593" alt="Screenshot_20230216_041308" src="https://user-images.githubusercontent.com/72620926/219320573-53f74bf2-9f7a-4916-9de7-b885b072ebdc.png">

## Task 7 - An Introduction to Shell Operators
<img width="891" alt="Screenshot_20230216_041558" src="https://user-images.githubusercontent.com/72620926/219321326-a6a993ac-17fd-4c2b-ad4b-3a988d7a1fc6.png">

# linuxfundamentalspart2
## Task 3 - Introduction to Flags and Switches
### What directional arrow key would we use to navigate down the manual page?
Nhập "man ls" trên terminal sau đó thử dùng các nút điều hướng -> câu trả lời là "down".
### What flag would we use to display the output in a "human-readable" way?
Nhập "man ls" sau đó lướt xuống để tìm trong phần "DESCRIPTION".
<img width="474" alt="Screenshot_20230217_045234" src="https://user-images.githubusercontent.com/72620926/219620090-696c8858-1508-45a1-98b7-a43076240611.png">

## Task 4 - Filesystem Interaction Continued
### How would you create the file named "newnote"?
<img width="439" alt="image" src="https://user-images.githubusercontent.com/72620926/219619410-75f8fc70-284b-412d-9882-80d50eba6982.png">

### On the deployable machine, what is the file type of "unknown1" in "tryhackme's" home directory?
Nhập lệnh "file unknown1" trong attackbox để xác định kiểu file.
<img width="290" alt="image" src="https://user-images.githubusercontent.com/72620926/219618818-658933f9-38bd-4263-874e-0b1dc85833a0.png">

### How would we move the file "myfile" to the directory "myfolder" 
<img width="445" alt="image" src="https://user-images.githubusercontent.com/72620926/219621220-5e9287e8-d559-4e30-8428-13d1c7cd94f4.png">

### What are the contents of this file?
Nhập lệnh "cat myfile" để đọc nội dung file myfile.
<img width="309" alt="image" src="https://user-images.githubusercontent.com/72620926/219621814-fc0b93b5-36cd-48a8-bd20-72bb18efaed6.png">

## Task 5 - Permissions 101
### On the deployable machine, who is the owner of "important"?
Nhập lệnh "ls -al".

<img width="424" alt="image" src="https://user-images.githubusercontent.com/72620926/219650312-74047c69-00dd-46ca-ad70-a1e04fea83d6.png">

### What would the command be to switch to the user "user2"?
<img width="882" alt="Screenshot_20230217_071345" src="https://user-images.githubusercontent.com/72620926/219651034-a1a41503-5378-4dc6-85e6-9e486fca356a.png">

### Output the contents of "important", what is the flag?
Nhập lệnh "cat important" để xem nội dung trong important
<img width="901" alt="image" src="https://user-images.githubusercontent.com/72620926/219652564-77f7f150-aed2-446c-88cb-8451ec75635c.png">

## Task 6 - Common Directories
### What is the directory path that would we expect logs to be stored in?
<img width="908" alt="image" src="https://user-images.githubusercontent.com/72620926/219654357-dae686f7-23db-4f42-9a8b-e53f29e6c29e.png">

### What root directory is similar to how RAM on a computer works?
This is a unique root directory found on a Linux install. Short for "temporary", the /tmp directory is volatile and is used to store data that is only needed to be accessed once or twice. Similar to the memory on your computer, once the computer is restarted, the contents of this folder are cleared out.

<img width="887" alt="image" src="https://user-images.githubusercontent.com/72620926/219655412-f0184590-0d7b-4edd-bdfc-c770a59cb177.png">

### Name the home directory of the root user 
the /root folder is actually the home for the "root" system user
 
<img width="904" alt="image" src="https://user-images.githubusercontent.com/72620926/219655738-3e309a4a-dd44-4e51-884e-b3434cdb6b24.png">
 
 # linuxfundamentalspart3
 ## Task 3 - Terminal Text Editors
 ### Edit "task3" located in "tryhackme"'s home directory using Nano. What is the flag?
 Nhập lệnh "nano task3" 
 
 <img width="891" alt="image" src="https://user-images.githubusercontent.com/72620926/219759705-7f36996e-4b2d-48ba-ade2-bbb058d57284.png">

## Task 4 - General/Useful Utilities
### Download the file http://MACHINE_IP:8000/.flag.txt onto the TryHackMe AttackBox. What are the contents?
Nhập lệnh "wget http://MACHINE_IP:8000/.flag.txt" để tải file .flag.txt.
<img width="370" alt="Screenshot_20230218_023329" src="https://user-images.githubusercontent.com/72620926/219787090-906ee108-24ff-4a8b-96a0-d9de5083677b.png">

Sau đó dùng lệnh "cat .flag.txt" để xem nội dung trong file
<img width="211" alt="Screenshot_20230218_023429" src="https://user-images.githubusercontent.com/72620926/219787452-e9be1af6-db7b-4632-9d69-764ad3b60fdc.png">

<img width="905" alt="Screenshot_20230218_024024" src="https://user-images.githubusercontent.com/72620926/219787489-9dcd9785-5081-4679-aea1-c3c4cfd219df.png">

## Task 5 - Processes 101
### If we were to launch a process where the previous ID was "300", what would the ID of this new process be?
The PID increments for the order In which the process starts. I.e. the 60th process will have a PID of 60.
<img width="890" alt="Screenshot_20230218_030157" src="https://user-images.githubusercontent.com/72620926/219787639-00dbe474-648e-471f-99ed-c9c8c1c3934a.png">

### If we wanted to cleanly kill a process, what signal would we send it?
<img width="897" alt="Screenshot_20230218_030417" src="https://user-images.githubusercontent.com/72620926/219787815-d06f528b-2646-4f39-ba6e-708172f72173.png">

### Locate the process that is running on the deployed instance (MACHINE_IP). What flag is given?
Nhập lệnh "ps aux", enter, sau đó tìm flag.
<img width="419" alt="Screenshot_20230218_030625" src="https://user-images.githubusercontent.com/72620926/219787876-08c16ed5-d400-4ea4-b392-e859db8ea18d.png">

<img width="902" alt="image" src="https://user-images.githubusercontent.com/72620926/219788182-a9cccd48-9d49-4a87-9e23-a54fc8874af2.png">

### What command would we use to stop the service "myservice"?
<img width="897" alt="Screenshot_20230218_031049" src="https://user-images.githubusercontent.com/72620926/219788249-05db3793-6231-419a-b20c-485905f85a59.png">

### What command would we use to start the same service on the boot-up of the system?
<img width="901" alt="Screenshot_20230218_031319" src="https://user-images.githubusercontent.com/72620926/219788341-df27de06-f6be-41b4-95b3-a8c253508784.png">

### What command would we use to bring a previously backgrounded process back to the foreground?
<img width="896" alt="Screenshot_20230218_031439" src="https://user-images.githubusercontent.com/72620926/219788410-66735aea-5427-4cab-b749-1b20e1469b6d.png">

## Task 6 - Maintaining Your System: Automation
### When will the crontab on the deployed instance (MACHINE_IP) run?
Nhập lệnh "crontab -e", enter
<img width="410" alt="Screenshot_20230218_034316" src="https://user-images.githubusercontent.com/72620926/219789058-5214c25a-1341-407e-820a-037bd0aef1aa.png">

<img width="906" alt="image" src="https://user-images.githubusercontent.com/72620926/219789281-35e891e9-f886-4588-9c01-580e577e5e54.png">

## Task 7 - Maintaining Your System: Package Management
## Task 8 - Maintaining Your System: Logs
### What is the IP address of the user who visited the site?
Đầu tiên nhập lệnh "cd /var/log" để chuyến đến thư mục log.

Sau đó nhập lệnh "ls" để xem list các mục trong thư mục, tìm mục apache2.
<img width="420" alt="Screenshot_20230218_035634" src="https://user-images.githubusercontent.com/72620926/219791754-8f995d81-d823-4ecf-94f7-e538b491cde0.png">

Nhập lệnh "cd apache2" để vào thư mục này và tiếp tục nhập "ls" để xem danh sách file. Vì user ở đây là tryhackme nên cần để ý đến dòng thứ 2 trong bảng, nó thuộc file access.log.1

Dùng lệnh "cat access.log.1" để đọc nôi dung của file, sẽ thấy phần ip ở đầu tiên.

<img width="394" alt="Screenshot_20230218_040102" src="https://user-images.githubusercontent.com/72620926/219792475-192c6a5f-7545-4b65-8835-8ef3f2d07803.png">

<img width="910" alt="image" src="https://user-images.githubusercontent.com/72620926/219793245-6da9a9e6-1e4a-4201-aeea-a3c269f7c337.png">

### What file did they access?
Phần được bôi đen chính là file đã được truy cập.

<img width="393" alt="Screenshot_20230218_040736" src="https://user-images.githubusercontent.com/72620926/219793499-d0b70dd8-a15c-437e-9ea6-f5252903e72c.png">

<img width="913" alt="image" src="https://user-images.githubusercontent.com/72620926/219793741-b84041fd-feea-4f9d-85cc-297f3e83acf5.png">

# googledorking
## Task 2 - Let's Learn About Crawlers
### Name the key term of what a "Crawler" is used to do
The diagram below is a high-level abstraction of how these web crawlers work. Once a web crawler discovers a domain such as mywebsite.com, it will index the entire contents of the domain, looking for keywords and other miscellaneous information

<img width="896" alt="image" src="https://user-images.githubusercontent.com/72620926/219825919-cc4a8ef5-f01f-4428-9ae6-73ae0ff83123.png">

### What is the name of the technique that "Search Engines" use to retrieve this information about websites?
<img width="917" alt="image" src="https://user-images.githubusercontent.com/72620926/219826351-e95b84df-82e6-48a3-80ab-1140d531e358.png">

<img width="145" alt="image" src="https://user-images.githubusercontent.com/72620926/219826396-7c6f8b2c-735b-4749-a57c-f43082dcaf4c.png">

### What is an example of the type of contents that could be gathered from a website?
<img width="257" alt="image" src="https://user-images.githubusercontent.com/72620926/219826517-eeec64d0-dd37-4d89-b289-1cfca2ade171.png">

<img width="915" alt="image" src="https://user-images.githubusercontent.com/72620926/219826539-0e9ac6dd-cb67-4d4d-bdb7-e9b9f5ea558a.png">

## Task 3 - Enter: Search Engine Optimisation

