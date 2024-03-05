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

### PEN TEST TOOLS CATEGORIES:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
### OUTPUT:
![1](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/4b2f493d-eb4b-4015-afb3-22242e1d6e0a)

### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
### OUTPUT:
![2](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/92b01d13-182a-4e64-a773-0536bb1a26bb)

### Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT
![3](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/58420a06-385c-402f-8bfd-ca8aefee584e)

### History of Website:
## OUTPUT:
![4](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/695ea1d6-8c1c-49d8-a5ef-f20988f63900)

## WEB SERVER FINGERPRINT
## NETCAT:
```
nc 172.17.52.118 80
```
## OUTPUT:
![5](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/4a65346e-812c-42b1-9cfd-c3ecf0415570)

## namap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## OUTPUT:
![6](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/983c8914-143d-452e-a3b4-643f77707044)

### Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## OUTPUT:
![7](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/69dcd9f3-7632-4eba-b78d-37f7e45ece22)

### httprint:InformationGathering:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## OUTPUT:
![8](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/6bb8391a-ac49-46a7-a0ce-10317130b9c5)
## Tracing the Location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## OUTPUT:
![9](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/8bc8b788-708c-4f11-8ecc-835f4166678b)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## OUTUT:
![10](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/364d334b-6a90-4692-bd46-17b461252e62)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## OUTPUT:
![11](https://github.com/Nandhinijaya/InformationGathering/assets/121998147/8836c1a0-788b-47be-b0af-0302833199c9)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
