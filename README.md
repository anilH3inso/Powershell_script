# defend.ps1
This is COIT11241 Term1 Cybersecurity A2 WK4 PEER PROGRAMMING Assessment.
------------------------------------

About
-----
Certainly! Here's the description of this script in bullet points:

- The tool is a PowerShell script designed for data protection and recovery, focusing on file backup and restoration with encryption features.
  
- It utilizes the Gnu Privacy Guard (GPG) utility for encryption, ensuring the security of data during backup and restoration processes.

- The script offers various functionalities accessible via command-line arguments:

  - **installGPG**: Installs GPG4Win, a prerequisite for encryption, ensuring seamless integration of encryption capabilities.
  - **setupGPG**: Generates a GPG key required for encryption and decryption tasks, ensuring data security.
  - **backup**: Allows users to specify the source folder containing files to be backed up and the destination backup folder for encrypted backups.
  - **restore**: Facilitates the recovery of encrypted backup files to a designated restore folder, ensuring data integrity and accessibility.
- During backup operations, the script iterates through files in the source folder, encrypts each file using GPG, and stores the encrypted versions in the backup folder.
- During restoration, it decrypts encrypted backup files, saving the decrypted versions in the restore folder, ensuring seamless data recovery.



Execution
---------
First you have to create folders -- Backup and Restore
To download and execute defend.ps1 , run the commands below:

`wget https://github.com/anilH3inso/defend.ps1.git`  
`.\defend.ps1 installgpg`  
`.\defend.ps1 setupgpg`  
`.\defend.ps1 Backup` 
You need to select the path of source file which you want to backup
`.\defend.ps1 Restore`  

Required Programs
-----------------

Chocolatey (https://github.com/anilH3inso/chocolatey.git)



Licensing
---------

defend.ps1 is licensed under the group 2 - Anil and Tanisha cqu assessment project

(C) 2024 Anil & Tanisha.
