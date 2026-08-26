# 🔎 Password Capturing Using Wireshark

## 📌 Experiment No. 3

**Subject:** Digital Forensics  
**Experiment:** Password Capturing Using Wireshark

---

## 🎯 Aim

To capture and analyze network packets using Wireshark and examine credentials transmitted through HTTP traffic in a controlled laboratory environment.

---

## 📝 Description

Wireshark is a network capture analyzer that can capture information transmitted over a network, including usernames, email addresses, personal information, and other network data.

Protocols such as HTTP, FTP, and Telnet may transmit sensitive information that can be observed during packet analysis. :contentReference[oaicite:0]{index=0}

> ⚠️ **Note:** Perform this experiment only on systems and networks for which you have explicit authorization.

---

## 🛠️ Requirements

- Wireshark
- Windows / Linux Virtual Machine
- Network Connection
- Authorized Test Website
- Test Credentials

---

## ⚙️ Procedure

### Step 1: Start Wireshark

1. Open Wireshark.
2. Select the required network interface.
3. Start packet capturing.

### Step 2: Generate Test Traffic

Open an authorized test website and submit the test login credentials.

### Step 3: Analyze Captured Packets

Return to Wireshark after submitting the test credentials and analyze the captured packets. :contentReference[oaicite:1]{index=1}

### Step 4: Filter HTTP Traffic

Use the following display filter:

```text
http
<img width="1600" height="800" alt="WhatsApp Image 2026-08-26 at 4 08 59 PM" src="https://github.com/user-attachments/assets/b9c6e96a-fb43-4ff9-9598-9d78dca0b9f9" />
<img width="1600" height="843" alt="WhatsApp Image 2026-08-26 at 3 55 32 PM" src="https://github.com/user-attachments/assets/954cf2e6-8c75-405f-a088-9d0fc8ae579b" />
<img width="1600" height="849" alt="WhatsApp Image 2026-08-26 at 3 55 31 PM" src="https://github.com/user-attachments/assets/4224bbda-02ea-43ca-9f38-9fa4f4333538" />
<img width="1536" height="1024" alt="WhatsApp Image 2026-08-26 at 4 08 59 PM (1)" src="https://github.com/user-attachments/assets/89528926-4ec7-4abb-8c0e-2879a97725c4" />
