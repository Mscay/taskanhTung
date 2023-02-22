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
## Task 4 - Beepboop - Robots.txt
### Where would "robots.txt" be located on the domain "ablog.com"
<img width="761" alt="image" src="https://user-images.githubusercontent.com/72620926/219830002-7ff0feb4-8e68-4d1a-a89e-cf76ae9268ac.png">

### If a website was to have a sitemap, where would that be located?
Dựa theo những ảnh chụp trong phần lý thuyết 
<img width="356" alt="image" src="https://user-images.githubusercontent.com/72620926/219830052-1155a57d-87b9-4baf-82c1-d43b08c11b19.png">

<img width="887" alt="image" src="https://user-images.githubusercontent.com/72620926/219830029-a290f0b2-34e2-4b6a-9b07-c40bb84cb0dc.png">

### How would we only allow "Bingbot" to index the website?
<img width="902" alt="image" src="https://user-images.githubusercontent.com/72620926/219830073-479eac02-d6bd-48b3-81e1-d5296bd98fc8.png">

### How would we prevent a "Crawler" from indexing the directory "/dont-index-me/"?
<img width="888" alt="image" src="https://user-images.githubusercontent.com/72620926/219830085-d2792f7f-fb80-457c-9bd8-3b2e94401487.png">

### What is the extension of a Unix/Linux system configuration file that we might want to hide from "Crawlers"?
Dựa vào tên file cấu hình "configuration" và hint "system files are usually 3/4 characters!"
<img width="891" alt="image" src="https://user-images.githubusercontent.com/72620926/219830110-f91cf4ec-31da-4472-9d5f-3ae827f2a1d3.png">

## Task 5 - Sitemaps
### What is the typical file structure of a "Sitemap"?
“Sitemaps” are XML formatted
### What real life example can "Sitemaps" be compared to?
Comparable to geographical maps in real life, “Sitemaps” are just that - but for websites!
### Name the keyword for the path taken for content on a website
he blue rectangles represent the route to nested-content, similar to a directory I.e. “Products” for a store
<img width="890" alt="image" src="https://user-images.githubusercontent.com/72620926/219830444-64379cc8-2972-4a3e-80c1-29f9cb9d71f3.png">

## Task 6 - What is Google Dorking?
### What would be the format used to query the site bbc.co.uk about flood defences
<img width="761" alt="image" src="https://user-images.githubusercontent.com/72620926/219830804-3cee8298-8108-4f49-a540-84527442c1e2.png">

### What term would you use to search by file type?
<img width="901" alt="image" src="https://user-images.githubusercontent.com/72620926/219830814-573b0cf5-a576-4a79-949b-78e2a0089be4.png">

### What term can we use to look for login pages?
Vì là trang login nên phải có "login" trong tiêu đề của trang -> dùng term "intitle"
<img width="762" alt="image" src="https://user-images.githubusercontent.com/72620926/219830827-1d10bfaf-3994-41ca-a42f-69c93f35645d.png">

# ohsint
## Task 1 - OHSINT
### What is this users avatar of?
Đầu tiên là tải file task, sau đó dùng exiftool để xem thông tin về file ảnh vừa tải

<img width="447" alt="image" src="https://user-images.githubusercontent.com/72620926/219836187-18c68022-62af-4978-8623-8d704e7e3fc3.png">

Chú ý phần copyright "OWoodflint", tra gg OWoodflint thì ra 1 trang twitter

<img width="517" alt="image" src="https://user-images.githubusercontent.com/72620926/219836585-8d347005-318a-4b94-8d7c-d96cffb933ae.png">

Thấy avatar là 1 con mèo -> câu trả lời là cat
<img width="761" alt="image" src="https://user-images.githubusercontent.com/72620926/219848058-52c16c37-3ba6-48cb-9b71-3b7ed64c1489.png">

### What city is this person in?
Đọc bài tweet thấy có 1 bài như sau:

<img width="342" alt="image" src="https://user-images.githubusercontent.com/72620926/219838480-c4d2f52a-71e3-4084-8548-4211f2c0de95.png">

Dưới phần bình luận có 1 đoạn mã base64

<img width="513" alt="image" src="https://user-images.githubusercontent.com/72620926/219838725-d00d1982-35c3-4c2c-8a85-f02910a4e17a.png">

Sau khi giải mã đoạn code trên thì nhận được "Give wigle.net a try", tra gg wigle.net.
<img width="924" alt="image" src="https://user-images.githubusercontent.com/72620926/219847868-d71e8583-f650-4566-a72e-8efe1581f908.png">

Paste "B4:5D:50:AA:86:41" vào phần BSSID/MAC: rồi chọn "view basic" và tìm chấm màu tím như hình -> câu trả lời là london.
<img width="771" alt="image" src="https://user-images.githubusercontent.com/72620926/219847954-049a9272-30cf-4870-b099-910fe082737a.png">

