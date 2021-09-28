# RegistrationServer
pada praktikum kali ini pada materi registration server saya membuat sebuah project iot untuk mendeteksi adanya objek yang bergerak yaitu manusia maka akan ada condition yang dijalankan
-project ini menggunakan 1 switch, 1 server, 1 PC, dan 4 device home yaitu motion detector, webcam, light dan fan
-masing-masing device tersebut dihubungkan ke switch menggunakan kabel copper straight dan juga mengganti pada ip addressnya
    -ip address Server = 192.168.1.1
    -ip address PC = 192.168.1.2
    -ip address Webcam = 192.168.1.3
    -ip address Motion Detector = 192.168.1.4
    -ip address Light = 192.168.1.5
    -ip address Fan = 192.168.1.6
-selanjutnya pada server mengubah ip, username dan password pada iot monitor. disini saya menggunakan username "admin" dan password "zulfi". selanjutnya memasukkan condition seperti yang telah dibuat di packet tracer. 
-pada setting iot server tiap device diubah dicentang yang remote server. dan pada server address, username dan password diubah sesuai dengan yang telah dibuat di server.
-hasil dari project ini adalah jika motion detector mendeteksi terdapat objek yang bergerak maka secara otomatis light, fan dan webcam menyala. ini bisa berfungsi untuk penjagaan keamanan rumah maupun ruangan.
