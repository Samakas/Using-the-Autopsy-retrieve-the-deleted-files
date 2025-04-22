# Using-the-Autopsy-retrieve-the-deleted-files
### Name: Samakash R S
### Reg NO: 212223230182
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

![Screenshot 2025-04-22 112903](https://github.com/user-attachments/assets/96c81d5a-7f64-4f41-a218-2531762b8cd7)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![Screenshot 2025-04-22 112917](https://github.com/user-attachments/assets/c20ea4a6-e448-4b53-842c-8af3827c20de)


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![Screenshot 2025-04-22 112946](https://github.com/user-attachments/assets/999425c0-8a2f-4d95-9a60-b5aa588d8061)


- Select **Local Disk** → **next** 
![Screenshot 2025-04-22 112953](https://github.com/user-attachments/assets/504a0094-1e84-44c2-b7e4-ea83b1c6e25c)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![Screenshot (1)](https://github.com/user-attachments/assets/2fd85fc1-7103-41a7-8eaf-97c6e6ca006e)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![Screenshot (10)](https://github.com/user-attachments/assets/3fdf30f1-d3f3-4db2-8ddd-ed3fc6215110)

![Screenshot (11)](https://github.com/user-attachments/assets/76afdb06-3c20-4385-8a59-dce0768b1b66)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![Screenshot (12)](https://github.com/user-attachments/assets/e0dc0c39-39d6-4f01-a018-4843d08b0de4)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot (15)](https://github.com/user-attachments/assets/e2b4f9f9-3b17-4e96-99e8-86f455cf82e0)


### Folder after deleting the files
![Screenshot 2025-04-22 162449](https://github.com/user-attachments/assets/2e44161e-e9b3-457b-a664-c056e7fb7a31)


### Folder after extracting the deleted images using autopsy
![Screenshot 2025-04-22 162433](https://github.com/user-attachments/assets/02a209a0-21e6-4a93-b5d7-39452d9ed9c6)


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
