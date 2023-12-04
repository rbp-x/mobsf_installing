# mobsf_installing
Install Mobile Security Framework

Install terlebih dahulu python 

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/d03c1af7-88aa-478c-b053-0287244ee512)

Kemudian install JDK menggunakan perintah seperti dibawah ini :

$ sudo apt install default-jdk

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/88c47608-6c8c-4a88-91d1-f76cfe2dbb66)

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/75951e76-2bb2-46ee-bd18-3113077d096e)

git clone mobSF

$ git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/d7440a40-592b-4924-9260-96616376b504)

Download selesai :

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/93c4d464-6a33-4208-baf8-008d24d1bc17)

Pindah ke direktori MobSF :

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/9f20c058-ed52-4520-9799-ace12056f04e)

Kemudian lakukan setup terhadap file mobSF setup.sh pada direktori tersebut :

$ sudo ./setup.sh

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/e7809602-cf28-41bf-941e-312ae67ed65a)

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/6933f018-2885-42be-8965-eb61b9b97f59)

Installation Complete

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/9277c1fb-400d-4bda-84f1-d543efd2ee31)

Jalankan MobSF dengan perintah :

$ ./run.sh 127.0.0.1:8000

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/cf2f02c9-27d0-44b1-be89-7dd8e2172a1e)

Jika menampilkan error seperti diatas, nggak perlu panik ! 

Cukup ketikan perintah :

$ sudo apt install gunicorn 

![image](https://github.com/rbp-x/mobsf_installing/assets/2045755/bbbf135c-1519-42b0-bba8-def96b291600)

Kemudian ulangi lagi : 

$ ./run.sh 127.0.0.1:8000



