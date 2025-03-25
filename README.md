
---

# Lazymux  

Lazymux is a tool that helps you to install and use multiple penetration testing and hacking tools on Android system with ease. It allows users to easily install and use a variety of popular tools such as Nmap, SQLMap, and Metasploit. The tool is simple to use, as you only need to type a command to install and use any of the tools. Lazymux is an open-source project and can be a very helpful tool for penetration testing and ethical hacking tasks.

### 🚀 Features  

✅ **Easy Tool Installation**  
- Install a single tool:  
  ```bash
  lzmx > set_install 1
  ```  
- Install multiple tools:  
  ```bash
  lzmx > set_install 1 2 3 4
  ```  
- Install all available tools:  
  ```bash
  lzmx > set_install @
  ```  

✅ **Custom Installation Directory**  
- Modify `lazymux.conf` to set your preferred installation path.  
- Example (`lazymux.conf`):  
  ```bash
  HOME = /sdcard
  ```  

### 📸 Screenshot  
<img src="core/lazymux_4.png">  

### 📌 Requirements  
- Python **3.x**  

### 🔧 Installation & Usage  
```bash
apt install python git  
git clone https://github.com/RKgroupkg/Lazymux-rk.git 
cd Lazymux  
python lazymux.py  
```  

### 👥 Credits  
- **Original Developer:** *Gameye98*  
- **Current Maintainers:** *Rkgroupkg, Phantom3192*  

---
