# Cyber Threats

>[!note]
>This liste contains multiple cyber threats/attacks that you need to know when starting in cyber security.

>[!caution]
>These INFORMATIONS are for EDUCATIONAL PURPOSES ONLY, i DO NOT encourage any illegal actions. The best way to counter a hacker is to become a hacker. Hacking is a WEAPON, ONLY YOU will decide what to to whith this knowledge.

## Information Gathering

OSINT or Open Source INTeligence is not specifically a "Cyber-Attack" it's used in other domains like in the military to gather information on the enemy. But using OSINT can also be interesting for cyber criminals, as they can gather specific informations about some one or an organization and use them to plan realistic looking fishing emails.
Informations can also be gathered throught data breaches. If you don't want your personal data to leak, don't put them on the www (world wide web) or the internet. Databreaches are pretty common, they happened to Meta, Google and even governemental entitys that have a lot of informations about you.
Here is some data about you that can leak: Name, Age, Origines, Pro Career, Familly members, House Adress, Car liscence plate, Medical Information

Governement Information: Name, Age, Origines, Familly members, House Address, 

## Start attacks

Start attacks are ttacks usually used to start a cyber attack.

An attack against an orginization is usually a combination of different attacks.

### Phishing

The fishing attack is the most common attack in cyber security. Its pretty much impossible to be fishing proof because the attackes is not targeting a machine but a human.
The fishing attacks is also known as a Social engineering attack.

A random email from your bank, boss, government, etc...

Most of the time the mail puts you under pressure and panick mode. You start panicking and want to escape this feeling. It works better on people that hate being an "outlaw". So you start doing exactly what you shouldn't do, follow what the mail, message tells you to do.

### Social enginnering

Social engineering is a skill that allows hackers to manipulate their victims, either by usrping a known one's identity, making them feel under pressor or juste by making them think they're ehre to help them.

Social engineering is not a hardskill it's more of a softskill.

### Network scanning (NMAP)

Scanning a network is often seen as a "recon attack". This attack allows a hacker to map the majority of the network, one of the tools used is nmap. With a command you will be able to mark every most of the devices on a network: name, ip, mac, etc...
Scanning the network allows you to understand how it could work. You can gather a lot of informations that could be useful. Like the web server's IP, the

### DDOS or DOS

Distributed Denial Of Service or Denial Of Service attacks are mainly used to slow the servers or machines targeted down to the point where they don't work anywore. This methode is the "easiest" thechnical attack possible. You might of even DOSed yourself whith out even realising.
You have the Stove, Washing Machine, Electric car and pool pump running and all of a sudden everything stops working so you have to go check the electricity pannel. That is a DOS, attack you over loaded your electrical network so it went into security mode.

These sort of attacks are used to slow down a orginization witch doesn't seem much but blocking a big orginizations computer network for 1 hour or even 30 min, can cause serious money loss and damages.
They are also used for a diversion so that the attackers can launch other attacks in the background like social engineering attacks or injections.

### Injection Attacks

There are a tone of injection attacks: SQL injection, SSI injection, XPath injection, etc...

When a buglary takes place most of the time if not all the time, the enter points used to acces the house is a weak point. It can be a door, window, chimney, etc... They are hole, or features to the house that allow users to enter the house or to let the outside tempetures or wind come into the house. The chimney allows the smoke to escape. 

A website is no different. The weakpoints are the parts of the websites where the user can modify the structure. 

Let's take an SQL injection for example and let's break it into a comprehensible exercise.

First of all you need to undertand that even thow a computer can do rediculusly hard operations at the speed of light, a computer is really DUMB. 

Imagine you as a kid, your friend has a treehouse in his garden. To enter his tree house you need a "password" let's say the correct password is "1234". So we have this line: "1234" = "correct_password" THEN "allow acces"

You can try a brute force attack: 0001, 0002, 0003, etc... but your friend might get bored and juste stop you from trying. So instead of trying to find the password, you're going to modify your friends rule. Instead of saying a random password you are going to tell him any_password. Now the line looks like this: "any_password" = "correct_password" THEN "allow acces". Any password is the correct password so you can access the tree house. 

## Hacking Scenario

Scenario: You are a hacker and your goal is to make money, steal informations or both.

You want to steal some data from a large company called Megasoft. Your goal is to leak user information and sell them on the darkweb (these information can be used for phishing, account Hijacking, better ads targetting, etc...)

You need to have acces to the database server. Even if you had all the credentials, most companys use VPNs to connect from outside the LAN. You need to take control of a employees computer. You then think of a phishing attack. The thing is to naviguate in the company's network and stop security protocols you need an admin's session. So you are going to start by gathering information "OSINT". You are going to study the company, employees, etc... when you found the person you need you are going to send a spear phishing attack or a whale phishing attack. With your OSINT you are going to act like if you where an employee and start gathering information. Uber had a social engineering attack where a hacker sent pushes to unlock a users sension. He was pretending to be tech support and told the employee to click the unlock button to stop the spaming he said it was a bug. Now that you have acces to the employee's computer you are going to install a backdorr which will allow you to connect to his session with out going through the social engineering stuff again. Most company's have different admin accounts (decentralization). One person is a windows admin an other a sql database server an other a Linux admin etc... Let's say that with the OSINT or a lot of luck you have access to the database admin's account. You can know access the database and steal the information. 

You just stole user informations and can know resell them on the darkweb.

## Protect from this attack

Know let's see how a company can stop this attack. 

### Human

- Employee Sensibilization: *Teach your employees of the dangers from cyberthreats and phishing, you can plan fake phishing emails to train your employees to report suspicious emails.*
- 2FA/MFA: *2 Factor Authentification or Multi Factor Authentification is a good way to add an extra layer of security when your employees log-in to there computer session*  
- Password/Passphrase: *Set up password rules, letters, numbers, special characters, minimal length, changing the password after a certain ammount of time, etc...*
- 0trust: *Any devices that is not monitored by the company is considered as 0 trust: usb, pc, phone, storage systems, etc...*
- Physical security *Locked doors (keys, badges, etc...), cameras, sensors, gates, well protected site and datacenter.*

### Machines

- Good Network Architecture
- Layer 3 switches *configure Vlans, block all ports to unknowned MAC adresses.*
- Firewalls *Configure firewalls to block unnecessary websites.*
- Redundancee *multiply the routes to different equipements to have faster traffic and if a machine gets comprimised you can turn it off whith out risking loosing any data or money.*

## Full attack.
