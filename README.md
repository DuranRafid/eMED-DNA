# eMed-DNA

## Abstract 
We present a proof-of-concept for archiving medical histories of a person in his DNAsequence.  Functions of more than 98% of the human genome are currently unknown andthese parts are called non-coding regions or Introns.  We developed a lossless architecturefor efficiently storing, managing and retrieving electronic health records (EHRs) within thenon-coding regions of a patients genome sequence for efficient archival of both EHRs andgenome sequences.  We also proposed an efficient binary to ATCG conversion techniquewhich is better than the traditional naive Binary-to-DNA mapping (where two binary bitsare mapped to one of the four DNA bases). With the recent success in DNA storage system,which is more robust and long-lasting than the typical hardware storage systems, we believeour proposed system will open the possibility to store the medical records of an individualsentire life in his DNA sequence which may last for many years, and thus will contributetowards modern research in personalized medicine and future healthcare system in general.We developed a software implementing our proposed architecture.



## Background 
eMED-DNA is a sophisticated pipeline which incorporates compression at different levels,  novel Binary-to-DNA base conversion technique, and an in-DNA file management system to manage the DNA base streams resulting from the EHRs and the dictionary entries. We proposed customized algorithms and computational techniques for each of these key components of eMED-DNA.  In this section we give the full details of these techniques.




## Requirements

### Java 


## Installtion 

A. Windows 

    1. Download the '' file.
    2. If you dont have any DICOM viewer and GDCM installed on your pc, you need to install them first.
       You can do it just by double clicking 'installer.bat' file. 
    3. Then you can run the software by double clicking the 'software.jar' file.

