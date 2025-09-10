# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE

## AIM
To use **Autopsy Digital Forensics Tool** to retrieve deleted files from a disk image.

---

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tool**: [Autopsy Digital Forensics](https://www.autopsy.com/)  
- **Test Data**: Disk image file (`disk.dd`, `disk.img`, `.E01`)

---

## ARCHITECTURE DIAGRAM

<img width="577" height="785" alt="Screenshot 2025-08-22 151258" src="https://github.com/user-attachments/assets/0e9e4744-5534-4828-8715-d6210ba065c3" />

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  
<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/c1496db4-5a37-4f85-8863-413902245937" />


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="1920" height="1080" alt="Screenshot (39)" src="https://github.com/user-attachments/assets/a896ddd9-8291-4f6d-8e76-4b485fac39d9" />


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

- Select **Local Disk** → **next** 

<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/2d9c5a0e-3130-4d43-9df6-55edf8dcfa9d" />


- Select Disk → **Choose the VHD drive (`Drive1`)**


<img width="1920" height="1080" alt="Screenshot (40)" src="https://github.com/user-attachments/assets/5efdb33e-4c81-414b-9e3f-e87ee592125f" />

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  


<img width="1920" height="1080" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/18fe6cb1-345b-4837-9f46-9738c4618773" />



<img width="1920" height="1080" alt="Screenshot (43)" src="https://github.com/user-attachments/assets/756984fe-1396-4f4c-a942-02b5f1b89a35" />


<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/c1192a44-b6a9-4f34-9ea8-e9f647e3efe7" />


<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/95ea55c0-5810-4f00-80a0-4452e43315be" />


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :

#### Name - DHARAN ADITYA S
#### Reg. No. - 212223040035

### Folder before deleting the files


<img width="1920" height="1080" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/5bad8667-1867-4899-a992-406c8d07740b" />



### Folder after deleting the files

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7d8cb6a0-4119-4d48-acbd-02aefd69c2a0" />


### Folder after extracting the deleted images using autopsy

<img width="1920" height="1080" alt="Screenshot (48)" src="https://github.com/user-attachments/assets/c2b683db-279a-4e4b-a694-a8a919aaa652" />


## RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.

