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

![image](https://github.com/user-attachments/assets/fc3b6366-ef6d-415b-bf1d-ff9c5c81c2cb)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/d9d8c966-80d6-4a14-9c8d-229d10a7709a)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/194ef365-4774-4003-b2eb-f6444ca77993)

- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/330e2e21-552b-4975-b64e-82383a611caa)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/e112c53c-035c-41f7-83d9-475ae90b6a5d)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![image](https://github.com/user-attachments/assets/3e4affff-5e42-4980-ac1a-ce0d1629ac61)

![image](https://github.com/user-attachments/assets/e3958db0-bb53-416e-8da4-fe3bc51f0837)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![image](https://github.com/user-attachments/assets/fe83ceeb-0094-468e-a229-2ab0a94feb34)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files

![image](https://github.com/user-attachments/assets/1291788e-5645-42ce-a88f-68672fb78fb1)

### Folder after deleting the files

![image](https://github.com/user-attachments/assets/2f6abdb7-4ccf-447d-9f71-fb90ee44fe3c)

### Folder after extracting the deleted images using autopsy

![image](https://github.com/user-attachments/assets/84b537ff-e9a5-42ac-868c-7a5334344103)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