### Whats the SSID of the WAP he connected to?
Phóng to điểm màu tím sẽ ra tên wifi
<img width="890" alt="image" src="https://user-images.githubusercontent.com/72620926/219848444-c1fac541-5138-4587-b4c0-6d2c1ea9ad28.png">

<img width="232" alt="image" src="https://user-images.githubusercontent.com/72620926/219848404-6942edce-17a0-4408-a758-846fee677172.png">

### What is his personal email address?
Lướt xem phần comment sẽ thấy có 1 comment email

<img width="515" alt="image" src="https://user-images.githubusercontent.com/72620926/219848526-071cfb52-7c17-475c-8009-73bfb36ff614.png">

<img width="899" alt="image" src="https://user-images.githubusercontent.com/72620926/219848560-911d698f-c6ea-4d7e-aeea-d8114677e192.png">

### What site did you find his email address on?
Tra gg email sẽ thấy có 3 trang: wordpress, twitter và github. Vào từng trang một thì sẽ thấy email trong trang github:
<img width="671" alt="image" src="https://user-images.githubusercontent.com/72620926/219848886-73d25ce3-1ec5-4495-893e-ca44d18d44aa.png">

<img width="896" alt="image" src="https://user-images.githubusercontent.com/72620926/219848904-a4c22ada-061d-4e52-aebb-5ebc460bb9c6.png">

### Where has he gone on holiday?
Trong wordpress đã nói rằng ông này đang ở new york: 

<img width="577" alt="image" src="https://user-images.githubusercontent.com/72620926/219849342-f955b8a1-2c20-41f4-bbd7-b6dd8e956744.png">

<img width="897" alt="image" src="https://user-images.githubusercontent.com/72620926/219849396-1c2feead-5c65-4a6e-a53a-90fe903beacb.png">

### What is this persons password?
Vào trang wordpress thì sẽ không thấy gì đặc biệt, nhưng khi bôi đen hết các dòng chữ thì sẽ hiện ra 1 dòng kí tự được viết bằng màu trắng:
"pennYDr0pper.!"
<img width="609" alt="Screenshot_20230218_060857" src="https://user-images.githubusercontent.com/72620926/219857160-db7460bd-9572-4352-bfaa-f35ab8135b2e.png">

<img width="903" alt="image" src="https://user-images.githubusercontent.com/72620926/219857175-052bdca7-44aa-440f-88dd-3a9bf678c1b7.png">

# shodan
## Task 2 - Filters
### How do we find Eternal Blue exploits on Shodan?
Let’s say we want to find IP addresses vulnerable to Eternal Blue:

vuln:ms17-010

<img width="901" alt="image" src="https://user-images.githubusercontent.com/72620926/219888843-8edf5dc1-e712-4cfb-818e-e04cb6d2e72f.png">

## Task 3 - Google & Filtering
### What is the top operating system for MYSQL servers in Google's ASN?
Đầu tiên, Tra gg tìm google's asn (AS15169).

TRa trên shodan "ASN:AS15169 product:MySQL", nhưng mà nó không ra nên phải dùng hint thôi chứ em hết cách rồi.
<img width="319" alt="Screenshot_20230219_023933" src="https://user-images.githubusercontent.com/72620926/219936023-5ffba7cf-6a3b-4162-99f0-ed45706733ec.png">

<img width="900" alt="Screenshot_20230219_024037" src="https://user-images.githubusercontent.com/72620926/219936037-9f364743-76fe-4600-b1a6-85fe94eb8af7.png">

### What is the 2nd most popular country for MYSQL servers in Google's ASN?
Ở vị trí thứ hai là "netherland"
<img width="301" alt="Screenshot_20230219_024109" src="https://user-images.githubusercontent.com/72620926/219936076-9c25b46b-1523-4fa2-8624-a61498122a73.png">

### Under Google's ASN, which is more popular for nginx, Hypertext Transfer Protocol or Hypertext Transfer Protocol with SSL?
Dựa vào format answer thì ra được câu trả lời là "Hypertext Transfer Protocol".
<img width="899" alt="image" src="https://user-images.githubusercontent.com/72620926/219936114-78b9ee02-096a-4f7a-968d-76be2fa4ecec.png">

### Under Google's ASN, what is the most popular city?
Vì US là nước đừng đầu trong top countries nên tra trên shodan thêm phần country "ASN:AS15169 product:MySQL country:"US""
<img width="225" alt="image" src="https://user-images.githubusercontent.com/72620926/219936243-ea7c940b-0ead-40af-a08f-63a9542fbd44.png">

Mặc dù "Council Bluffs" là nước đứng đầu, tuy nhiên điền vào phần đáp án lại không được. Thử dến "Los Angeles" rồi đến "Mountain view" thì mới được.
<img width="893" alt="image" src="https://user-images.githubusercontent.com/72620926/219936338-60e7604b-e6ed-42c3-92c8-2349e8da590e.png">

### Under Google's ASN in Los Angeles, what is the top operating system according to Shodan?
Tra "ASN:AS15169 product:MySQL country:"US" city:"Los Angeles"" trên Shodan, nhưng lại không có kết quả.

