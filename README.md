# 🪟 AWS Windows VM Deployment Project

## 🎯 Project Objective
Deploy a Windows Server VM on AWS EC2 and connect via RDP to gather system information using Command Prompt.

## 🛠️ Tech Stack
- **Cloud Provider**: AWS
- **Service**: EC2 (Windows Server)
- **Connection Protocol**: RDP (Remote Desktop Protocol)
- **Tools**: Command Prompt (CMD)

## 🚀 Quick Steps

### 1. Create Windows EC2 Instance
- Launch EC2 instance with Windows Server OS
- Configure security group to allow RDP (port 3389)
- Generate/download key pair (.pem file)

### 2. Connect via RDP
- Use the generated password from .pem file
- Connect using Windows Remote Desktop Connection
- Use public IP of EC2 instance

### 3. Gather System Information
Open Command Prompt and run:
```cmd
systeminfo
hostname
ipconfig
```

## 📁 Project Structure
```
AWS-windows-vm-project/
├── README.md
└── Project-Steps.txt
```

## 📋 Submission Requirements

### 📸 Required Screenshots:
1. **EC2 Instance Creation** - Showing Windows VM configuration
2. **RDP Connection** - Successful remote desktop connection
3. **System Information** - CMD output showing `systeminfo` command

### 🔗 URLs to Submit:
- GitHub Repository URL
- (Optional) Any additional documentation

## 💡 Pro Tips
- Choose appropriate instance type (t3.medium recommended)
- Ensure RDP port (3389) is open in security group
- Save the key pair file securely
- Take clear screenshots of each step

## 🎉 Success Criteria
- ✅ Windows VM successfully created in AWS
- ✅ RDP connection established
- ✅ System information gathered via CMD
- ✅ All screenshots and files pushed to GitHub

---
