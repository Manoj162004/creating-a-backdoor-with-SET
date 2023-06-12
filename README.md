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

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for
Social Engineering Attacks

![sudoetoolkit](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/d509d5eb-4a42-4287-9af6-7e529de8b933)

It displays the following menu and select 2 for Website Attack Vectors:

![webattackvector](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/64865c66-1b3b-4e1e-9c57-d93b38fbc6e7)

The website Attack Vectors displays the following menu. In this menu3 for Credential
Harvester Attack Method is selected:

![credentialharvesterattack](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/d83ed04b-e117-4a4d-923a-69651c54fde3)

The Credential Harvester Attack Method displays the following menu. In this menu1 for
Web Templates is selected:

![webtemplates](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/467a3347-54ec-4e4d-9555-1badaf02733c)

It shows the following screen in which the ip address of the attacker need to be given
which is the default value:

![ipforattack](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/e3dcac41-253c-4372-ae3c-10922ea9fd18)

It shows the following screen in which the option Google can be selected:

![selectgoogle](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/6a714db4-2c9a-44fc-953f-f3a93ac29a17)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page.
The setup is done:

![set-80](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/01ff1d1c-17cf-4834-b077-61afcf549d68)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The
victim can enter the username and password

![fakegooglepage](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/a84174f9-39b4-4ca0-8608-15580da72c0d)

SET logs the information regarding the Google credentials:

![setlog](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/6390e2f9-7580-4bc2-a09c-26da41bbd6f4)

SET logs the information in the xml file under /root/.set directory:

![setloginxml](https://github.com/Manoj162004/creating-a-backdoor-with-SET/assets/120365042/71bd58c0-705e-4a84-9007-f3c0bb4ba9c8)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully.
