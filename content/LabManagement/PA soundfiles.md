# Passive Acoustic\_soundfiles structure

The PassiveAcoustics\_Soundfiles server is where we store all raw audio files. For information on where we store all other data see the [PassiveAcoustic server page](https://docs.google.com/document/d/1VxZ9pT2j1ylzHbp2VbaZNV3WVEpuYS_ZFzozmT1G850/edit?usp=sharing). 

### Accessing the server

To access the server for the first time, submit an ITD ticket requesting access to PAB file shares and include Sofie or your team lead on the ticket so that they can provide approval.

To access from the Windows file explorer enter: \\\\nefscdata\\PassiveAcoustics\_Soundfiles\\  
To access from a container enter: \\\\mnt\\PassiveAcoustics\_Soundfiles\\

For quick access on your computer, it is recommended to pin the server folder 

### PassiveAcoustics\_soundfiles server information

The general organizational structure of PassiveAcoustic Soundfile directories is as follows: 

* **Recorder type\\**  
  Each hydrophone or recorder type has a folder (see the nefsc-1 folder for all the recorder type options). A READ\_ME\_region\_key text file should be added here with region acronyms spelled out for reference.  
  *File name format: \[recorder\_type\]*  
  *Example: BOTTOM\_MOUNTED*

  * **Region\\**  
    Each general region where recorders are deployed has a folder. These should correspond with the regions most commonly used in your analyses and deployment planning.  
    *File name format: \[fmc acronym\]\_\[region acronym\]*  
    *Example: NEFSC\_SBNMS*

    * **Deployment\\**  
      Each individual deployment has a folder.  
      *File name format: \[fmc acronym\]\_\[region acronym\]\_\[deployment start month/year as \[YYYYMM\]\_\[unique site ID\]*  
      *Example: NEFSC\_SBNMS\_202307\_SB03*

      * **Recorder\\**  
        If multiple instruments are deployed on one mooring, each recorder type (deployed together as a unit) has its own a folder.  
        *File name format: \[fmc acronym\]\_\[region acronym\]\_\[deployment start month/year as \[YYYYMM\]\_\[site ID\]\_\[instrument type\]*

        *Example:NEFSC\_SBNMS\_202307\_SB03\_ST*

          
