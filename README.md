# TWOS (The Wolf of SUTD) Dataset

## 1. Introduction
The TWOS dataset has been collected from real user interaction with the host machine that contains both legitimate user data and malicious insider instances (masqueraders and traitors).  The dataset was collected during the competition organized by Singapore University of Technology and Design in March 2017, and comprises of data collected from 6 data sources (keystrokes, mouse, host monitor, network traffic, SMTP logs, and logon)  with additional data from psychological personality questionaire. 

The dataset contains activity of 24 users that were collected over a period of 5 days. It includes 12 masquerader instances, each 90 minutes long and 5 possible traitor instances,  each 120 minutes long. 

![Image](poster.png)

## 2. Conditions of Use
Since this dataset was collected with human subjects and through confidentiality agreements with them, access to this dataset is given only upon meeting several conditions. We expect to receive an request email to address `corplab-project3 (AT) sutd.edu.sg` with the template below. If you are a student or a research assistant, we also need a confirmation from your supervisor saying that she/he understand these conditions as well.

### Email Template
> `I am interested in obtaining a copy of TWOS dataset for research purposes. These purposes are described below.`
>
> <_here indicate what you plan to do with the data_>
>
> `I agree to abide by the following conditions limiting my use of this data set.`
>
> 1. `I will use the data for only the research purposes described above.`
> 2. `I will not pass the data to other researchers without explicit permission from the original authors.`
> 3. `I will indicate in any potential publication the source of the data as the following citation:`
>
>> _Athul Harilal, Flavio Toffalini, John Castellanos, Juan Guarnizo, Ivan Homoliak, and Martin Ochoa. TWOS: A Dataset of Malicious Insider Threat Behavior Based on a Gamified Competition. In International Workshop on Managing Insider Security Threats (MIST@CCS). 2017._

<_Indicate your name, surname, and institution_>


## 3. Description of Data Sources

### Keystrokes: 
Keystroke activity of each user can be found within a single file named according to the user name. It contains information pertaining to timestamp, key press / release events, key value (annonymized as sub-part of keyboard), and username.

### Mouse: 
Mouse activity of each user can also be found within a single file named after the user. It contains information pertaining to timestamp, mouse move / click / release events, coordinates of mouse pointer, and username.

### Host Monitor: 
The system calls of each user can be found within multiple files that contain the name of the user. It contains file system, registry, process, and network related information. Specifically it contains information such as timestamp, program name, PID, Parent Program name, Parent PID, system call operation.

### Network Traffic: 
Network activity of all users are logged into one pcap file. It contains information such as HTTP Request / Response, method (e.g., GET, POST), status code, content length, content type.

### SMTP Logs / Emails:
Email activity of all users is found within a single file in the order of emails send by the users. It contains information such as timestamp, header, sender, receiver,  LIWC features extracted from an email body (anonymized body of message upon explicit request).

### Logon Activity: 
The login / logout activity each user can be found within a single file. It contains information such as timestamp, login attempt, login success, logout event, username.

## 4. Other Important Information: 
We also share a ground truth file that contains the following:

* Composition of each Team and it's leader
* Masquerade session timings 
* Detail of fired members, such as old team, new team


 