<img width="281" alt="Screenshot_20230219_030444" src="https://user-images.githubusercontent.com/72620926/219936495-0f3d8700-a7d9-4f74-8aad-c6fab2bbb6e5.png">

Nên vẫn dùng kết quả của hint

<img width="899" alt="image" src="https://user-images.githubusercontent.com/72620926/219936531-aa87a5ed-40f3-4a16-ae09-770a0d47ebc7.png">

### Using the top Webcam search from the explore page, does Google's ASN have any webcams? Yay / nay.
Tra trên Shodan "ASN:AS15169 tags:webcam" và không có webcam nào
<img width="575" alt="image" src="https://user-images.githubusercontent.com/72620926/219936666-bff2c6ce-5a78-4de5-936c-a8aa35856fd9.png">

<img width="895" alt="image" src="https://user-images.githubusercontent.com/72620926/219936670-3214391a-5218-4b53-80a0-8b81d34743e7.png">

## Task 4 - Shodan Monitor
### What URL takes you to Shodan Monitor?
<img width="894" alt="image" src="https://user-images.githubusercontent.com/72620926/219937011-7a4cd8c2-f61a-40a4-b600-2420e4238d96.png">

## Task 5 - Shodan Dorking
### What dork lets us find PCs infected by Ransomware?
<img width="901" alt="image" src="https://user-images.githubusercontent.com/72620926/219937058-5bcdb688-5cd7-47a8-b7cd-6318a5fa5284.png">

# Intro to Digital Forensics
## Task 1 - Introduction To Digital Forensics
<img width="894" alt="Screenshot_20230219_034242" src="https://user-images.githubusercontent.com/72620926/219939252-48c29078-c645-46ff-a838-fbfcdcc6bb4f.png">

## Task 2 - Digital Forensics Process
### It is essential to keep track of who is handling it at any point in time to ensure that evidence is admissible in the court of law. What is the name of the documentation that would help establish that?
Chain of custody: This is necessary to keep track of who was holding the evidence at any time.

<img width="888" alt="Screenshot_20230219_035204" src="https://user-images.githubusercontent.com/72620926/219939295-8be2ce15-2163-4071-8342-21948e285ceb.png">

## Task 3 - Practical Example of Digital Forensics
Using pdfinfo, find out the author of the attached PDF file.

<img width="442" alt="image" src="https://user-images.githubusercontent.com/72620926/219939340-d22c3b42-2d77-42f7-9e28-24f97eff9853.png">

Thấy phần "author" là  "Ann Gree Shepherd"

<img width="888" alt="image" src="https://user-images.githubusercontent.com/72620926/219939407-7285e9a0-91d2-465d-a2d0-3ccc696b4543.png">

### Using exiftool or any similar tool, try to find where the kidnappers took the image they attached to their document. What is the name of the street?
Dùng lệnh "exiftool letter-image.jpg" trong ubuntu

<img width="612" alt="image" src="https://user-images.githubusercontent.com/72620926/220008415-1f5b44b0-e7d8-4f34-886a-9b3c9079f025.png">

Chú ý phần GPS lattitude, longitude và position. chuyển đổi sang dạng decimal để tra gg map.

<img width="516" alt="image" src="https://user-images.githubusercontent.com/72620926/220008471-1b435355-0241-4534-b596-dfe441fa61ae.png">

<img width="443" alt="image" src="https://user-images.githubusercontent.com/72620926/220008647-2da9d792-d8fb-4dcc-9be6-77e7c9facfad.png">

Đây là thông tin thu được khi tra gg map

<img width="943" alt="image" src="https://user-images.githubusercontent.com/72620926/220008796-eaa3bb60-c9bf-4f97-b67a-aeeec762c788.png">

Phần vị trí ở khung bên trái, thấy tên con phố là "milk street".

<img width="889" alt="image" src="https://user-images.githubusercontent.com/72620926/220008998-cdce2896-18cf-4724-a0de-65cb101b4e45.png">

### What is the model name of the camera used to take this photo?
chú ý dòng "Camera model name".
<img width="391" alt="Screenshot_20230220_112507" src="https://user-images.githubusercontent.com/72620926/220009501-7048e153-2704-4a52-81fc-4225e32e22e4.png">

<img width="903" alt="image" src="https://user-images.githubusercontent.com/72620926/220009692-6e08c476-ccd5-4365-b6a3-baaa7ce2c621.png">

# Windows Fundamentals 1
## Task 2 - Windows Editions
### What encryption can you enable on Pro that you can't enable in Home?
<img width="796" alt="image" src="https://user-images.githubusercontent.com/72620926/220171525-b83cdf57-d13f-43e3-8b68-cf87bfb6c185.png">

So sánh giữa 2 bản thì thấy phần Bitlocker device encryption có bên bản pro còn home thì không.

