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
## OUTPUT

<img width="1712" height="896" alt="Screenshot 2026-09-02 103045" src="https://github.com/user-attachments/assets/811c5ac3-5f36-4411-a235-b32019d73c67" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1712" height="908" alt="Screenshot 2026-09-02 103110" src="https://github.com/user-attachments/assets/1f9ae121-70aa-485a-9fa3-702763ce7399" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1716" height="913" alt="Screenshot 2026-09-02 103132" src="https://github.com/user-attachments/assets/705c2f69-3921-49a5-9c30-21eb03b31492" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1712" height="915" alt="Screenshot 2026-09-02 103156" src="https://github.com/user-attachments/assets/4aedc586-d6a1-4721-8932-5955eb789873" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="1713" height="913" alt="Screenshot 2026-09-02 103213" src="https://github.com/user-attachments/assets/10046f86-2ad6-4e78-8e28-278521de4e9d" />


It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="1717" height="910" alt="Screenshot 2026-09-02 103232" src="https://github.com/user-attachments/assets/8a010985-2928-4da2-9378-e4db18e826b9" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1716" height="912" alt="Screenshot 2026-09-02 103258" src="https://github.com/user-attachments/assets/2f0b303f-c38f-4ed6-8700-45a1832870c1" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1712" height="592" alt="Screenshot 2026-09-02 103357" src="https://github.com/user-attachments/assets/694818b9-58cb-4463-a2db-17394853f7b0" />

SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1917" height="967" alt="Screenshot 2026-09-02 103504" src="https://github.com/user-attachments/assets/8e84ce61-a3d3-474f-b368-e704f44e5339" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT
<img width="1715" height="911" alt="Screenshot 2026-09-02 103550" src="https://github.com/user-attachments/assets/0a9296d1-085e-4b3b-8268-1e1c4608bb6e" />












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
