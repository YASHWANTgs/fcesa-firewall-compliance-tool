# fcesa-firewall-compliance-tool
This project is a cross platform python tool that can work on both linux and windows operatng system its developed for automates firewall configuration assesment against cyber essentials, We can extract the firewall rules using a command and then upload into a gui which provides real time monitoring and detailed compliance report in PDF format. It was designed in way that it can be used in SMEs and even non technical staffs can understand the GUI and its functionality. It checks if the the firewall rule is compatible to Cyber essentials Framework.

# Features 
- It provides Dual-platform support (Windows and Linux)
- Generates PDF compliance reports which provides remedial advice in one line.
- Automated rule extraction and monitoring which is done evey 60 seconds it can be turned on or off in GUI.
- Provides log information which can be used for audit purpose
- GUI version availabe (Tkinter) has on off toggle buttons,report generating buttons.
- Python

# Project Context
- This tool was developed in the context of my MSc Cybersecurity Final Year Project at University Of Hertfordshire which includes testing, evaluation, demostration of woring model and documentation with academic and industry ecpectations.

# How to use
- Extract the firewall rules and put that extracted JSON file in gui  then click generate report or on real-time monitoring if needed. real-time monitoring is automated and starts working as soon as the file is dropped.

  # MITRE Mapping
  T1562.004 : Impair Defenses -Firewall rule manipulation.

  # Author
  Yashwant - MSc cybersecurity , Comptia security+, Fortinet FCA
  
