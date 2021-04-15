![ProdigyBackground](https://user-images.githubusercontent.com/47261571/114292583-732e9200-9a5d-11eb-87b0-f7541599ef9c.png)

# ARCHER Rock Recognition Server
This is a Rock Recognition Server used for ARCHER's AR System NASA SUITS Challenge 2021
Made by Team Prodigy from the University of Puerto Rico at Mayagüez campus. 
One of the tasks for future mission to the lunar surface such as the Artemis Program is to understand the geology of our natural satellite. With Rock Recognition it allows the astronauts to easily identify the rocks to be taken as sample.
This [server](#how-to-get-the-server-running-on-windows) has a trained [model](#rock-classification) based on ML.NET Deep Learning.

Table of contents
=================

<!--ts-->
   * [Introduction](#archer-rock-recognition-server)
   * [Table of contents](#table-of-contents)
   * [Rock Classification](#rock-classification)
   * [How to get the Server Running on Windows](#how-to-get-the-server-running-on-windows)
<!--te-->

## Rock Classification
Using ML.NET Deep Learning a model was trained with more than two thousands Images available from the Apollo Program and the internet.
This current Model is capable of classifying the following rocks:
### Basalt
<img src="https://user-images.githubusercontent.com/47261571/114284947-799f1880-9a21-11eb-8bd2-80b0a2a615e2.jpeg" width="350" height="400">


### Breccias
<img src="https://user-images.githubusercontent.com/47261571/114284986-bcf98700-9a21-11eb-902b-85b3d3758f5b.jpg" width="350" height="400">


### Obsidian
<img src="https://user-images.githubusercontent.com/47261571/114284935-69873900-9a21-11eb-98e1-f7f9de4de7f6.jpeg" width="350" height="400">


### Peridotite
<img src="https://user-images.githubusercontent.com/47261571/114284913-42c90280-9a21-11eb-9461-e60b132c8d4f.jpeg" width="350" height="400">


### Gneiss
<img src="https://user-images.githubusercontent.com/47261571/114284953-80c62680-9a21-11eb-87d9-6ade551c5cbb.jpeg" width="350" height="400">


# How to get the Server Running on Windows
### 1. Download the content in the git
![image](https://user-images.githubusercontent.com/47261571/114128479-70e7fe80-98ca-11eb-8f8e-176db5be3c81.png)

### 2. Go to RockRecognitionServer Folder and run the RockRecognition.exe.
![image](https://user-images.githubusercontent.com/47261571/114128326-1b135680-98ca-11eb-9a12-0acbdf139a03.png)

### 3. The system will prompt you to press Enter to start the Rock Recognition Server. Once continue it will load the Deep Learn Rock Recognition model and boot the Server.
![image](https://user-images.githubusercontent.com/47261571/114128620-c4f2e300-98ca-11eb-81ef-eb9e9ae7fb55.png)

### 4. Now you are capable of connecting to the Rock Recognition Server on the ARCHER system by providing the IP Address of the machine currently running this server to the ARCHER Client. [More information available at ARCHER's User Guide].
Here a example of a Image Receive from the Archer System:
![image](https://user-images.githubusercontent.com/47261571/114128841-4ea2b080-98cb-11eb-83d6-7ff4866331d8.png)

