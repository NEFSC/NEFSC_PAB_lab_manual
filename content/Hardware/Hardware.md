# Hardware

The NEFSC Passive Acoustic Branch uses a variety of passive acoustic recording platforms to monitor sounds in the ocean. PAM deployments also often consist of co-located hardware to collect ancillary data about the ocean or provide mechanisms to recover the instruments.

## Bottom-Mounted 

Bottom-mounted moorings are most commonly used for continuous monitoring at single location, providing long-term time series for marine mammals, fish, soundscapes, and anthropogenic noise. 

- TOSSIT Protocol link  
- ARC Protocol link  
- Etc. etc. 

Bottom-Mounted Mooring example

![][image1]

## Moored Buoy

### Moored Surface Buoy: Woods Hole Oceanographic Institution ([Robots4whales](https://robots4whales.whoi.edu/platforms/moored-buoy/))

A WHOI-engineered quiet surface buoy specifically for acoustic applications. Data detection delivered from DMON/LFDCS to shore-side computer via Iridium satellite modem.

## 

## 

## Mobile Platforms

### Slocum Gliders: Woods Hole Oceanographic Institution ([Robots4whales](https://robots4whales.whoi.edu/platforms/slocum-glider/), [TeledyneMarine](https://www.teledynemarine.com/en-us/products/Pages/slocum-glider.aspx)?)

Slocum gliders are useful for passive acoustic monitoring, as they can glide silently through vast depth ranges for months at a time. Can self-navigate using GPS systems, and can communicate with researchers via Iridium communication sessions.

### Towed Array: 

A towed array is the acoustic sampling technique of dragging a recording device behind a moving ship, which usually allows the pairing of recording with visual groundtruthing. This method is particularly useful for pairing vocalizations with under-studied species.

