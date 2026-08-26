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

FTK Imager provides a practical method for acquiring and preserving digital forensic evidence. It supports memory acquisition, disk imaging, multiple forensic image formats, and hash verification.

## Repository Structure

```text
Ex.No.1-FTK-Imager/
│
├── README.md
├── screenshots/
│   ├── capture-memory.png
│   ├── create-disk-image.png
│   ├── image-destination.png
│   └── hash-verification.png
│
└── report/
    └── Ex.No.1-FTK-Imager.pdf
<img width="500" height="472" alt=screenshot 2026-08-26 at 1 28 18 PM" src="https://github.com/user-attachments/assets/9d4e5737-b6fb-4fe5-860c-6f20d42b926f" />
<img width="505" height="390" alt=screenshot 2026-08-26 at 1 28 18 PM (1)" src="https://github.com/user-attachments/assets/221fabcf-45f4-44e2-ac4a-e950b55c4dbc" />
<img width="1438" height="1093" alt=screenshot 2026-08-26 at 1 28 40 PM" src="https://github.com/user-attachments/assets/ea2d43f8-dc63-4a22-80ef-e0f4797a1cb4" />
<img width="585" height="428" alt=screenshot 2026-08-26 at 1 28 19 PM" src="https://github.com/user-attachments/assets/bb2b5af7-47d7-4c9e-94be-6c56414f2dd6" />
<img width="575" height="426" alt=screenshot 2026-08-26 at 1 28 20 PM" src="https://github.com/user-attachments/assets/fe113a41-c9c8-4242-980a-fbf865cfb967" />
<img width="395" height="347" alt=screenshot 2026-08-26 at 1 28 20 PM (1)" src="https://github.com/user-attachments/assets/1a5dc811-8dba-40b3-9109-eb65ae3ddf94" />
<img width="465" height="355" alt=screenshot 2026-08-26 at 1 28 21 PM" src="https://github.com/user-attachments/assets/d662a286-72bd-4553-a5a5-004fc6ec6ec2" />
<img width="1448" height="1086" alt=screenshot 2026-08-26 at 1 28 39 PM" src="https://github.com/user-attachments/assets/1001e1d2-b481-40b4-a1a3-202282f5017c" />
<img width="470" height="355" alt=screenshot 2026-08-26 at 1 28 22 PM" src="https://github.com/user-attachments/assets/8b22e89e-5920-405b-958e-9d65434e74cd" />

