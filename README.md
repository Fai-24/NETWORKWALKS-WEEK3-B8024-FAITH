# NETWORKWALKS-WEEK3-B8024-FAITH

# PASSWORD CRACKING
### Footprinting & Network Scanning Phases

**W3-PM-FINAL  |  CYBERSECURITY  |  NETWORKWALKS**

| Field | Detail |
|---|---|
| **Pentester Name (Cybersecurity Professional)** | **Ngozichukwu Faith Oluchukwu** |
| **Program/Batch** | B084-Networkwalks |
| **Date** | 18 November 2026 |
| **Modules completed** | W3-PM1 (Password cracking with JTR)<br>W3-PM2 (Password cracking with NETWORKWALKS TOOLS) |
| **Client/Target** | 1. Protected files (like PDF,ZIP and office document)<br>2. My locked PDF |
| **Permission secured from client?** | Yes |
| **Phases covered** | **Phase 1:** Hashing<br>**Phase 2:** Cracking |

# 1. Liability Disclaimer

I have performed these activities only on files  was given permission or files that I own myself. All these materials are for education and research purpose only. Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged.

# 2. Introduction

This report covers password cracking using JTR (W3 -PM1) and NETWORKWALKS tools (W3-PM2). One module covers the cracking of password using JTR and the other covers password cracking using the two free tool of network academy which is hash calculator and password cracker.g phase, so together they show how a file hash can be gotten and the hash used to get the password of a file. It is the Week 3 part of my ongoing internship program at Networkwalks.

Everything was done on a Windows PC with JTR John and JTR Johnny installed. Every step below includes the exact process used, the result I observed, a screenshot as evidennce.

# 3. Tools Used

The table below lists each tool used in this report and its purpose.


| Tool | Purpose |
|---|---|
| John the Ripper      | Password cracking tool                                                 |
| Jonnny               | The graphical version of John the Ripper                               |
| onlinehashcracker    | to find the hash of a file uploaded                                    |
| Hash calculator      | to find the hash of a file uploaded                                    |
| Password cracker     | Hash every word in a wordlist and match it against a PDF password hash.|


# 4. Activities Performed

## 4.1 Password cracking with JTR

I cracked the password of attached PDF file (My locked PDF2.pdf) using JTR JOHN and JTR JOHNNY tools on my windows PC. 

First, I downloaded the John the Ripper from the official website on my windows PC

I then downloaded the Johnny GUI from the official website.

Using  an encrypted PDF file downloaded to my PC i opened the hash website and uploaded the pdf file to find the its hash.

I saved and copied the hash value and saved it as a text file

Finally, I opened johnny again and , clicked on open password file, browse my text fle containing my hash value, clicked open and started a new attack, which took some time and the PDF file wpassword was cracked.

## 4.2 Password cracking with Neworkwalks tools
For the second activity, I used recovered the password of a locked PDF using Networkwalks Hash calculator and password cracker to find the password.

I first uploaded the locked PDF to the hash calculator to grt the hash, then paste that hash into the password cracker to find the password.

# 5. Recommendations

Based on the observations from these activities, I recommend the following security improvements:

1.  **Very Strong password are encouraged to be used**  
    The use of strong password are encoraged to personal secure files that does not need public access


# 7. Conclusion

During Week 3 of my Cybersecurity & Ethical Hacking internship, I completed practical activities password cracking.

In password cracking with JTR I used JTR john and JTR johnny to recover the password of a protected file.

In the password cracking with Networkwalks tools i recovered the password of the locked PDF using the Networkswalkks Hash calculator and password Cracker

The exercises helps me to learn how password cracking works and why it is important to use strong passwords for protection.
Finally i also learnt that encryption ia a two way functon while hashing is a one way function that scrambles plain text to produce a unique message digest.


# 8. Evidences Collected
*Screenshots collected as evidence during the activities are below:*

<img width="902" height="712" alt="Screenshot 2026-11-18 084915" src="https://github.com/user-attachments/assets/2252e847-4ca5-4780-bcae-1e5b01956c1c" />
<img width="940" height="922" alt="Screenshot 2026-11-18 084726" src="https://github.com/user-attachments/assets/19b37d82-6511-42db-a808-868d4d0b1266" />
<img width="948" height="924" alt="Screenshot 2026-11-18 084650" src="https://github.com/user-attachments/assets/8a2e1451-e406-49d2-9186-45ac92bfb067" />
<img width="562" height="798" alt="Screenshot 2026-11-18 081749" src="https://github.com/user-attachments/assets/4863537b-4af1-4f3f-af1a-b71b7d48cba6" />
<img width="613" height="797" alt="Screenshot 2026-11-18 082524" src="https://github.com/user-attachments/assets/3d5dc870-9a6f-475e-aa31-fcefef01c409" />