* ‘A GUIDE TO CONSTRUCTING HYDROPHONE ARRAYS FOR PASSIVE ACOUSTIC DATA COLLECTION DURING NMFS SHIPBOARD CETACEAN SURVEYS’ \- Shannon Rankin → relevant?  
* [Lab Protocols](https://drive.google.com/drive/folders/1nQI9PQkyzDe7hP53RlUzBnHaYxUoo3s8)

![][image2]

### DASBRs: 

DASBRs are floating, mobile platforms that typically incorporate Soundtrap and hydrophone components. DASBRs are typically deployed if Gervais’ beaked whales are sighted during offshore fieldwork. GPS will indicate location once the platform is ready to be retrieved. 

* [Lab Protocol](https://docs.google.com/document/d/13FeiyPSnvGXLOZfFxmZceHb_1UlwR0YP/edit?tab=t.0)

### Dipping Hydrophone: 

Dipping hydrophones are acoustic recorders that are attached to a rope and suspended in the water. 

* [Lab Protocol](https://docs.google.com/document/d/17L0CEr6XYmXnvDHzgUtjk7NDoLuuo8aQ/edit)

## Recording Instruments

### SoundTrap: [Ocean Instruments](https://www.oceaninstruments.co.nz/product/soundtrap-st600-std-long-term-recorder/)

* PABs primary instrument due to relatively long battery life and large memory, and broad sampling rate. Typical deployments consist of 5 month recording at 48kHz providing data for most cetaceans, fish and soundscapes.   
* [Ocean Instruments SoundTrap guide](https://drive.google.com/file/d/1upLq-g1WelZr6P0-W1eXaOoZqM6sPbdo/view?usp=sharing)  
* Lab protocol link

### F-POD: [Chelonia Wildlife Acoustic Monitoring](https://www.chelonia.co.uk/f-pod/)

* F-PODs are a high-resolution click detector used to identify delphinids. The instrument is calibrated, has a long battery life and is an integrated product that records audio and automatically detects clicks.  
* F-Pod protocol link

### 

### Vemco Acoustic Telemetry and Release (order site \- [InnovaSea](https://www.innovasea.com/fish-tracking/products/acoustic-receivers/), VR2AR Acoustic Release Receiver)

* Acoustic telemetry release allows researchers to retrieve bottom-mounted recording devices using acoustic signalling. Using VEMCOs eliminates the need for surface buoys, mitigating whale entanglement risk.   
* VEMCO protocol link

## Auxiliary Hardware

### HOBO Temperature Loggers ([order site](https://www.onsetcomp.com/products/data-loggers/utbi-001))

* Small mechanism that logs temperature over long periods of time. Requires HOBOware software and either an Optic USB Base Station or HOBO Waterproof Shuttle (U-DTW-1).

### Apollo X1 Satellite Beacon ([order site](https://xeostech.com/apollo-x1))

* The Apollo Satellite Beacon is used to monitor unplanned or accidental release of subsurface instrument moorings.

### Hermes Beacon Locator ([order site](https://xeostech.com/hermes))

* The Hermes Beacon Locator is used to communicate with the Apollo Satellite Beacon to locate mooring units at sea

### VHTx: Transponding Hydrophone ([order site](https://www.oceans-research.com/vhtx/))

* Transponding hydrophone used for communication between VEMCO VR100 Deck Box and VEMCO Acoustic Release Receiver.

### VEMCO VR100 Deck Box ([order site](https://www.oceans-research.com/vr100/))

* The VEMCO Deck Box is used to remotely connect and communicate with the submerged VEMCO, primarily to release the VEMCO from the bottom-mounted weights. 

# Technical advice

### When should I replace my VR2AR / ASCENT-AR acoustic release battery?

* Replace the release motor AA batteries once they indicate they are approaching 25%. It is very strange that they did not last longer (5 years estimated life expectancy), but once you replace them, you will be prompted to reset the battery indicator within the VUE software. Vue should then indicate that they are at 100% again with the new batteries. You can then monitor the percentages in future deployments; if they continue to drop towards 25% quickly (within a year or two), then the receiver may be faulty or would at least warrant a call to Innovasea/Vemco to see what might be going on.  
* Web resources:  
  * INNOVAsea: [When should I replace acoustic release battery?](https://support.fishtracking.innovasea.com/s/article/When-should-I-replace-my-VR2AR-ASCENT-acoustic-release-battery)  
  * INNOVAsea: [How to change the AA release battery](https://support.fishtracking.innovasea.com/s/article/How-do-I-change-the-AA-release-battery-in-my-VR2AR-ASCENT)

### Flooded ST600s

* Sent them back to Ocean Instruments to be fixed  
* Email chains:  
  * [First ST600s flooded](https://drive.google.com/file/d/1GImB989mVDIIf2ORAn2mwT8pNbH5rpMz/view?usp=drive_link)  
  * [Instructions for return](https://drive.google.com/file/d/19kJQtU3yk-t8OMcwjKXLUxtM3EC94L1C/view?usp=drive_link)

### ST600 Battery bay malfunction

* Lots of advice from John Atkins \- ended up needing to send back to be fixed  
* Email chains:  
  * [ST600 with one battery bay nonfunctional](https://drive.google.com/file/d/1If67SQuWS5amUWraMGj7D1jQVHAFLHf6/view?usp=drive_link)

### ST600 clock drift

* Outcome \- John Atkins was going to push a universal fix for this  
* Email chains:  
  * [Clock Drift](https://drive.google.com/file/d/1S697qXnuB-xhNNiEs0KaXODroJyiQMVE/view?usp=drive_link)  
  * [Fix clock drift manually](https://drive.google.com/file/d/1fQb9_XiKwVxegYYUvwQz9s1-ZqqcArrM/view?usp=drive_link)  
  * This email conversation can also be found on the server here: \\\\stellwagen.nefsc.noaa.gov\\stellwagen\\MANUALS\_SOFTWARE\_CODE LIBRARY\\HARDWARE\\SoundTraps

### ST600 Broken Hydrophone

* Need to be sent back for repair  
* Email chain:  
  * [Broken hydrophone](https://drive.google.com/file/d/1_3e-nJLZ5C6a-rbKnhVutBTsr6bolDzA/view?usp=drive_link)

### Apollo Beacon Voltage

* Info on when to switch out batteries 2v is low, 2.5v  is plenty  
* Email chain:  
  * [Apollo beacon battery voltage](https://drive.google.com/file/d/1eI8eAdZqxqj6vss9Jx2pIV9ZlqfPJ_AC/view?usp=drive_link)

### FPOD Batteries

* Info on what types of batteries are compatible with FPODs  
* Additional resources:  
  * [FPOD battery guide from manual](https://drive.google.com/file/d/13hkncRfZVod3fCwQtu3g13EQvEiVxOcN/view?usp=drive_link)

### Piston phone ST calibration

* How to use the pistonphone to calibrate the STs  
* Email chain:  
  * [Pistonphone protocol](https://drive.google.com/file/d/1u6tWJSvCm1_CjszZn7Tnfn303O06RCj3/view?usp=drive_link)

### Hydrophone bonding issue for ST600s serial \# \<7000

* The bond between the hydrophone and ST600 for serial \#s prior to the 7000's can degrade over time. Need to keep an eye out on hydrophone bond to ST for older ST600s  
  * Timothy Rowell \- This did happen to the first one we had deployed in Rookery Bay Florida. Scrub gently and inspect often.  
* Email chain:  
  * [ST600 Hydrophone bonding issue](https://drive.google.com/file/d/19jdmku3WF5ZOw3tllENY0heaL6JOYohX/view?usp=drive_link)

### Data upload errors

* Google Bucket error   
  * [Examples](https://drive.google.com/file/d/1xoWyPJskAPTCfX1kpJC9cCRtwOj0t85X/view?usp=drive_link) \- screenshots did not transfer in pdf

### ST Recording Start Time Programming

* Error when setting recording start time to a previous/past time  
* Email chains:  
  * [Soundtrap configure failure](https://drive.google.com/file/d/13mTDNsYi7uPwTdeN1YcmMYHY7IxaquHm/view?usp=drive_link)

### VR2AR temp/depth/tilt Data

* See email. How to download the temperature, depth, and tilt data recorded by VR2ARs  
* Email chain:  
  * [VR2AR2 record temp/depth data](https://drive.google.com/file/d/1I42Gy-5E1hGG72Y0G01k_FmweSCaZMtP/view?usp=drive_link)

### Cross-center SoundTrap Issue Documentation

* It was brought up in a call today about a [spreadsheet](https://docs.google.com/spreadsheets/d/1HYPw2-IsgiTonLoSUGJ00FHVmN4wSoPqCmpd0fQESbk/edit#gid=0) that has been shared amongst the science centers that annotates the various SoundTrap issues folks have been experiencing. I don't see any of ours logged on there, if someone wants to and has a moment to log down our issues we've had? This is not a high priority by any means. Also I became aware of a [StackExchange page](https://bioacoustics.stackexchange.com/questions/242/st600-hardware-failures) that documents the known ST600 issues that I wanted to share with you.  
* Additional resources:  
  * [Soundtrap troubleshooting log](https://docs.google.com/spreadsheets/d/1HYPw2-IsgiTonLoSUGJ00FHVmN4wSoPqCmpd0fQESbk/edit?gid=0#gid=0)

### ST Host Connection Error from 512GB SD Card

* Guidance on how to resolve a ST Host connection issue  
* Email chain:  
  * [SoundTrap Host USB connection issue troubleshooting help](https://drive.google.com/file/d/1R4L8T95VP2dA3tJnrcd1o4dT_aaR6z-h/view?usp=drive_link)  
* Additional resources:  
  * [How do I format EVO 256GB and 512 GB using the SoundTrap ST600 software?](https://bioacoustics.stackexchange.com/questions/1605/how-do-i-format-evo-256gb-and-512-gb-using-the-soundtrap-st600-software)

### ST Host Software v4.0.19 and manual

* Guidance on how to resolve a ST Host connection issue. Ocean Instruments is strongly recommending SoundTrap users from here on out use ST Host version 4.0.19, which is their most recent non-beta software release. I came across this on their most recent ST600 manual. No specific reason was given other than that it will ensure correct operation of the SoundTrap recorders.  
* Additional resources:  
  * [ST600 User guide](https://drive.google.com/file/d/1ykVxSLBLNAjFntzwqIuLX6SEwOAUkKvB/view?usp=drive_link)

### ST Card Reader Download Location

* Email chain:  
  * [ST Host v4.0.19](https://drive.google.com/file/d/1atDu25Vkg7nensG_5i64gsYET3y5FrPO/view?usp=drive_link)

[image1]: <data:image/png;base64,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>

[image2]: <data:image/png;base64,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>