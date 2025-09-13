# Using-the-Autopsy-retrieve-the-deleted-files

## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

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

<img width="1366" height="768" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/4e06db12-2a5d-408b-b157-c9bc57f123ce" />

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="1366" height="768" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/60c42dba-7592-42e0-be44-b6c4dec86494" />

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

<img width="737" height="389" alt="image" src="https://github.com/user-attachments/assets/6a622f44-2378-4a89-9e77-37a7b5a6ba2d" />

- Select **Local Disk** → **next** 

<img width="1366" height="768" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/42406b54-93b1-4675-8458-fd82b5c3d2b0" />

- Select Disk → **Choose the VHD drive (`Drive1`)**

<img width="1366" height="768" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/c5208aee-2e69-481d-b490-7311d9b2c5b5" />

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

<img width="1366" height="768" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/25123b5b-d9e0-4d89-9257-03f0f46a9c6b" />

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

<img width="1366" height="768" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/1c825643-ef5d-4429-a898-b2f4a3641104" />

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
<img width="1366" height="768" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/97cdfccf-5e7a-48bd-a7c2-5ddc4510b9c7" />

### Folder after deleting the files
<img width="1366" height="768" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/a8f00e6e-eedb-4a5c-9e0f-5a557cd7b1a9" />

### Folder after extracting the deleted images using autopsy
<img width="1366" height="768" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/146eb5d9-5c7d-4f1f-a4b8-76ee30dcb9c0" />

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
