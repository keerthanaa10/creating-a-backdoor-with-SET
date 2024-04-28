# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows.

### Step 3:
Open terminal and try execute some kali linux commands.

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![7 1](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/28e7a558-5750-41a6-b4c8-577995b9df6d)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![7 2](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/6f63d23d-33a0-46d0-9be3-0eeabfc23d03)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![7 3](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/091ff1fe-5908-4d29-a395-b9add52bb0ef)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![7 4](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/8516d89a-c069-49fd-a9be-f85d71e3688e)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![7 5](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/52e30de1-1ece-44b0-bd3c-260cbc17c1b2)


It shows the following screen in which the option Google can be selected: 

![7 6](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/5f2094c2-01af-4faa-8b33-f66ac051bf11)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![7 7](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/63a79348-f9a4-46e0-95d7-5f3662c39860)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![7 8](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/40ec1b04-1b6b-4807-a7b4-4c2e7028cd34)


SET logs the information regarding the Google credentials: 

![7 9](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/47c9d2a8-5a00-4856-b8b5-635dab100026)


SET logs the information in the xml file under /root/.set directory:

![7 10](https://github.com/keerthanaa10/creating-a-backdoor-with-SET/assets/132996371/0c969b01-904a-4406-93b8-d64e38d2b35c)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
