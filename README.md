# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="1036" height="556" alt="632475191-22823815-37af-4cb2-89ea-7e2311357d61" src="https://github.com/user-attachments/assets/4f36f3e9-46a0-41f2-88b8-9a696a952c44" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="1033" height="556" alt="632475362-a9e9bc8d-6a63-452d-aa0d-e880784a99a0" src="https://github.com/user-attachments/assets/67460695-fa10-4166-b87a-153be074e45d" />


## History of the website:
## output
https://web.archive.org/
<img width="1033" height="507" alt="632475524-ef8d98c1-352c-4a46-a2ed-4f5f6832347b" src="https://github.com/user-attachments/assets/b618c845-6af6-4a26-ba76-96f77f9be6d2" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

<img width="1037" height="565" alt="632475582-75f74431-7ad7-4ca4-acdd-d62c591fecfd" src="https://github.com/user-attachments/assets/62d47a66-83d5-4dea-8db4-96f79c00cf51" />


## nmap:
###output
<img width="1035" height="522" alt="632475687-b7957627-a3e3-4f9b-a190-2cb3cc8f4249" src="https://github.com/user-attachments/assets/f79e2ae7-e47f-448e-b15c-6b304573a17d" />


## Whatweb
### output
<img width="1567" height="1004" alt="632475886-fd267d5c-46ce-475b-aded-71ed5bdf0740" src="https://github.com/user-attachments/assets/26428e64-d829-4e91-a030-83b4cf7605cc" />


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="1042" height="558" alt="632478071-1fb6eb09-1d9f-402c-a875-fc81b7e5da58" src="https://github.com/user-attachments/assets/4b00387d-48a6-49a1-9ac4-0dca8f370f60" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="1042" height="586" alt="632478135-fae84f01-740c-457a-a9ba-525f98da834a" src="https://github.com/user-attachments/assets/0d9bced5-d5cb-4b54-a767-088c1838a514" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output

<img width="1558" height="1010" alt="ChatGPT Image Ethical hacking" src="https://github.com/user-attachments/assets/0a8c19fb-73b1-4bb0-a68b-04c562a937d9" />





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
