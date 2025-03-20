# Configure-Active-Directory Domain Controller
The AD DS role has been installed in your Windows Server 2019, 

# Configure-Active-Directory Domain Controller. 

Let’s go back to Server Manager and start the configuration.

1- **Back in Server Manager**

You should see a yellow exclamation mark by the notifications flag in the top-right corner. Click it and then click Promote this server to a domain controller

![ad-9](https://github.com/user-attachments/assets/b3321d3e-b12d-465c-8769-416b0233d0bb)

**In the Active Directory Domain Services Configuration Wizard dialog**

Check Add a new forest under Select the deployment operation and type the Fully Qualified Domain Name (FQDN) for your new AD forest. 
I’m going to use Testlab.com for my AD domain name. 

2- **Click Next to continue**

![ad-10](https://github.com/user-attachments/assets/9001c6c3-082b-4ffb-9113-17b4e643920f)

On the Domain Controller Options screen, type and confirm a Directory Services Restore Mode (DSRM) password. You will need this if you want to restore AD from backup. **Click Next** to continue.

On the DNS Options screen, you can safely ignore the delegation warning and **click Next**.

On the Additional Options screen, click Next to accept the assigned NetBIOS name.

Click Next again on the Paths screen to accept the default database, log files, and SYSVOL folder locations

![ad-11](https://github.com/user-attachments/assets/cb9f5142-a2be-4348-9b81-ab8a19dc4f34)

**Now click Next on the Review Options screen.**

Click Install to configure AD on the server. The server will automatically reboot to complete the installation process.
![ad-12](https://github.com/user-attachments/assets/67a925ab-51df-4f06-81cd-c42c7e287be2)

**Now you are all done**

![ad-13](https://github.com/user-attachments/assets/ed7b297a-1c2e-433d-92ab-323c4af64313)

On the sign-in page, type administrator in the User name Type the password for the administrator account, 
which is the same as the password for the previous built-in administrator account, and press ENTER.