<img width="902" alt="image" src="https://user-images.githubusercontent.com/72620926/220171798-db96c7b7-c318-41e5-a53e-c95886cfedbb.png">

## Task 3 - The Desktop (GUI)
<img width="930" alt="image" src="https://user-images.githubusercontent.com/72620926/220236924-62a7df36-a1b0-48a4-9c19-0486438c421a.png">

## Task 4 - The file system
<img width="903" alt="image" src="https://user-images.githubusercontent.com/72620926/220239499-dc36b842-0baa-4912-a7b0-c2493858b9c2.png">

## Task 5 - The Windows\System32 Folders
<img width="904" alt="image" src="https://user-images.githubusercontent.com/72620926/220241142-114f0343-8187-4657-8267-a3d35bbe56cd.png">

## Task 6 - User Accounts, Profiles, and Permissions
Đã được anh Tùng hướng dẫn và không giải thích gì thêm

<img width="897" alt="image" src="https://user-images.githubusercontent.com/72620926/220252228-7abab444-6477-4291-9886-ac7f59ba15a2.png">

## Task 7 - User Account Control
<img width="904" alt="image" src="https://user-images.githubusercontent.com/72620926/220253106-a025877f-420a-4f92-b247-a76005d997d6.png">

## Task 8 - Settings and the Control Panel
Không phải cái cuối thì thử cái gần cuối. 

<img width="569" alt="Screenshot_20230221_113926" src="https://user-images.githubusercontent.com/72620926/220254018-28e81227-65b1-4f87-b030-b233bfef35b3.png">

<img width="908" alt="image" src="https://user-images.githubusercontent.com/72620926/220254234-26dd7dd2-147e-4cdb-b6a2-fda62a43cee3.png">

## Task 9 -  Task Manager
Tra gg "keyboard shortcut task manager" 

<img width="896" alt="image" src="https://user-images.githubusercontent.com/72620926/220254448-8a179aa0-c032-4628-9190-8ae9fa88a8d9.png">

# Volatility
## Task 2 - Obtaining Memory Samples
<img width="898" alt="image" src="https://user-images.githubusercontent.com/72620926/220256600-c9bc0af5-b7b0-47c0-95a2-f820c49302f7.png">

Những thông tin để làm những câu này đều có ở phần lý thuyết

**What memory format is the most common?**

> The .raw format is one of the most common memory file types you will see in the wild.

**The Window's system we're looking to perform memory forensics on was turned off by mistake. What file contains a compressed memory image?**

> hiberfil.sys, better known as the Windows hibernation file contains a compressed memory image from the previous boot. 

**How about if we wanted to perform memory forensics on a VMware-based virtual machine?**

> VMware - .vmem file

## Task 3 - Examining Our Patient
### Running the imageinfo command in Volatility will provide us with a number of profiles we can test with, however, only one will be correct. We can test these profiles using the pslist command, validating our profile selection by the sheer number of returned results. Do this now with the command `volatility -f MEMORY_FILE.raw --profile=PROFILE pslist`. What profile is correct for this memory image?
Chạy dòng lệnh "vol.py -f cridex.vmem imageinfo" để xem thông tin những profile cần sử dụng.

<img width="851" alt="Screenshot_20230221_013450" src="https://user-images.githubusercontent.com/72620926/220266177-5450b81f-06e4-45d9-a4a4-9eb98de26203.png">

Ở phần suggested profile có 2 cái là WinXPSP2x86 và WinXPSP3x86, thử đáp án thì câu trả lời là: WinXPSP2x86

<img width="919" alt="image" src="https://user-images.githubusercontent.com/72620926/220266445-2de6bbb3-0508-4b1d-8b3d-116ebf2649c2.png">

### Take a look through the processes within our image. What is the process ID for the smss.exe process? If results are scrolling off-screen, try piping your output into less
Chạy dòng lệnh "vol.py -f cridex.vmem --profile=WinXPSP2x86 pslist" để xem processes.

<img width="750" alt="image" src="https://user-images.githubusercontent.com/72620926/220266600-20f6d6b1-0af7-473f-b338-9eee5b2e3e93.png">

Nhìn ở dòng cuối trong hình thì thấy được process ID (PID) của smss.exe process là 368

<img width="885" alt="image" src="https://user-images.githubusercontent.com/72620926/220266860-138bebdc-886e-4a50-aea7-89396db8c879.png">

### It's fairly common for malware to attempt to hide itself and the process associated with it. That being said, we can view intentionally hidden processes via the command `psxview`. What process has only one 'False' listed?
Chạy dòng lệnh "vol.py -f cridex.vmem --profile=WinXPSP2x86 psxview" để xem những processes bị cố ý giấu đi.

<img width="940" alt="image" src="https://user-images.githubusercontent.com/72620926/220267050-40bc1d06-1979-4300-a4f2-f5971a79ae09.png">

Và thấy rằng chỉ có phần csrss.exe là có duy nhất 1 cái false.

<img width="891" alt="image" src="https://user-images.githubusercontent.com/72620926/220268056-1be12cd6-48da-4298-864d-7e5b03acb963.png">

