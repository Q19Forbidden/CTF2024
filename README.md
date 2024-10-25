# CTF2024
CTF2024
Kịch bản: 
- Máy chủ web server bị  lỗi SQL Injection, dẫn đến lấy được DB, do cấu hình lỗi user này có quyền write file dẫn đến RCE. Server DB này nằm trong mạng lan Internal của công ty dẫn đến nó có thể bị lợi dụng làm bàn đạp tấn công lan trong mạng nội bộ. 
- Flag nằm ở các vị trí: 
+ Internet: 1. Máy WebServer: /user/flag.txt, /root/flag.txt
+ Internal: 
1. Postgresql, MySQL, MS SQL: /user/flag.txt, /root/flag.txt
2. File server: Nằm trong 1 file share nào đó.
3. Mail Server: Nằm trong mail CEO gửi admin1
4. CEO: /user/CEO/flag.txt; /root/flag.txt
5. Admin: /user/admin/flag.txt; /root/flag.txt
