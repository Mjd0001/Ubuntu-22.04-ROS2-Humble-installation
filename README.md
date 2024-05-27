# VMWarte-Ubuntu-22.04-installation
Steps of installing VMWare Workstation Player 17 on Windows 11, and installing Ubuntu 22.04 
<br>
<br>
<br>
## Step 1: Download and Install VMWare Workstation Player 17
1- go to this page to download vmware: https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html.html <br>
you will find download button in the bottom of the page: <br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/3eea4840-71e8-4cc5-b99a-ba6d260687b0)
<br>note: if the link doesn't work you can download from this link: 
<br>https://softwareupdate.vmware.com/cds/vmw-desktop/player/17.5.1/23298084/windows/core/
<br>reffere: https://www.reddit.com/r/vmware/comments/1cvm19z/vmware_player_download_link_isnt_workinggives_a/
<br>
<br>
2- installation: open the downloaded exe vmware file 
<br>click on next :<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/e299257e-a250-46a2-96bc-15e51b6ca77b)
<br>
<br>accept and next:<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/16f991e6-c1ca-4b62-9c12-bb5f61f7becd)
<br>
then click next next next until the end, click install and wait, after installation click finish.
<br>
3- you will found vmware icon in the desktop, click on it:
<br>choose the first option and click continue:<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/57c4cb08-5bf2-42ef-9e6c-c4a371324850)
<br>
then click finish.
<br>refference: https://youtu.be/wpnDSgN3L_o?si=epIgdigNWGO4Fv1Q
<br>
<br>
<br>
## Step 2: installing Ubuntu 22.04 on VMWare:

1- Download Ubuntu ISO Image: <br>
Note: if you want to use ROS2 Humble then you have to choose Ubuntu 22.04.4 LTS (Jammy Jellyfish)<br>
Download link: https://releases.ubuntu.com/jammy/ <br>
Choose desktop image<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/074407ae-5780-420b-ac3a-fd03196a59f9)
<br>
<br>

2- open VMWare, and select the ‘Create a New Virtual Machine‘ option as shown in the figure below.<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/970cf594-3bd1-4e93-b1f0-a5c0ed373442)
<br><br>
3- choose the last option 'I will install the operating system later' : <br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/9f892bdf-d016-402f-995f-1c785ad234af)
<br><br>
4- Select 'Linux' and 'Ubuntu 64-bit':<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/e3fbce6b-c41b-457b-b6de-d0e9457c8684)
<br><br>
5- You can change the Virtual Machine name and the location if you want, or you can keep it as default:<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/a7006c86-e8ac-4fe2-b198-7b8414ee43fb)
<br><br>
6-The next step is to assign the size of the virtual hard disk. You can safely work with 20 GB size for hard disk. but i prefer to increase it more than 30 GB. it depend on you disk size. If you can increase it to 50 GB, even better <br>
There are two options for creating a virtual hard disk. The first option is to store the virtual disk file as a single file. The second option is to split the disk into multiple files. The advantage of splitting is if you want to copy the hard disk file to another computer, you can easily copy the files. The problem with this configuration is, the performance will reduce if the disk size is very high.<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/2e245774-1a9a-4a63-8273-5e391b5db51b)
<br><br>
7- Then press the ‘Customize Hardware‘ button<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/34befd93-c400-442c-96a5-7999df7b7061)
<br>
In memory tab, based on your RAM number you have allocate RAM size, for me I have 16 GB so between 6 GB AND 8 GB is good<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/b4beeed0-84c3-4140-8492-d98eecc4dad1)
<br>
In Processor tab, besed on your CORE number change the number of processor core, for me I have 6 core so choose 3 or 4 core is good<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/ba003fb9-5707-4483-bd33-886daf5f5e56)
<br>
In New CD/DVD (SATA), select 'use ISO image file' and press 'Browse', and go to iso file of ubuntu 22.04 that we download it and choose it:<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/345ca9c6-ff29-4e55-882f-3d66a08376a6)
<br>
8- finally click in close button and then Finish button.<br>
you can change these settings when every you want by click on 'Edit virtual machine settings'. and to Run the virtual machine click on 'Play virtual Machine'<br>
![image](https://github.com/Mjd0001/VMWarte-Ubuntu-22.04-installation/assets/105239889/9df4543f-d062-4c6a-86cc-c213fc5b4398)
<br>
refference: https://youtu.be/9rUhGWijf9U?si=FLkbDTYp9KXtFoKz
<br><br><br>

