## memCpuCheck

INSTALLATION

- You need to install this packages before running the script:
    - sudo apt-get install libsnmp-dev snmp-mibs-downloader gcc python-dev
    - pip3 install easysnmp

DESCRIPTION:

- It's a simple python script that returns the ticks values of the processors, 
the value of the total memory and the value of the available memory.
    
USAGE:

- python3 memCpuCheck.py

PARAMETERS:
    
- community: community string for snmp.
- host: host that receive the requests sent.
- version: version of snmp for the requestes.
- num_processors: number of the agent processors.
    
OUTPUT:
	
- The number of ticks spent idle, for num_processors processors: ...
- Available memory: ... kb
- Total memory: ... kb
