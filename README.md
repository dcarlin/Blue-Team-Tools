# Blue-Team-Tools
This contains a list of Blue Team Tools that I use daily, and have stored here for reference.


## Malware Analysis
Malware Analysis is a broad scope. My aim is to extract IOC's to use for further threat hunting and detection through both static and dynamic analysis.

### What I use

I use a suite of VM's for my Analysis that references the environments that I work with. The main testing ground is done on a Windows 7 VM with no AV installed. Then another Windows 7 VM with all the corporate security tools installed. Aditionally I will also use the Ubuntu VM mentioned in the below section for Network Traffic Analysis.

#### Static Analysis
- Notepad ++:	
	- Advanced text editor, used in order to view any javascript files.
- IDA Pro Free:
	- x86 Disassembler.
- Ollydbg:
	- x86 Disassembler.
- PE View:
	- PE File Viewer.
- PEID:
	- Used to determine if a file is packed, and other basic info.
- Resource Hacker:
	- Allows us to view the resources that an executable file calls.
- CRITS:
	- Malware analysis and IOC storage platform. Handy for quick analysis on Malware.
	- Can extract macros and javascript embedded in documents
#### Dynamic Analysis
- Malwr.com:
	- Website where you can upload your sample and detonate it in a virtual sandbox.
- Hybrid-analysis.com"
	- Website where you can upload your sample and detonate it in a virtual sandbox.
- Wireshark:
	- Network Traffic Analysis Tool.
- Fiddler:
	- Web debugging tool.
- Process Explorer:
	- Shows a live process tree.
- Process Monitor:
	- Shows real time file system modifications and registry edits.
- Regshot:
	- Can take a before and after snapshot of your registry.
- Network Traffic Analysis VM:
	- See related section.


## Network Traffic Analysis
Traffic analysis can cover both PCAP data and Flow data. Here I am focusing on analyzing PCAP Data, as my use of Flow data is concerned mostly with hunting and monitoring.

### What I use

All of the Traffic Analysis that I perform is done on a Ubuntu VM running the below tools. Most often when Analyzing a PCAP I use Wireshark and Network Miner side by side.

- Wireshark:
	- Graphical PCAP Analysis Tool
- TCPDump:
	- Command line based PCAP Analysis Tool
- Network Miner:
	- PCAP Parser and Analyzer
- Snort:
	- Intrusion Detection System
- Bro:
	- Intrusion Detection System
- Whois Lookup
	- IP Address Lookup Tool
