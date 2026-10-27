
##  Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## REG NUMBER: 212225230031
## NAME: BHARATH S

## Aim :
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
## Steps:
Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.
Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
## Steps:
Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
Login to Kali Linux:

Use root credentials.
(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox
![440120436-737dafde-fd5d-4266-849a-a12013ce9c5b](https://github.com/user-attachments/assets/c4dc7d5e-2bd2-48d7-85d5-1576256f5a3e)

Snapshot 2: Kali Running in Virtual
![440120616-6b08c65e-e2c0-4f8e-a782-0914a3470759](https://github.com/user-attachments/assets/2b88a9c0-c2ca-4aed-84c4-14dda2bfe217)

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
## Linux Commands:
1. ls Command
The ls command is used to display a list of content of a directory.

## Syntax:
1.ls

2. pwd Command
The pwd command is used to display the location of the current working directory.

## Syntax:
~~~
pwd
~~~

3. mkdir Command
The mkdir command is used to create a new directory under any directory.

## Syntax:
~~~
mkdir <directory_name
~~~

4. rmdir Command
The rmdir command is used to delete a directory.

## Syntax:
~~~
rmdir <directory_name>
~~~

5. cd Command The cd command is used to change the current directory
## Syntax:
~~~
cd <directory_name>
~~~

6. cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

## Syntax:
~~~
cat [options] [file_name]
~~~


7. cp Command
The cp command is used to copy a file or directory.

## Syntax:
~~~
cp [source] [destination]
~~~

8.mv Command
The mv command is used to move a file or a directory form one location to another location.

## Syntax:
~~~
mv [source] [destination]
~~~

9. touch Command
Create empty file.

## Syntax:
~~~
touch [filename]
~~~

vi Command
Edit file contents using editor.

## Syntax:
~~~
vi [filename]
~~~
<img width="1280" height="800" alt="Screenshot From 2026-10-27 09-19-07" src="https://github.com/user-attachments/assets/801269a6-02d2-49e1-811e-16381fe9d8b6" />
<img width="1280" height="800" alt="Screenshot From 2026-10-27 09-20-02" src="https://github.com/user-attachments/assets/f3eca038-6f7f-46e1-956a-2308d5ffd55e" />
<img width="1280" height="800" alt="Screenshot From 2026-10-27 09-23-08" src="https://github.com/user-attachments/assets/1c6ef070-f113-4912-8e2d-538fd55787bd" />
<img width="1280" height="800" alt="Screenshot From 2026-10-27 09-24-44" src="https://github.com/user-attachments/assets/d6180219-dffb-467c-853d-2a6ae9c51071" />
<img width="1280" height="800" alt="Screenshot From 2026-10-27 16-11-35" src="https://github.com/user-attachments/assets/29457b33-f027-488a-aafe-ac0a47328c8b" />
<img width="1280" height="800" alt="Screenshot From 2026-10-27 09-24-44" src="https://github.com/user-attachments/assets/5eb228a5-f1eb-4749-8344-f9468382ee87" />
<img width="1280" height="800" alt="Screenshot From 2026-10-27 09-27-14" src="https://github.com/user-attachments/assets/a2bbb2a4-ea10-4cb3-bb11-5667906c66a0" />
<img width="1280" height="800" alt="Screenshot From 2026-10-27 16-10-34" src="https://github.com/user-attachments/assets/fad4f404-6c55-4acb-b704-b59b7212b981" />
## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
