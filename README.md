### **📜 Firstpoint Security.txt**  
This repository contains the `security.txt` file for **Firstpoint**, following the [RFC 9116](https://datatracker.ietf.org/doc/html/rfc9116) standard. It provides security researchers and ethical hackers with the necessary contact information for reporting vulnerabilities responsibly.

---

## **📂 Repository Contents**
- **`security.txt`** – The security contact file.  
- **`security.txt.sig`** – GPG-signed version of the `security.txt` file.  
- **`pgp-key.txt`** – The public PGP key used for encrypted communication.  

---

## **📩 Contact Information**
- **Security Contact Email:** [security@firstpoint.com.tr](mailto:security@firstpoint.com.tr)  
- **PGP Key:** Available in [`pgp-key.txt`](pgp-key.txt)  
- **Security Policy:** [firstpoint.com.tr/security-policy](https://firstpoint.com.tr/security-policy)  
---

## **🔑 How to Verify the Security.txt Signature**
To ensure the `security.txt` file is authentic and signed by **Firstpoint**, follow these steps:

### **1️⃣ Import the Public PGP Key**
```sh
gpg --import pgp-key.txt
```

### **2️⃣ Verify the Signature**
```sh
gpg --verify security.txt.sig security.txt
```

If you see a message like this, the file is **authentic** and signed by Firstpoint:

```
gpg: Signature made ... using RSA key 0xABCD1234EF567890
gpg: Good signature from "Firstpoint Security <security@firstpoint.com.tr>"
```

---

## **📌 What is security.txt?**
`security.txt` is a **standardized security contact file** that allows security researchers to report vulnerabilities in a responsible manner. It is placed under:

```
https://firstpoint.com.tr/.well-known/security.txt
```

This file helps **ethical hackers, security researchers, and developers** reach the right contact when they find potential security issues.

For more details, visit the official **RFC 9116** specification:  
📖 [https://datatracker.ietf.org/doc/html/rfc9116](https://datatracker.ietf.org/doc/html/rfc9116)

---

## **🛠️ Contributing**
If you notice any outdated information in this repository, feel free to submit a **pull request** or open an **issue**.

---

## **📜 License**
This repository is licensed under the **MIT License**.

---

This `README.md` will make it easy for **security researchers** and **developers** to understand the purpose of your `security.txt` repository. 🚀🔐
