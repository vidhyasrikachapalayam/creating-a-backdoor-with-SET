# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:
Install kali linux either in partition or virtual box or in live mode
### Step 2:
Investigate on the various categories of tools as follows:
### Step 3:
Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![image](https://github.com/user-attachments/assets/87193f12-06cb-4810-aa77-43c26128d5ec)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/99b8308f-28bb-49f5-84b6-c9e76ee69c7b)
The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/e48d5baf-c1a6-4f81-87f6-f852c86b8345)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/03661cf4-9095-49e6-aa11-077ceb0f1a81)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/user-attachments/assets/27a93b04-48ef-4872-9a4e-bb2534184cf7)
It shows the following screen in which the option Google can be selected:
![image](https://github.com/user-attachments/assets/b208083b-db11-4010-ac70-501986f2571f)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/user-attachments/assets/b93c7550-43bf-444a-a239-69f5d3918b70)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/e248fa0e-b426-4c12-b4ee-8cfaf0c52775)
SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/05f1a60e-06df-44ff-b690-1afc68631bac)
SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/f5c0e9ad-a390-4949-9275-20258dea343e)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
