# Distributed-File-System-Using-NFS-Protocol
# Python Distributed File System 
# Amrita Vishwavidyapeetam 


## Dependencies
This project is written in **Python 3.6**  
It was written on a Windows Machine.
This project uses sockets to send information between servers and services.

To run this project, do the following:

* Run the client application: **python client.py**
* Run the directory service: **python directory_service.py**
* Run the locking service: **python locking_service.py**
* Run fileserver A in a separate directory - fileserver A is holds the primary copy for replication and can be written to: **python fileserverA.py**
* Run fileserver B in a separate directory - fileserver B only takes read requests: **python fileserverB.py**
* Run fileserver C in a separate directory - fileserver C (like fileserver B) only takes read requests: **python fileserverC.py**
