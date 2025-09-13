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

<img width="737" height="389" alt="image" src="https://github.com/user-attachments/assets/ca3f4b05-17c6-47bf-afff-e2b8252c3100" />


- Select Disk → **Choose the VHD drive (`Drive1`)**

<img width="1920" height="1080" alt="Screenshot (312)" src="https://github.com/user-attachments/assets/6fdf53d7-550e-4562-a23a-c8519f91ff18" />


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
<img width="1920" height="1080" alt="Screenshot (315)" src="https://github.com/user-attachments/assets/20c8feb3-c1da-4a77-a5aa-d6b9656c5646" />

<img width="1920" height="1080" alt="Screenshot (313)" src="https://github.com/user-attachments/assets/43eaa3bd-ab40-4b04-8501-e8387783850c" />


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

<img width="1920" height="1080" alt="Screenshot (316)" src="https://github.com/user-attachments/assets/ef1668e1-6614-48e6-8f6f-12bab0901157" />


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
<img width="1920" height="1080" alt="Screenshot (305)" src="https://github.com/user-attachments/assets/6b565d7e-ecf8-4331-b3db-935434d7710a" />


### Folder after deleting the files
<img width="1920" height="1080" alt="Screenshot (306)" src="https://github.com/user-attachments/assets/54e3e54d-3562-40c4-9ad3-a24381f13845" />


### Folder after extracting the deleted images using autopsy
<img width="1920" height="1080" alt="Screenshot (314)" src="https://github.com/user-attachments/assets/20e7e7ac-a654-4d5c-af56-708e05f779df" />


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
