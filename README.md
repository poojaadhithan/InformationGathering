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

OUTPUT:
<img width="1910" height="953" alt="631705573-424cb1b0-2275-43ec-a88b-4f99b40bbd07" src="https://github.com/user-attachments/assets/2c93d9fc-43f4-4db6-81a2-5c0ff85a1d9d" />



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

Output:

facebook.com

<img width="803" height="298" alt="632731535-5753a687-40de-4310-bcac-2a2e8494b8c8" src="https://github.com/user-attachments/assets/e4b3a1d3-9bfd-479d-8a3a-b0b6a8b67c0d" />


## Finding Hosting Company
get further detail by using ip2location.com website.

Output:
<img width="1917" height="911" alt="631710673-b34ad291-efc3-46fe-bb96-25d0cafe02a3" src="https://github.com/user-attachments/assets/9c4f48c0-f2c9-4978-9309-d6300b4151e8" />
<img width="1917" height="923" alt="631710537-da291759-5fff-4193-83f9-073b4f72ae8b" src="https://github.com/user-attachments/assets/4ad5c3f6-8d20-4cc0-8b93-62e558068551" />


## History of the website:

Output:

https://web.archive.org/
<img width="1917" height="907" alt="632720723-1648cd38-78ea-4238-8e13-c55cf59fee4a" src="https://github.com/user-attachments/assets/efc6dc1e-153a-47a0-8f74-e133bfa5ba61" />
<img width="1917" height="973" alt="632720838-93f51757-fcca-42ef-a62d-0ed3cde624a5" src="https://github.com/user-attachments/assets/560cfde5-be85-409b-ab10-977c4573d6e8" />
<img width="1917" height="886" alt="632720895-8769b894-6185-4e12-aa1e-82e9fa4e1e75" src="https://github.com/user-attachments/assets/482b9df5-7ba5-475e-9562-6564db58fdc2" />




# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

<img width="752" height="466" alt="632726933-d385f7b1-0bec-4ae8-8f86-4674552f2bcf" src="https://github.com/user-attachments/assets/0913b3cc-d385-4e99-951d-665ca061dd2a" />


## nmap:

Output:
<img width="942" height="627" alt="632727248-0be9e5a5-7380-4e36-a7e3-ee26083805e4" src="https://github.com/user-attachments/assets/2eb0efa2-f703-428f-b30c-8285be0176b6" />



## Whatweb
Output:
<img width="877" height="712" alt="632728592-a9223261-cd84-4c25-ae67-74f5661c21c0" src="https://github.com/user-attachments/assets/5a1963ce-9658-430c-a442-e3903aefb370" />



## httprint

Output:
<img width="685" height="300" alt="632729792-bcd1da6c-862a-4c35-a031-b4e9de276bb7" src="https://github.com/user-attachments/assets/5a218e7b-46fc-455d-be7d-e3c9efdf65d7" />





# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com

Output:
<img width="705" height="182" alt="632729955-da492fc2-b860-45bf-a1b0-02340661e17b" src="https://github.com/user-attachments/assets/f679d439-8b34-4e53-aab2-6d7f11d42c4c" />



## UDP Traceroute:
sudo traceroute -U www.google.com

Output:
<img width="656" height="587" alt="632730358-760a9798-2648-48e7-b17f-85786ec2af60" src="https://github.com/user-attachments/assets/235946d0-903b-41b2-9c6d-16eba7b1eaef" />




## ICMP Traceroute:
sudo traceroute  www.google.com

Output:
<img width="700" height="536" alt="632730593-655f647d-a636-418e-b10f-06941b64f432" src="https://github.com/user-attachments/assets/68e7c6ea-1b6c-4abb-bfce-2b22b2b88608" />







## RESULT:
The information gathering techniques tools/procedure were  identified successfully
