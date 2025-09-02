# 🌐 Static Website Hosting on AWS EC2 (Windows Server 2019)

## 📌 Project Overview
This project demonstrates how I hosted a **static website** on an **AWS EC2 instance** using **Windows Server 2019 Base** and **IIS (Internet Information Services)**.  
It gave me hands-on experience with cloud infrastructure, server setup, and web hosting.

---

## 🚀 Steps I Followed
1. **Launched EC2 Instance**
   - Chose Windows Server 2019 Base AMI
   - Configured Security Groups (HTTP – Port 80, RDP – Port 3389)

2. **Connected via RDP**
   - Logged into the server using Remote Desktop

3. **Installed IIS**
   - Enabled IIS from *Server Manager → Add Roles and Features*

4. **Deployed Website**
   - Placed my website files in:  
     `C:\inetpub\wwwroot\`

5. **Accessed the Website**
   - Opened the site in browser using the **Public IPv4 address**

---
## 🔮 Future Improvements
- Attach an Elastic IP so that the website IP never changes  
- Configure a custom domain using Route 53  
- Enable HTTPS with AWS Certificate Manager  

---

## 🛠️ Technologies Used
- **Amazon Web Services (AWS EC2)**  
- **Windows Server 2019**  
- **IIS (Internet Information Services)**  
- **Static Website (HTML, CSS, JS)**  

---

⭐ *If you found this project useful, don’t forget to star the repo!*  

