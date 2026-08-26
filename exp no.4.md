# 📧 Email Header Analysis and Spoofing Detection using MHA

## Experiment No. 4

**Subject:** Digital Forensics  
**Experiment:** Analyze Email Headers and Detect Email Spoofing using MHA (Mail Header Analyzer)

---

## 🎯 Aim

To analyze email headers and detect possible email spoofing using Mail Header Analyzer (MHA).

---

## 🛠️ Tools Required

- MHA (Mail Header Analyzer)
- Gmail / Outlook / Yahoo Mail
- MXToolbox
- WHOIS / IP Lookup Tool

---

## 🔍 Procedure

### 1. Access Email Header

**Gmail:**
- Open the email.
- Click **More (⋮)**.
- Select **Show original**.

**Outlook:**
- Open the email.
- Go to **File → Properties**.
- Find **Internet headers**.

**Yahoo:**
- Open the email.
- Click **More (⋮)**.
- Select **View raw message**.

### 2. Copy Email Header

Copy the complete email header for analysis.

### 3. Identify Important Header Fields

| Field | Purpose |
|---|---|
| `From` | Sender address |
| `To` | Recipient address |
| `Date` | Date and time |
| `Subject` | Email subject |
| `Return-Path` | Bounce address |
| `Received` | Email server path |
| `Message-ID` | Unique email identifier |
| `SPF` | Sender authentication |
| `DKIM` | Email integrity |
| `DMARC` | Authentication policy |

### 4. Analyze Received Fields

Check:

- Sending server
- Receiving server
- IP address
- Hostname
- Date and time

### 5. Check IP Address

Use WHOIS or an IP lookup service to determine whether the IP address belongs to the expected mail server.

### 6. Check SPF, DKIM and DMARC
<img width="1860" height="967" alt="Screenshot 2026-08-26 154639" src="https://github.com/user-attachments/assets/69d83630-dc16-41cb-8ea5-fdf95f914fa4" />
<img width="1537" height="537" alt="Screenshot 2026-08-26 154712" src="https://github.com/user-attachments/assets/b21da161-ab0d-4220-9a00-53363c4c2752" />
<img width="1706" height="871" alt="Screenshot 2026-08-26 154738" src="https://github.com/user-attachments/assets/7f61f6a2-1f46-41f4-af3e-6e017c07f242" />
<img width="858" height="160" alt="Screenshot 2026-08-26 154759" src="https://github.com/user-attachments/assets/4e11d7aa-5af1-4623-954e-634e9504efea" />
<img width="1427" height="417" alt="Screenshot 2026-08-26 154839" src="https://github.com/user-attachments/assets/8b876a58-4332-4968-82d4-e90b6dd6be8f" />
<img width="1875" height="890" alt="Screenshot 2026-08-26 155031" src="https://github.com/user-attachments/assets/c8fdea60-59db-4cd9-8350-4bf6c186d6da" />
<img width="1560" height="552" alt="Screenshot 2026-08-26 175529" src="https://github.com/user-attachments/assets/68fe923b-b4f1-4eae-a229-c35862d5af26" />
<img width="1885" height="842" alt="Screenshot 2026-08-26 175549" src="https://github.com/user-attachments/assets/631f45f9-3d98-4f7c-a0c5-13945de9a030" />
