# Ex. No. 1: Evidence Acquisition Using AccessData FTK Imager

## Aim

To acquire volatile and non-volatile digital forensic evidence using FTK Imager.

## Tool Used

- FTK Imager
- Platform: Windows
- Domain: Digital Forensics

## Objectives

- Acquire volatile memory (RAM).
- Acquire non-volatile memory (hard disk).
- Create forensic disk images.
- Verify the integrity of acquired evidence using hash values.

## 1. Volatile Memory Acquisition

### Steps

1. Open **FTK Imager**.
2. Select **Capture Memory**.
3. Select the destination folder.
4. Optionally include the Windows pagefile.
5. Start the memory acquisition.
6. The acquired memory is saved with the `.mem` extension.

### Pagefile

The Windows `pagefile.sys` can contain valuable information and may be included during volatile-memory acquisition.

## 2. Non-Volatile Memory Acquisition

### Steps

1. Open **FTK Imager**.
2. Select **Create Disk Image**.
3. Select the required source.
4. Select **Physical Drive**.
5. Select the drive to acquire.
6. Click **Finish**.
7. Enter the case details.
8. Select the image destination and filename.
9. Configure the image fragment size.
10. Enable **Verify images after they are created**.
11. Click **Start** to begin acquisition.

## Image Formats

| Format | Description |
|--------|-------------|
| Raw (dd) | Raw image format commonly used by analysis tools. |
| SMART | Image format designed for Linux file systems. |
| E01 | Proprietary compressed forensic image format. |
| AFF | Advance Forensic Format for forensic disk imaging. |

## Evidence Integrity

The **Verify images after they are created** option verifies hash values after image creation. This helps ensure the integrity of the acquired evidence.

After acquisition, FTK Imager creates a text file containing acquisition information, and the hash values are matched.

## Write Blocker

A **write blocker** provides read-only access to an evidence disk and helps prevent modification of the original evidence during forensic acquisition.

## Result

Volatile memory and non-volatile disk evidence were acquired using **FTK Imager**, and the acquired image integrity was verified using hash values.

## Conclusion

FTK Imager provides a practical method for acquiring and preserving digital forensic evidence. It supports memory acquisition, disk imaging, multiple forensic image formats, and hash verification
<img width="500" height="472" alt="WhatsApp Image 2026-08-26 at 1 28 18 PM" src="https://github.com/user-attachments/assets/4696c419-3ff9-4b35-99db-05a02e34f470" />
<img width="505" height="390" alt="WhatsApp Image 2026-08-26 at 1 28 18 PM (1)" src="https://github.com/user-attachments/assets/4ae031f2-fc83-47b1-bbaf-9ad9437f4a4b" />
<img width="1438" height="1093" alt="WhatsApp Image 2026-08-26 at 1 28 40 PM" src="https://github.com/user-attachments/assets/bf5c83f4-9b52-494a-b32f-cf6a7899cb5c" />
<img width="585" height="428" alt="WhatsApp Image 2026-08-26 at 1 28 19 PM" src="https://github.com/user-attachments/assets/5116f72f-247d-451f-89b7-0f45cb921d6a" />
<img width="575" height="426" alt="WhatsApp Image 2026-08-26 at 1 28 20 PM" src="https://github.com/user-attachments/assets/0a09c75e-6972-4c69-9eca-f13fc264a002" />
<img width="395" height="347" alt="WhatsApp Image 2026-08-26 at 1 28 20 PM (1)" src="https://github.com/user-attachments/assets/3e463f3c-4871-4adf-bff6-5037ac55a85c" />
<img width="465" height="355" alt="WhatsApp Image 2026-08-26 at 1 28 21 PM" src="https://github.com/user-attachments/assets/d30a277a-ddd4-4b2e-8619-d9c701e63249" />
<img width="1448" height="1086" alt="WhatsApp Image 2026-08-26 at 1 28 39 PM" src="https://github.com/user-attachments/assets/fa5ea0bc-9f78-483f-83e3-370c734bbf61" />
<img width="470" height="355" alt="WhatsApp Image 2026-08-26 at 1 28 22 PM" src="https://github.com/user-attachments/assets/8166f302-02cf-4dd8-b26a-fc518b4304ec" />
