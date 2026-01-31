<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

# Active Directory Deployment and Configuration









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



*5.* Tap **Rename this PC**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img5.png)



*6.* Enter a standardized name, then proceed by clicking **Next**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img6.png)



*7.* Select **Restart now** to complete the update.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img7.png)



### 8. Server Manager Launches on Startup
Upon starting up, Server Manager will launch automatically.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img8.png)
If it does not, open the **Windows Menu**, search for Server Manager, and start the application manually.



### 9. Configure Roles and Features
In Server Manager, navigate to **Manage** > **Add Roles and Features**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img9.png)



### 10. Proceed from ‘Before You Begin’ Page
Click **Next** on the **Before You Begin** page to proceed.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img10.png)



### 11. Select Destination Server
Ensure the intended server is selected on the **Destination Server** page, then continue.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img11.png)



### 12. Enable Active Directory Domain Services
Select **Active Directory Domain Services** on the **Server Roles** page. A pop-up will appear.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img12.png)



### 13. Tap Add Features and Proceed
Choose **Add Features** and advance through the following prompts.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img13.png)



### 14. Begin Installation Process
Click **Install** on the **Confirmation** page. The process may take a few minutes to complete.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img14.png)



### 15. Promote Server to Domain Controller
Once the setup is complete, initiate **Promote this server to a domain controller**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img15.png)



### 16. Add a New Forest
Configure a new forest in **Deployment Configuration** by specifying the root domain name (e.g., *apstudios.local*) and selecting **Next**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img16.png)



### 17. Configure Domain Controller Options
On the **Domain Controller Options** page, accept the default settings, set a **DSRM password** for recovery, and click **Next**.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img17.png)
Advance through the **DNS Options**, **Additional Options**, **Paths**, and **Review Options** pages by selecting **Next**.



### 18. Run Prerequisites Check and Install
Click **Install** on the **Prerequisites Check** page. The process may take several minutes, and the system will restart upon completion.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img18.png)



### 19. Log in with Domain Credentials
Once the system restarts, log in using your domain account, e.g., *APSTUDIOS\Administrator*.

![Screenshot](https://github.com/alexandrpaul/ad-dac/blob/eac0e60437de11d8eed0c74f81faeb34bb5d7d6e/Screenshots/img19.png)
