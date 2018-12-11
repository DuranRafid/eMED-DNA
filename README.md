
# Background

Recent success in DNA storage technologies shows the feasibility and practicality of a complete system for encoding, storing and retrieval of digital data using DNA molecules. Healthcare is moving towards Precision medicine, also known as genomic medicine which emphasizes the need for integrating genomic data and patient’s health records so that medical treatment can be tailored to the specific characteristics of an individual. Various retrospective studies related to personalized medicine will require access to both the DNA sequences
and medical records of patient. However, there are practical challenges to integrate genomic data into electronic health records (EHRs) like storage issues, security issues and longetivity issues.

## eMed-DNA

We present eMED-DNA which is a proof-of-concept for archiving medical histories of a person in his DNA sequence. Functions of more than 98% of the human genome are currently unknown and these parts are called non-coding regions or Introns. We developed a lossless architecture
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

    1. Download the '' file.
    2. If you dont have any DICOM viewer and GDCM installed on your pc, you need to install them first.
       You can do it just by double clicking 'installer.bat' file. 
    3. Then you can run the software by double clicking the 'software.jar' file.
    
 B. Linux
 
    1. Download the '' file.
    2. Run the following commands to install GDCM. 
      - sudo apt-get update
      - sudo apt-get install python-gdcm
      - sudo apt install libgdcm-tools
    3. Give executive permission to the file 'software.jar'.
      - chmod +x software.jar
    Then you can run the software by double clicking the 'software.jar' file.
    
C. Mac

    1. You need to have BREW installed on your mac. 
    2. The run the following command. 
       - brew update
       - brew install python-gdcm
       - brew install libgdcm-tools
    3. Then you can run the software by double clicking the 'software.jar' file.


## Chromosome Set
You can download Chromosome files from following link: [Drive link.](https://drive.google.com/open?id=1wSoMo0tgrqCKAH21L2vvTv72PTE9SmyV)

## Download Software 
eMed-DNA software can be found in the following link: [Drive link.](https://drive.google.com/drive/folders/1gT55X1rMFGIWAySb2ZIzzRwsAujVF14O?usp=sharing)

## Tutorial 
A comprehensive step by step tutorial can be found [here.](https://jakariamd.github.io/eMed-DNA/)
