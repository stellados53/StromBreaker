# Storm Breaker

**installation on kali linux**

- open root terminal.
- run `apt upgrade`.
- enter 'y' and then click 'enter', this could take a while.
- run `apt update`.
- run `cd /opt/`.
- now, 
```
git clone https://github.com/ultrasecurity/Storm-Breaker
```
![image](https://github.com/stellados53/Storm-Breaker/assets/142677726/b62c5f84-9ecb-4b0e-b4f3-def855c10bd8)

- now,
```
sudo install python3 python-resourses python-colorama python-util
```
- now run,
```
cd /opt/Storm-Breaker
```
- next,
```
sudo bash install.sh
```
![Screenshot 2023-08-30 033231](https://github.com/stellados53/Storm-Breaker/assets/142677726/7e1e089d-7d32-41b7-bd9c-f26ecaba3fb6)

- now,
```
sudo python3 -m pip install -r requirements.txt
```
- now run the program,
```
python3 st.py 
```
![Screenshot 2023-08-30 033207](https://github.com/stellados53/Storm-Breaker/assets/142677726/5a0ebad8-4bfe-4491-845b-b9906ed0c088)

<h3 align="center">...</h3>  

## installation of ngrok

**ngrok** is a software which makes the **localhost** website to the **global website** with a secure https.  
Follow the given steps below for the installation of ngrok :  
- Open firefox in kali linux.
- Open the following website,
```
https://ngrok.com/download
```
- click on `linux`. Then click `select`.
- then click `x84-64`.  
- click on `download`.

![Screenshot 2023-08-30 034001](https://github.com/stellados53/Storm-Breaker/assets/142677726/c0afc280-daad-42e9-8284-e45129fa3b37)

<h3 align="center">...</h3>  

- now open the root terminal and full screen it for the better usage,
- right-click the mouse and then select `split terminal vertically`.



- run the command,
```
sudo tar xvzf ~/Downloads/ngrok-v3-stable-linux-amd64.tgz -C /usr/local/bin
```
- Now again open the ngrok firefox website and create a account with your gmail in ngrok.
- Make sure that the account has to be __verified__.
- Now there we can see a step called "connect you account" and there exists a unique command line given below.

![image](https://github.com/stellados53/Storm-Breaker/assets/142677726/c635fa5b-63c8-43ab-83a2-ec75bc2c7328)

- Copy the command and paste it your terminal and then click  `enter`.
- Now run open terminal and run `ngrok http 2525`.

now comes most exiting part...
- Copy the link given by your root terminal and open it in the firefox

![Screenshot 2023-08-30 034422](https://github.com/stellados53/Storm-Breaker/assets/142677726/73bc7a5b-510c-4fb4-99c9-1d0908443e8f)

- A popup or the website appear for the login

`username`:`admin`  
`password`:`admin`

- The links given are your links that can be sent to the people
to know their location or to access their microphones or cameras😉.

![image](https://github.com/stellados53/Storm-Breaker/assets/142677726/eb01fd98-38f4-459f-83bb-c6e201aaa3fb)

- To look the images or the audio files...
- Open your file system > opt > Storm-Breaker > storm-web > images...


The job is done..
