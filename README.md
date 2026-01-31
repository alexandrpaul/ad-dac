<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# Active Directory Deployment and Configuration

This project demonstrates practical experience with **Windows Server 2022** and **Active Directory Domain Services**, covering full server deployment, administrator account configuration, role and feature setup, and promotion of a server to a Domain Controller with a new Active Directory forest and domain. It reflects real enterprise IT responsibilities, including secure credential management, domain configuration, and validation of user access within a network environment.

## Environments and Technologies Used

- **Windows Server ISO (Installation Media)**
- **Windows Server 2022**
-  **Active Directory Domain Services (AD DS)**
-  **Server Manager**
-  **Active Directory Domain Controller environment**
-  **Oracle VirtualBox**


## Skills Demonstrated

- Windows Server installation and initial configuration
- Administrator account setup and secure password management
- Active Directory Domain Services (AD DS) deployment
- Promoting a server to a Domain Controller
- Creating a new Active Directory forest and domain
- Domain Controller configuration and validation of domain credentials


## Tasks for this project

### 1. Install the Windows Server 2022
This step sets up the server environment, preparing the system for configuration, management, and deployment of essential services.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img1.png)



### 2. Set Admin Password
Assign a strong password to the Administrator account and finish configuration.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img2.png)



### 3. Windows Server Setup Complete
The server installation has completed successfully and is ready for use.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img3.png)



### 4. Update the PC Name (Recommended)
Right-click the Windows Menu and select **System**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img4.png)



Tap **Rename this PC**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img5.png)



Enter a standardized name, then proceed by clicking **Next**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img6.png)



Select **Restart now** to complete the update.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img7.png)



### 5. Server Manager Launches on Startup
Upon starting up, Server Manager will launch automatically.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img8.png)
If it does not, open the **Windows Menu**, search for Server Manager, and start the application manually.



### 6. Configure Roles and Features
In Server Manager, navigate to **Manage** > **Add Roles and Features**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img9.png)



### 7. Proceed from ‘Before You Begin’ Page
Click **Next** on the **Before You Begin** page to proceed.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img10.png)



### 8. Select Destination Server
Ensure the intended server is selected on the **Destination Server** page, then continue.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img11.png)



### 9. Enable Active Directory Domain Services
Select **Active Directory Domain Services** on the **Server Roles** page. A pop-up will appear.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img12.png)



### 10. Tap Add Features and Proceed
Choose **Add Features** and advance through the following prompts.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img13.png)



### 11. Begin Installation Process
Click **Install** on the **Confirmation** page. The process may take a few minutes to complete.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img14.png)



### 12. Promote Server to Domain Controller
Once the setup is complete, initiate **Promote this server to a domain controller**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img15.png)



### 13. Add a New Forest
Configure a new forest in **Deployment Configuration** by specifying the root domain name (e.g., *apstudios.local*) and selecting **Next**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img16.png)



### 14. Configure Domain Controller Options
On the **Domain Controller Options** page, accept the default settings, set a **DSRM password** for recovery, and click **Next**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img17.png)
Advance through the **DNS Options**, **Additional Options**, **Paths**, and **Review Options** pages by selecting **Next**.



### 15. Run Prerequisites Check and Install
Click **Install** on the **Prerequisites Check** page. The process may take several minutes, and the system will restart upon completion.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img18.png)



### 16. Log in with Domain Credentials
Once the system restarts, log in using your domain account, e.g., *APSTUDIOS\Administrator*.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img19.png)



<h2> Final Thoughts </h2>

<p> Through this project, I gained hands-on experience deploying and configuring a Windows Server 2022 environment, setting up the system for enterprise operations. The process included assigning secure administrative credentials, updating system identifiers, and launching Server Manager to configure roles and features. Enabling Active Directory Domain Services, promoting the server to a domain controller, and creating a new forest allowed for practical application of directory services, network authentication, and domain management best practices. Logging in with domain credentials confirmed the successful integration of the server into a managed IT environment. Moving forward, these experiences provide a strong foundation for advanced Windows Server administration and enterprise infrastructure management. </p>
