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

### Pen Test Tools Categories:   
Following Categories of pen test tools are identified for information gathering: Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

### OUTPUT:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/a8b3ea85-7980-4c63-bd0c-895b914012df)

### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
### OUTPUT:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/e496f0cb-713c-4eda-b4b6-780cb3a08744)

### Finding Hosting Company:
get further detail by using ip2location.com website.

### OUTPUT:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/b3e43374-a54c-445a-839e-54e696c99023)

### History of the website:
https://web.archive.org/

### Output:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/105b0b3f-82eb-4d42-8cf1-6242fd2d3071)
```
nc 172.17.52.118 80
```
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/32361312-c901-4c7c-b075-f523f76cb8e5)
### nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
### Output:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/ddfba70d-c8ac-44d6-9d6e-1012993b62de)
### Whatweb:
```
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
```
### Output:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/e618b707-70ec-46b4-a707-7ad0d5934427)
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/93d29576-e895-4c30-93ea-9baee2cc6b51)
### httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
### Output:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/27be5ba9-28f2-437e-a14c-ede7ae80f225)
### Tracing the Location:
TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
### Output:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/61231b8f-7c0d-4521-983c-07a50d158d41)
### UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
### Output:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/ded09be0-3008-4d39-987a-b9dea77050d9)

### ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
### Output:
![image](https://github.com/ASHWINKUMAR2903/InformationGathering/assets/119407186/936b122b-8633-45f9-a37d-1779f45afd03)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
