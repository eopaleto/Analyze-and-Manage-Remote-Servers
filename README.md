Section 14.2: Guided Exercise: Analyze and Manage Remote Servers

1. Open Lab Console Redhat dan mulai
   - `lab start support-cockpit`
   - `ssh student@servera`
   - `sudo systemctl enable --now cockpit.socket`
     
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/2e1c1207-7f51-4d9a-a75a-645b27e06064)

2. Kemudian buka browser firefox redhat anda dan ketik link berikut, kemudian scroll ke bawah dan klik `Accept and risk`
   -  `https://servera.lab.example.com:9090`
     
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/66624206-5e64-499c-b105-61fa8fcdd776)
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/c8c03cb7-96b1-4dbc-ac01-5ca8d42ae588)

3. Login dengan akun berikut :  
   - Username : **student**
   - Password : **student**

![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/aa558e0e-f51c-438d-922e-674c5d6e4a58)

4. Buka limit access atau untuk mengganti menjadi administrator.Klik `Limited access`

![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/77c74871-a752-4d0a-b4d6-8f157a9cada5)

5. Klik `Authenticate`

![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/1a8c5d40-d4e8-459b-acc0-f5ff78e6daae)

6. Masuk ke `Account` >> `Create New Account`

![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/b7d8e36b-deec-4513-a85d-c50e5cdb1518)

7. Isi akun sebagai berikut :
   - Full Name : **manager1**
   - Username  : **manager1**
   - Password  : **manager1**
   - Confirm   : **manager1**
     
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/fdb64867-0b85-4ac6-9c49-e9b789c31efc)
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/542fb099-5c2d-408e-b34a-1439e23ced21)

8. Buka `Terminal` >> `id manager1` >> `sudo usermod -aG wheel manager1` >> `id manager1`
   
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/f312818e-8ea1-4496-903a-5b1da3fd44ab)

9. Masuk ke `Service` >> cari filter dengan nama `psacct`, kemudian klik yang biru
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/0afd400a-6c4d-4aca-a390-2b6f9301e3a1)

10. Active kan server psacct 
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/29b33144-db48-496b-a93c-fd20c964b5b0)

11. Log out dan buka terminal linux Redhat, kemudian akhiri dengan perintah:
    - `exit`
    - `lab finish support-cockpit`
      
![image](https://github.com/eopaleto/Analyze-and-Manage-Remote-Servers/assets/126212773/e694037f-5882-47ce-8556-fda15516a709)

***SELESAI***
