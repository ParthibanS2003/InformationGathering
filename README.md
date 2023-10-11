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
![ex](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/354f1ba4-87bd-493f-aad1-89b20d0ccb54)


### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
### OUTPUT:
![exx](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/b2227b29-a797-4baa-a96a-48cb8bdb68cf)

### Finding Hosting Company:
get further detail by using ip2location.com website.

### OUTPUT:
![ex3](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/95f05cfe-472b-4b5d-b0ed-2d3509c978b9)


### History of the website:
https://web.archive.org/

### Output:
![ex4](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/eeca4997-4163-4f55-a737-aca18940db12)

```
nc 172.17.52.118 80
```
![ex5](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/62349ad9-faaa-4f34-b9de-c1c6dd5f910d)

### nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
### Output:
##![ex7](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/4082880f-0b13-431d-bbe7-fbedc904d378)
# Whatweb:
```
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
```
### Output:
![ex8](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/bb267717-ee0e-49cc-8448-4ee08e3afba0)

![ex9](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/02933248-a9b4-4d4f-932f-0a022659c156)

### httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
### Output:
![ex10](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/9dbc5b03-333c-412f-9127-941fbebedf41)

### Tracing the Location:
TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
### Output:
![ex11](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/201fa258-066c-47ea-818a-5549eb14885c)

### UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
### Output:
![ex12](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/16488230-8584-433f-b094-2085ece71abb)


### ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
### Output:
![ex13](https://github.com/ParthibanS2003/InformationGathering/assets/123487519/05e33570-51cd-41e6-a387-7cf4cf1e674c)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
