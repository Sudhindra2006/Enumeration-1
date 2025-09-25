# Enumeration
Enumeration Techniques

## Name: Sudhindra.R
## Reg no: 212224240164
# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

<img width="1920" height="1080" alt="Screenshot (323)" src="https://github.com/user-attachments/assets/ca0f9b97-12e0-4c65-8de5-51731245d9f6" />



## filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
<img width="1920" height="1080" alt="Screenshot (324)" src="https://github.com/user-attachments/assets/8c0a51b6-5933-47b1-a725-a8cea2653b37" />





## intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

<img width="1577" height="872" alt="image" src="https://github.com/user-attachments/assets/3475fa44-02aa-4545-ba13-aa24d4bcf33b" />


## inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
<img width="1920" height="1080" alt="Screenshot (326)" src="https://github.com/user-attachments/assets/9d409a5d-0d0e-480f-bcba-4601d4c6d5ed" />





## intitle: 
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
<img width="1920" height="1080" alt="Screenshot (327)" src="https://github.com/user-attachments/assets/7d1ca4ab-83f0-413a-88d3-e0ef4363530c" />

## link:
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
<img width="1920" height="1080" alt="Screenshot (328)" src="https://github.com/user-attachments/assets/2e24581c-f929-45ae-9333-7b0039ac603f" />



## cache:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
<img width="1920" height="1080" alt="Screenshot (329)" src="https://github.com/user-attachments/assets/287b8b33-83d1-4e1e-b29a-b4da34ad6ee6" />

 
# DNS Enumeration


## DNS Recon

provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## OUTPUT:

<img width="1920" height="936" alt="dnsrecon" src="https://github.com/user-attachments/assets/d85db53a-ba64-4fa5-b99f-6202eb2c7a93" />






## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

## Output:

<img width="1920" height="936" alt="dnsenum" src="https://github.com/user-attachments/assets/28f3e1ce-9e68-476e-91be-9ae3baafaa23" />



## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
  
 ## Output:
 <img width="1920" height="936" alt="smtp" src="https://github.com/user-attachments/assets/669f40ed-63f4-4923-94cb-f0f680bd9a64" />


  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
<img width="1920" height="936" alt="nmap" src="https://github.com/user-attachments/assets/e6306e74-e9e9-4bb1-b3bc-ad9a4b762216" />


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