### In addition to viewing hidden processes via psxview, we can also check this with a greater focus via the command 'ldrmodules'. Three columns will appear here in the middle, InLoad, InInit, InMem. If any of these are false, that module has likely been injected which is a really bad thing. On a normal system the grep statement above should return no output. Which process has all three columns listed as 'False' (other than System)?
Chạy dòng lệnh "vol.py -f cridex.vmem --profile=WinXPSP2x86 ldrmodules". Ngoài system thì chỉ có csrss.exe là có cả 3 cột đều false.

<img width="941" alt="image" src="https://user-images.githubusercontent.com/72620926/220278988-1babcbe2-e8ce-4eb2-ae7d-074c6036dfcb.png">

Note: em lỡ nhập thêm "ds" ngay sau khi submit nên không sửa lại được nữa, chứ câu trả lời là : "csrss.exe".

<img width="893" alt="image" src="https://user-images.githubusercontent.com/72620926/220279604-b7b26181-9316-4d7c-8caf-737dce0851a6.png">

### Injected code can be a huge issue and is highly indicative of very very bad things. We can check for this with the command `malfind`. Using the full command `volatility -f MEMORY_FILE.raw --profile=PROFILE malfind -D <Destination Directory>` we can not only find this code, but also dump it to our specified directory. Let's do this now! We'll use this dump later for more analysis. How many files does this generate?
Tạo 1 thư mục tên là "tmp" sau đó chạy lệnh " vol.py -f cridexmemdump/cridex.vmem --profile=WinXPSP2x86 malfind -D ./tmp". 

Mở thư mục tmp ra thì thấy có 12 items

<img width="888" alt="image" src="https://user-images.githubusercontent.com/72620926/220289299-037dad5a-9daf-41f7-bb10-dcfdcf90828f.png">

### Now that we've seen all of the DLLs running in memory, let's go a step further and pull them out! Do this now with the command `volatility -f MEMORY_FILE.raw --profile=PROFILE --pid=PID dlldump -D <Destination Directory>` where the PID is the process ID of the infected process we identified earlier (questions five and six). How many DLLs does this end up pulling?
Tạo thư mục "tmp2" sau đó chạy lệnh "vol.py -f cridexmemdump/cridex.vmem --profile=WinXPSP2x86 --pid=584 dlldump -D ./tmp2".

Mở thư mục tmp 2 ra thì có 12 items

<img width="891" alt="image" src="https://user-images.githubusercontent.com/72620926/220289724-a4272e23-07c8-47bf-b159-c8e640a9ac54.png">

