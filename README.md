
## Background

Recent success in DNA storage technologies shows the feasibility and practicality of a complete system for encoding, storing and retrieval of digital data using DNA molecules. Healthcare is moving towards precision medicine, also known as genomic medicine, which emphasizes the need for integrating genomic data and patient’s health records so that medical treatment can be tailored to the specific characteristics of an individual. Yet, since the dawn of genomic medicine and the exponential rise of sequencing, the full application and power of our genomic revolution has not been fully utilised in clinical medicine. However, there are practical challenges to integrate genomic data into electronic health records (EHRs) like storage issues, security issues and longetivity issues.

## eMED-DNA

We present eMED-DNA which is a proof-of-concept for archiving medical histories of a person in his DNA sequence. A large genome  regFunctions of more than 98% of the human genome are currently unknown and these parts are called non-coding regions. We developed a lossless architecture
for efficiently storing, managing and retrieving electronic health records (EHRs) within the regions of a
patient's genome that have no or little known biological functions or deem not useful for a particular clinical context. This represents the first integrative clinical genomic and EHR operating system.  With the recent success in DNA storage system,
which is more robust and long-lasting than the typical hardware storage systems, we believe
eMED-DNA will open the possibility to store the medical records of an individuals
entire life in his DNA sequence, and thus will contribute
towards modern research in personalized medicine and future healthcare system in general.

We innovated a number of efficient and sophisticated techniques to implement the proposed operating system. All these techniques are seamlessly combined into an integrated pipeline called eMED-DNA for random and error free management of EHRs within a genome sequence. 






## Requirements

### Java 


## Installtion 

A. Windows 

    1. Download the 'Windows' folder from: https://goo.gl/KKjeHi/. Unzip and extract all the files in a single folder.
    2. If you do not have any DICOM viewer or GDCM (Grassroots DICOM) installed in your computer, you need to install them first.
       You can do it just by double clicking 'installer.bat' file.
    3. Finally, run the 'eMed-DNA_windows.jar' file (simply by double clicking on it).
    
 B. Linux
 
    1. Download the 'Linux' folder from: https://goo.gl/KKjeHi. Unzip and extract all the files in a single folder.
    2. Open the terminal, cd (change directory) to the installation directory and run the following commands to install GDCM and give execute permission to the jar file.
      - chmod +x script.sh
      - ./script.sh
    3. Finally, run the 'eMed-DNA_linux.jar' file.
    
C. Mac

    1. Download the 'MacOS' folder from: https://goo.gl/KKjeHi. Unzip and extract all the files in a single folder.
    2. Open the terminal, cd (change directory) to the installation directory and run the following commands to install brew, GDCM and give execute permission to the jar file. If you already have brew installed in your computer, then this sript will just update the existing one. 
      - chmod +x script.sh
      - ./script.sh
    3. Finally, run the 'eMed-DNA_mac.jar' file.


## Default Files
In order to make it easy to explore and learn how to use eMED-DNA, eMED-DNA comes with a default genome sequence GRCH38 (Genome Reference Consortium Human Build 38) obtained from ENSEMBL. Default input files (genome sequence, gene lists and choromose lengths) are available to downloat at [here.](https://goo.gl/GjwxAg)  Save these files and the eMED-DNA jar file in the same folder.

<!--## Download Software 
eMED-DNA software is freely available at: [Drive link.](https://drive.google.com/drive/folders/1gT55X1rMFGIWAySb2ZIzzRwsAujVF14O?usp=sharing)-->

## Tutorial 
A comprehensive step-by-step video tutorial can be found [here.](https://jakariamd.github.io/eMED-DNA/)
