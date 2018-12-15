
## Background

Recent success in DNA storage technologies shows the feasibility and practicality of a complete system for encoding, storing and retrieval of digital data using DNA molecules. Healthcare is moving towards Precision medicine, also known as genomic medicine, which emphasizes the need for integrating genomic data and patient’s health records so that medical treatment can be tailored to the specific characteristics of an individual. Various retrospective studies related to personalized medicine will require access to both the DNA sequences and medical records of patient. However, there are practical challenges to integrate genomic data into electronic health records (EHRs) like storage issues, security issues and longetivity issues.

## eMed-DNA

We present eMED-DNA which is a proof-of-concept for archiving medical histories of a person in his DNA sequence. Functions of more than 98% of the human genome are currently unknown and these parts are called non-coding regions. We developed a lossless architecture
for efficiently storing, managing and retrieving electronic health records (EHRs) within the
non-coding regions of a patients genome sequence for efficient archival of both EHRs and
genome sequences. We also proposed an efficient binary to ATCG conversion technique
which is better than the traditional naive Binary-to-DNA mapping (where two binary bits
are mapped to one of the four DNA bases). With the recent success in DNA storage system,
which is more robust and long-lasting than the typical hardware storage systems, we believe
our proposed system will open the possibility to store the medical records of an individuals
entire life in his DNA sequence which may last for many years, and thus will contribute
towards modern research in personalized medicine and future healthcare system in general.
We developed a software implementing our proposed architecture.






## Requirements

### Java 


## Installtion 

A. Windows 

    1. Download the 'Windows' folder from the link https://goo.gl/KKjeHi. It will be downloaded as a zip file. Unzip and extract all the files in a single folder.
    2. If you do not have any DICOM viewer or GDCM (Grassroots DICOM) installed in your machine, you need to install them first.
       You can do it just by double clicking 'installer.bat' file, which will install GDCM and MicroDicom Viewer in your PC. 
    3. Finally, you can run the software by double clicking the 'eMed-DNA_windows.jar' file.
    
 B. Linux
 
    1. Download the 'Linux' folder from the link https://goo.gl/KKjeHi. It will be downloaded as a zip file. Unzip and extract all the files in a single folder.
    2. Open the terminal, cd (change directory) to the installation directory and run the following commands to install GDCM and give execute permission to the jar file.
      - chmod +x script.sh
      - ./script.sh
    3. Finally, you can run the software by double clicking the 'eMed-DNA_linux.jar' file.
    
C. Mac

    1. Download the 'MacOS' folder from the link https://goo.gl/KKjeHi. It will be downloaded as a zip file. Unzip and extract all the files in a single folder.
    2. Open the terminal, cd (change directory) to the installation directory and run the following commands to install brew, GDCM and give execute permission to the jar file. If you already have brew installed, then this sript will just update it. 
      - chmod +x script.sh
      - ./script.sh
    3. Finally, you can run the software by double clicking the 'eMed-DNA_mac.jar' file.


## Default Files
You can download the full genome sequence, gene lists and choromose lengths (obtained from ENSEMBL) from the following link: [Drive link.](https://goo.gl/GjwxAg) They are the default inputs for eMED-DNA. Save these files and the eMED-DNA jar file in the same folder.

## Download Software 
eMED-DNA software can be found here: [Drive link.](https://drive.google.com/drive/folders/1gT55X1rMFGIWAySb2ZIzzRwsAujVF14O?usp=sharing)

## Tutorial 
A comprehensive step by step tutorial can be found [here.](https://jakariamd.github.io/eMed-DNA/)
