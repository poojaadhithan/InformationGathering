
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
<img width="1910" height="953" alt="631705573-424cb1b0-2275-43ec-a88b-4f99b40bbd07" src="https://github.com/user-attachments/assets/267ef5fb-c16f-460d-8028-1b9a43e6295e" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

Output

facebook.com

<img width="803" height="298" alt="632731535-5753a687-40de-4310-bcac-2a2e8494b8c8" src="https://github.com/user-attachments/assets/b52af8ad-27e7-495b-905a-eca913a68339" />



## Finding Hosting Company
get further detail by using ip2location.com website.

Output

<img width="1917" height="911" alt="631710673-b34ad291-efc3-46fe-bb96-25d0cafe02a3" src="https://github.com/user-attachments/assets/ef490b52-7cc5-4b13-9d10-f81d48eb2963" />
<img width="1917" height="923" alt="631710537-da291759-5fff-4193-83f9-073b4f72ae8b" src="https://github.com/user-attachments/assets/97f9d632-b27d-4e0c-bdc2-9f0da6fcdc74" />




## History of the website:

 Output

https://web.archive.org/
<img width="1917" height="907" alt="632720723-1648cd38-78ea-4238-8e13-c55cf59fee4a" src="https://github.com/user-attachments/assets/799e5cc4-4fe6-4f01-8784-c26d1ab1483f" />
<img width="1917" height="973" alt="632720838-93f51757-fcca-42ef-a62d-0ed3cde624a5" src="https://github.com/user-attachments/assets/66e4cafc-f4a5-46e2-9a4e-e9de7fe16c81" />
<img width="1917" height="886" alt="632720895-8769b894-6185-4e12-aa1e-82e9fa4e1e75" src="https://github.com/user-attachments/assets/0768d612-0a73-48c3-88b0-921a0f9a4728" />




# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="752" height="466" alt="632726933-d385f7b1-0bec-4ae8-8f86-4674552f2bcf" src="https://github.com/user-attachments/assets/ef3fdcda-931d-49eb-80ab-9a0e88c49eed" />



## nmap:
Output

<img width="942" height="627" alt="632727248-0be9e5a5-7380-4e36-a7e3-ee26083805e4" src="https://github.com/user-attachments/assets/27bc1728-006e-417b-8352-71374afb3f68" />


## Whatweb
 Output

<img width="877" height="712" alt="632728592-a9223261-cd84-4c25-ae67-74f5661c21c0" src="https://github.com/user-attachments/assets/c1b04282-af66-4a98-99ae-cdbc00f8864f" />


## httprint
 Output

<img width="685" height="300" alt="632729792-bcd1da6c-862a-4c35-a031-b4e9de276bb7" src="https://github.com/user-attachments/assets/878c1820-8ebb-46a2-a2ed-e10ad9d7c960" />



# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com

Output

<img width="705" height="182" alt="632729955-da492fc2-b860-45bf-a1b0-02340661e17b" src="https://github.com/user-attachments/assets/87b82c68-95e2-4d5b-95f9-d376ef0c9a95" />


## UDP Traceroute:
sudo traceroute -U www.google.com

Output

<img width="656" height="587" alt="632730358-760a9798-2648-48e7-b17f-85786ec2af60" src="https://github.com/user-attachments/assets/d2ec8fa6-8577-4b51-b223-52ac58892414" />


## ICMP Traceroute:
sudo traceroute  www.google.com

Output

<img width="700" height="536" alt="632730593-655f647d-a636-418e-b10f-06941b64f432" src="https://github.com/user-attachments/assets/3216c8f5-3d60-4d7c-979a-19eac6e9b699" />

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