## Task 4 - Post Actions
![image](https://user-images.githubusercontent.com/72620926/220412361-74190957-54ec-4735-8658-596e8343f74b.png)

Tra gg thì biết được cridex là malware.

<img width="887" alt="image" src="https://user-images.githubusercontent.com/72620926/220412188-4a2d853d-f5fc-491e-9f3f-b20582fde8bb.png">

# Redline
## Task 1 - Introduction
<img width="898" alt="image" src="https://user-images.githubusercontent.com/72620926/220412845-a24183a2-36ef-496e-9b32-d4f3eb5a2561.png">

## Task 2 - Data Collection
### What data collection method takes the least amount of time?
> Standard Collector - this method configures the script to gather a minimum amount of data for the analysis. This is going to be our preferred method to collect data in this room. It is also usually the fastest method to collect the data you need. It takes only a few minutes to complete.

<img width="896" alt="image" src="https://user-images.githubusercontent.com/72620926/220413235-a9347cd3-1a78-4f7b-9acf-94623baee0ac.png">

### You are reading a research paper on a new strain of ransomware. You want to run the data collection on your computer based on the patterns provided, such as domains, hashes, IP addresses, filenames, etc. What method would you choose to run a granular data collection against the known indicators?
> IOC Search Collector (Windows only) - this method collects data that matches with the Indicators of Compromise (IOCs) that you created with the help of IOC Editor. You will choose this method if you want to run the data collection against known IOCs that you have gathered either through threat intelligence (data feed or narrative report), incident response, or malware analysis. You imported them into IOC Editor. We'll look at the IOC Editor a bit further in the next task.

<img width="897" alt="image" src="https://user-images.githubusercontent.com/72620926/220414364-a1453322-dd85-4869-9fe6-40199821dda0.png">

### What script would you run to initiate the data collection process? Please include the file extension. 
![image](https://user-images.githubusercontent.com/72620926/220416242-f8aa1d65-b5f7-4be4-9fea-9e43f2e73c93.png)

Cả extention sẽ là "RunRedlineAudit.bat"

<img width="897" alt="image" src="https://user-images.githubusercontent.com/72620926/220416474-f193d851-8315-464d-bc85-8f93a03f2fe4.png">

### If you want to collect the data on Disks and Volumes, under which option can you find it? 
<img width="653" alt="image" src="https://user-images.githubusercontent.com/72620926/220417156-9533bedc-f0b3-4b4f-aadd-d2526a36d4f6.png">

<img width="907" alt="image" src="https://user-images.githubusercontent.com/72620926/220417039-f74214ab-9370-4bdc-82c6-3c035232f94c.png">

### What cache does Windows use to maintain a preference for recently executed code? 
Cái này tra gg là ra.

<img width="903" alt="image" src="https://user-images.githubusercontent.com/72620926/220418149-4e1808cf-22a3-4b78-9617-883e2b74e098.png">

## Task 3 - The Redline Interface
<img width="897" alt="image" src="https://user-images.githubusercontent.com/72620926/220433608-36734169-bb93-4e90-8ecb-e109c992b2a3.png">

> System Information: this is where you will see the information about the machine, BIOS (Windows only), operating system, and user information.

## Task 4 - Standard Collector Analysis
### Provide the Operating System detected for the workstation.
<img width="893" alt="image" src="https://user-images.githubusercontent.com/72620926/220436895-8d5d0995-d981-4a3b-941b-05254844c9e4.png">

Vào phần system information tab và cuộn xuống thì sẽ thấy
### Provide the BIOS Version for the workstation.
<img width="897" alt="image" src="https://user-images.githubusercontent.com/72620926/220437154-57e14171-fca8-4288-9a8f-ba4ae399e719.png">

Vẫn ở trong phần system information đó

<img width="354" alt="image" src="https://user-images.githubusercontent.com/72620926/220437249-13bb755b-7d81-4d9b-baf3-dea69a5173b3.png">

### What is the suspicious scheduled task that got created on the victim's computer? 
Vào phần task và tìm cái tên khả nghi
<img width="448" alt="image" src="https://user-images.githubusercontent.com/72620926/220437639-3baf6e26-c32e-47ad-b24a-047cf4701b3e.png">

<img width="892" alt="image" src="https://user-images.githubusercontent.com/72620926/220437804-a4ce175f-de2c-40fb-801c-4ca15531c9a4.png">

### Find the message that the intruder left for you in the task.
Đọc phần comment của ảnh phía trên (trong phần task), comment đó chính là message cần tìm.

<img width="904" alt="image" src="https://user-images.githubusercontent.com/72620926/220438104-54ea1bc2-75ef-4344-b66b-20882215b151.png">

### There is a new System Event ID created by an intruder with the source name "THM-Redline-User" and the Type "ERROR". Find the Event ID #.
Vào phần Event Logs và tra "THM-Redline-User" sẽ thấy được file cần tìm có type "error".

<img width="450" alt="image" src="https://user-images.githubusercontent.com/72620926/220438637-dcf075a1-fabc-4cb1-983b-60259078c8e5.png">

Để ý thấy EID là 546.

<img width="891" alt="image" src="https://user-images.githubusercontent.com/72620926/220438753-2ad648f8-a693-4e5b-93c6-284086ed5188.png">

### Provide the message for the Event ID.
Vẫn ảnh câu phía trên, để ý phần message

<img width="894" alt="image" src="https://user-images.githubusercontent.com/72620926/220438940-f11ddaf7-94f8-4aa3-9b24-09f37342c0a2.png">

### It looks like the intruder downloaded a file containing the flag for Question 8. Provide the full URL of the website.
Vào phần File download history và tìm file nào đó có vẻ ám muội thì tìm được file có tên là flag.txt

Dòng ở cột source URL là câu trả lời

<img width="898" alt="image" src="https://user-images.githubusercontent.com/72620926/220439423-48879f38-2c6a-4bbe-a58f-f437a4220343.png">

### Provide the full path to where the file was downloaded to including the filename.
Vẫn ở phần File download history copy phần Target directory và thêm \flag.txt.

<img width="891" alt="image" src="https://user-images.githubusercontent.com/72620926/220439654-11e79e9e-ab44-43c7-ae93-129119913495.png">

### Provide the message the intruder left for you in the file.
Mở file flag.txt đó ra thì nhận được "THM{600D-C@7cH-My-FR1EnD}" và đây là câu trả lời

<img width="889" alt="image" src="https://user-images.githubusercontent.com/72620926/220439870-b59a1733-b1ce-48be-afe4-989b2ee8fcfc.png">

## Task 5 - IOC Search Collector
### What is the actual filename of the Keylogger? 
<img width="278" alt="image" src="https://user-images.githubusercontent.com/72620926/220515835-1c30d3cd-711b-4030-b882-66b006c05bce.png">

<img width="894" alt="image" src="https://user-images.githubusercontent.com/72620926/220515891-5876588c-f1aa-4f41-a176-eaa3a6db6588.png">

### What filename is the file masquerading as? 
![image](https://user-images.githubusercontent.com/72620926/220516460-f59aafd9-f966-44f7-8263-1d500e426031.png)

Thấy phần owner đều giống nhau nên thử từng file một

<img width="899" alt="image" src="https://user-images.githubusercontent.com/72620926/220516617-bc973b4f-d12a-41db-8e1d-7ad191b9c0be.png">

### Who is the owner of the file?
Như ảnh phía trên, chú ý phần owner

<img width="897" alt="image" src="https://user-images.githubusercontent.com/72620926/220517132-ef4db93f-fb97-4183-a45b-24d671e6ce50.png">

### What is the file size in bytes? 
Nhìn cột size in bytes

<img width="907" alt="image" src="https://user-images.githubusercontent.com/72620926/220522224-ce9069f8-2234-4114-af40-721590d7dab7.png">

### Provide the full path of where the .ioc file was placed after the Redline analysis, include the .ioc filename as well
<img width="900" alt="image" src="https://user-images.githubusercontent.com/72620926/220522325-d791e150-031c-42b3-a7ae-03e54d0151f9.png">

## Task 6 - IOC Search Collector Analysis
### Provide the path of the file that matched all the artifacts along with the filename.
<img width="836" alt="image" src="https://user-images.githubusercontent.com/72620926/220561807-10f5e9eb-9f87-44ba-9cc0-c47137579221.png">

> answer: C:\Users\Administrator\AppData\Local\Temp\8eJv8w2id6lqN85dfC.exe

### Provide the path where the file is located without including the filename.
Như câu trên, chỉ cần bỏ tên file ở cuối

<img width="424" alt="image" src="https://user-images.githubusercontent.com/72620926/220562281-24f705b9-a3d9-4bc8-b64b-52a18307b2e5.png">

### Who is the owner of the file?
Ở hình phía trên có cột owner

<img width="428" alt="image" src="https://user-images.githubusercontent.com/72620926/220562529-771b9c68-4e3d-4cc6-b758-3e4219fad8c9.png">

### Provide the subsystem for the file.
nhấn chuột vào detail và sẽ thấy subsystem

<img width="850" alt="image" src="https://user-images.githubusercontent.com/72620926/220562842-ff348564-c973-4c3d-a6c5-9c868356a523.png">

<img width="432" alt="image" src="https://user-images.githubusercontent.com/72620926/220563650-75c3c483-308f-4f64-b9cf-78a81ef6f539.png">

### Provide the Device Path where the file is located
Ở ảnh phía trên cũng có thể thấy device path

<img width="433" alt="image" src="https://user-images.githubusercontent.com/72620926/220563794-1c2b5656-4af8-4816-bde9-74783a0f9f4f.png">

### Provide the hash (SHA-256) for the file.
<img width="436" alt="image" src="https://user-images.githubusercontent.com/72620926/220563908-8c6a98d4-0fe1-45f0-ac3a-3a67c7d0350d.png">

Vào windows powershell và nhập lệnh "Get-FileHash"

<img width="562" alt="image" src="https://user-images.githubusercontent.com/72620926/220564261-1ba2575b-b117-4b49-8e0e-cfbc48226c68.png">

### The attacker managed to masquerade the real filename. Can you find it having the hash in your arsenal? 
Search hash trong VirusTotal:

<img width="94" alt="image" src="https://user-images.githubusercontent.com/72620926/220564960-40af8965-714a-47e3-8fc6-e6e09da48057.png">

<img width="428" alt="image" src="https://user-images.githubusercontent.com/72620926/220565011-2ec96222-e938-43dc-9398-30f40778033d.png">

## Task 7 - Endpoint Investigation
### Can you identify the product name of the machine?
Vào phần system information và chú ý phần product name

<img width="439" alt="image" src="https://user-images.githubusercontent.com/72620926/220566862-9dd435e7-0934-481b-9d01-03f22addc3ea.png">

### Can you find the name of the note left on the Desktop for the "Charles"?
<img width="442" alt="image" src="https://user-images.githubusercontent.com/72620926/220569493-19033a52-f027-4612-a629-3956ee549f2c.png">

### Find the Windows Defender service; what is the name of its service DLL? 
<img width="429" alt="image" src="https://user-images.githubusercontent.com/72620926/220569625-22971227-ac02-4848-8599-01622bbf00f8.png">

### The user manually downloaded a zip file from the web. Can you find the filename? 
<img width="428" alt="image" src="https://user-images.githubusercontent.com/72620926/220569752-07cb0960-4fe4-456a-83c8-ec6baacdf898.png">

### Provide the filename of the malicious executable that got dropped on the user's Desktop.
<img width="427" alt="image" src="https://user-images.githubusercontent.com/72620926/220569883-4742c49b-0ae3-4565-994c-8cbf5704046b.png">

### Provide the MD5 hash for the dropped malicious executable.
<img width="428" alt="image" src="https://user-images.githubusercontent.com/72620926/220570187-ca565277-5f31-4bf6-ab76-e55677b0a79b.png">

### What is the name of the ransomware? 
<img width="439" alt="image" src="https://user-images.githubusercontent.com/72620926/220570223-e4228b67-fb1b-42f0-b1cb-e538d818c5d0.png">

# Disk Analysis & Autopsy
## Tasl 1 - Windows 10 Disk Image
### What is the MD5 hash of the E01 image?
<img width="466" alt="image" src="https://user-images.githubusercontent.com/72620926/220572679-e79cc37c-c0b1-4081-8a1e-bed619ffac1e.png">

Vào phần data source, sau đó chọn file HASAN2.E01 và chọn file metadata sẽ thấy dòng MD5

<img width="441" alt="image" src="https://user-images.githubusercontent.com/72620926/220573377-9d098fb4-1b48-4123-8848-f98a26375a71.png">

### What is the computer account name?
<img width="476" alt="image" src="https://user-images.githubusercontent.com/72620926/220574669-fe6d4b2a-02f9-49f7-9c69-e8660de58ecf.png">

Đẩu tiền chọn operating system information, rồi chọn SYSTEM là sẽ thấy tên

<img width="439" alt="image" src="https://user-images.githubusercontent.com/72620926/220574899-a73c7cf9-7d02-4929-aa83-0e9954b1fbf7.png">

### List all the user accounts. (alphabetical order)
<img width="476" alt="image" src="https://user-images.githubusercontent.com/72620926/220575450-ca3bc3e2-4078-4d43-9e8d-8ac635169d24.png">

Đầu tiên chọn operating system user account, kéo sang bên phải sẽ thấy cột user name, nhập tên theo thứ tự chữ cái là ra đáp án.

<img width="429" alt="image" src="https://user-images.githubusercontent.com/72620926/220577150-1c9967f4-1a55-4572-9d7c-9e57bcd1724b.png">

### Who was the last user to log into the computer?
<img width="480" alt="image" src="https://user-images.githubusercontent.com/72620926/220577584-dcce9e43-4966-401e-a841-1c8c4e1cf817.png">

Chú ý cột date accessed, người cuối cùng là sivapriya

<img width="432" alt="image" src="https://user-images.githubusercontent.com/72620926/220577831-a91e4632-6e1a-4529-8f14-a8b67259539b.png">

### What was the IP address of the computer?
Data Sources > HASAN2.E01 > Vol3 > Program Files (x86) > Look@LAN > irunin.ini

<img width="464" alt="image" src="https://user-images.githubusercontent.com/72620926/220580228-d6a4a6bf-569b-426a-8162-0e744186553b.png">

<img width="444" alt="image" src="https://user-images.githubusercontent.com/72620926/220578098-0b8a0d49-602e-4ba1-9333-8aef0ceed1eb.png">

### What was the MAC address of the computer? (XX-XX-XX-XX-XX-XX)
<img width="434" alt="image" src="https://user-images.githubusercontent.com/72620926/220580279-30c00d2e-2c56-4bff-87d6-3430ce4a0c0a.png">

### What is the name of the network card on this computer?
<img width="437" alt="image" src="https://user-images.githubusercontent.com/72620926/220581211-6facd8c7-978a-49b3-af65-101dec376149.png">

### What is the name of the network monitoring tool?
<img width="431" alt="image" src="https://user-images.githubusercontent.com/72620926/220581310-3ebb51ae-7e9e-4a10-a242-1846691de0a2.png">

### A user bookmarked a Google Maps location. What are the coordinates of the location?
<img width="426" alt="image" src="https://user-images.githubusercontent.com/72620926/220581424-90073bab-ce5f-4b40-b9fd-a5bfbbe089b8.png">

### A user has his full name printed on his desktop wallpaper. What is the user's full name?
<img width="430" alt="image" src="https://user-images.githubusercontent.com/72620926/220581547-fcd05e7f-1383-4985-bbaf-9f0fa333402c.png">

### A user had a file on her desktop. It had a flag but she changed the flag using PowerShell. What was the first flag?
<img width="428" alt="image" src="https://user-images.githubusercontent.com/72620926/220581703-731a9b36-6f4c-4f51-a3a9-63d5ae309b5c.png">

### The same user found an exploit to escalate privileges on the computer. What was the message to the device owner?
<img width="426" alt="image" src="https://user-images.githubusercontent.com/72620926/220581840-17a1aea0-51d8-4105-9368-197e3f40e945.png">

### 2 hack tools focused on passwords were found in the system. What are the names of these tools? (alphabetical order)
<img width="427" alt="image" src="https://user-images.githubusercontent.com/72620926/220581929-2795a5e1-60bc-4248-b225-592cdf80860b.png">

### There is a YARA file on the computer. Inspect the file. What is the name of the author?
<img width="434" alt="image" src="https://user-images.githubusercontent.com/72620926/220581998-66c51669-f960-45cf-8031-0f7cd517b8fa.png">

### One of the users wanted to exploit a domain controller with an MS-NRPC based exploit. What is the filename of the archive that you found? (include the spaces in your answer) 
<img width="425" alt="image" src="https://user-images.githubusercontent.com/72620926/220582101-36f10733-32aa-4feb-bd5b-289a1b5ec977.png">
