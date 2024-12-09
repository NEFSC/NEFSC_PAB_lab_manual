# Passive Acoustic\_soundfiles structure

The PassiveAcoustics\_Soundfiles server server is where we store all acoustic data files. For information on where we store all other data see the [PassiveAcoustic server page](https://docs.google.com/document/d/1VxZ9pT2j1ylzHbp2VbaZNV3WVEpuYS_ZFzozmT1G850/edit?usp=sharing). 

### Accessing the server

To access the server for the first time, submit an ITD ticket requesting access to PA\_group file shares and include Sofie or your team lead on the ticket so that they can provide approval.

To access from the Windows file explorer enter: \\\\nefscdata\\PassiveAcoustics\_Soundfiles\\  
To access from a container enter: \\\\mnt\\PassiveAcoustics\_Soundfiles\\

For quick access on your computer, it is recommended to pin the server folder 

### PassiveAcoustics\_soundfiles server information

The general organizational structure of PassiveAcoustic Soundfile directories is as follows: 

* **Recorder type\\**  
  Each hydrophone or recorder type has a folder (see the nefsc-1 folder for all the recorder type options). A READ\_ME\_region\_key text file should be added here with region acronyms spelled out for reference.  
  *File name format: \[recorder\_type\]*  
  *Example: bottom\_mounted*

  * **Region\\**  
    Each general region where recorders are deployed has a folder. These should correspond with the regions most commonly used in your analyses and deployment planning.  
    *File name format: \[fmc acronym\]\_\[region acronym\]*  
    *Example: nefsc\_sbnms*

    * **Deployment\\**  
      Each recorder deployment has a folder.  
      *File name format: \[fmc acronym\]\_\[region acronym\]\_\[deployment start month/year as YYYYMM\]\_\[unique recorder ID\]*  
      *Example: nefsc\_sbnms\_202307\_sb03*

      * **Recorder\\**  
        Each recorder type (deployed together as a unit) has a folder.  
        *File name format: \[fmc acronym\]\_\[region acronym\]\_\[deployment start month/year as* 