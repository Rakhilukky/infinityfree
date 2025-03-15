# **InfinityFree API Bypass** 🚀  
**Bypass InfinityFree security restrictions & access the API without limitations!**  

[![PyPI Version](https://img.shields.io/pypi/v/infinityfree.svg)](https://pypi.org/project/infinityfree/)  
[![GitHub License](https://img.shields.io/github/license/yourusername/infinityfree)](https://github.com/yourusername/infinityfree/blob/main/LICENSE)  
[![GitHub Stars](https://img.shields.io/github/stars/yourusername/infinityfree?style=social)](https://github.com/yourusername/infinityfree/stargazers)  
[![GitHub Forks](https://img.shields.io/github/forks/yourusername/infinityfree?style=social)](https://github.com/yourusername/infinityfree/network/members)  

---

## **🔥 About**
**InfinityFree API Bypass** is a **Python module** that automates **bypassing security restrictions** on the **InfinityFree hosting platform**. It decrypts **AES-encrypted cookies**, solves **JS security challenges**, and allows smooth **GET/POST API requests**.  

### **✨ Features**
✅ **Bypass JavaScript security challenges** on InfinityFree  
✅ **AES-encrypted cookie decryption** for seamless API requests  
✅ **GET & POST request automation**  
✅ **Supports custom headers & cookies**  
✅ **Fast, lightweight, and easy to use**  

---

## **🛠 Installation**
Install the module using **pip**:  
```sh
pip install infinityfree
```

Or install directly from GitHub:  
```sh
pip install git+https://github.com/Rakhilukky/infinityfree.git
```

---

## **📌 Usage Example**
### **Basic GET Request**
```python
from infinityfree import Bypasse

# Make a bypassed GET request
response = Bypasse.get("https://example.com/protected-page")
print(response.text)
```

### **POST Request with Custom Headers & Cookies**
```python
custom_headers = {"User-Agent": "MyCustomAgent"}
custom_cookies = {"session_id": "abcd1234"}

response = Bypasse.post("https://example.com/api", headers=custom_headers, cookies=custom_cookies)
print(response.text)
```

---

## **🛡️ How It Works**
💡 **InfinityFree uses JavaScript challenges & encrypted cookies to prevent automated access.** This module:  
🔹 **Extracts & decrypts AES-encrypted security tokens**  
🔹 **Generates valid `__test` cookies** for authentication  
🔹 **Automatically redirects to the final page**  

---

## **📚 Supported Bypasses**
| Security Feature            | Bypassed? |
|-----------------------------|-----------|
| JavaScript Challenges       | ✅ Yes |
| AES Encrypted Cookies       | ✅ Yes |
| 403 Forbidden (Invalid Cookies) | ✅ Yes |

---

## **📖 Documentation**
📌 **Full documentation is available on GitHub:** [**Read the Docs**](https://github.com/yourusername/infinityfree/wiki)  

---

## **🛠 Troubleshooting**
### **1️⃣ "403 Forbidden" Error?**
✔️ **Check if your API request is correctly formatted**  
✔️ **Ensure your IP is not blocked by InfinityFree**  
✔️ **Try using a different User-Agent header**  

### **2️⃣ "Failed to extract values from HTML" Error?**
✔️ **InfinityFree may have updated its security.** Open an issue on GitHub!

---

## **🤝 Contributing**
💡 Found a bug or want to improve this module?  
✔️ **Fork this repo**  
✔️ **Submit a pull request**  
✔️ **Open an issue for bug reports & feature requests**  

---

## **📜 License**
🔓 **MIT License** – You’re free to use, modify, and distribute this project!  
Plese Give my Credits too !

---

### **⭐ If You Find This Project Useful, Give It a Star! ⭐**
👉 **[Click here to Star the Repo!](https://github.com/yourusername/infinityfree/stargazers)**  

---

### **🚀 Ready? Start Bypassing InfinityFree API Now! 🚀**  

## **🌍 Keywords**
To improve visibility on **GitHub & Google**, this repo uses the following keywords:  
🔹 **InfinityFree API bypass**  
🔹 **Bypass InfinityFree security**  
🔹 **Python InfinityFree module**  
🔹 **Automate InfinityFree login**  
🔹 **AES-encrypted cookie bypass**  
🔹 **Bypass free hosting restrictions**  

---
