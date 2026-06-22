# Honey-pot

## Objective
[Brief Objective - Remove this afterwards]

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
[Bullet Points - Remove this afterwards]

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
1. I started by creating an ubuntu virtual machine in the vultr cloud and when creating the Virtual Machine I did not create any firewalls because I wanted anyone on the internet to connect or attack the honeypot
<img width="200" height="200" alt="creating vm" src="https://github.com/user-attachments/assets/8ab4dd44-feff-4d07-b17f-dae3cadaf26b" />

2.I opened powershell on my PC and I updated and upgraded my repositories
<img width="350" height="400" alt="updating and upgrading vm" src="https://github.com/user-attachments/assets/18dc30b0-9bb8-4788-86a8-05f5e25cf1a9" />


3.I created a new user because it is unsafe to use my root account
<img width="350" height="400" alt="adding jerry" src="https://github.com/user-attachments/assets/35124ea7-9e47-4b6b-a8db-937bdc75f92d" />

4.I added my new user (Jerry) into the sudo group so that he has admin priviledges
<img width="350" height="400" alt="su jerry" src="https://github.com/user-attachments/assets/e570853d-3774-44fa-a6a7-7aa44bf02e8d" />

5.Cloned the tpot github repository

<img width="350" height="400" alt="inside jerry acc" src="https://github.com/user-attachments/assets/99b659b0-5afa-4a53-ba29-828d79172382" />

6.I then installed the tpot standard repository and while installing it, it changed my SSH Port to 64295 meaning I can no longer SSH into my honey pot using the default port 22

<img width="350" height="400" alt="installing tpot" src="https://github.com/user-attachments/assets/3b974ee1-d32a-4340-905a-35cb1dbf07db" />

7. My standard tpot repository was installed and now I had to reboot and reconnect using a new SSH
 
<img width="350" height="400" alt="i think upgrading jerry" src="https://github.com/user-attachments/assets/1763aca4-cd5c-4bc5-9dd0-ab61c924d4b1" />

8.Here I was just trying to login with my default SSH and it did not work because the SSH Port was changed and I then logged in using the correct SSH

<img width="350" height="400" alt="ijo ohlistening to different" src="https://github.com/user-attachments/assets/edb17abc-dbfd-40d2-9f08-800a90c3fb67" />

9.I logged into the web GUI and used the IP address of the honeypot and this time I did not forget that the tpot web GUI listens on the new port number not that default one and it gave me an error and I clicked proceed

<img width="350" height="400" alt="warning advances" src="https://github.com/user-attachments/assets/15ac1f2e-d04d-4b13-8ee2-5073cab82d67" />

10.That is how I Installed tpot and it gave me so many options like cyberchef,Kibana but my personal favourite was the attack map that allowed me to see any devices that attacked my honeypot from all parts of the world

<img width="350" height="400" alt="created honeypot" src="https://github.com/user-attachments/assets/2a142979-c7f8-4db0-aac4-ec61afa6ed2c" />












