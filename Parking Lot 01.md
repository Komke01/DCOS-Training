# Parking Lot 01
## Issues we face while executing the hands on tasks and the ways we resolve them.

* when downloading precise32/64 system asks if we need to use Virtual Box or VMware or sth else 
	we choose Virtual Box
	
I re-installed all applications (oracle VB, Docker, Vagrant) checked that OracleVB and Docker are not running, made sure VM is enabled in BIOS,  ran all the vagrant commands untill I reached "vagrant up and it crashed my laptop again. No output was shown before the crash
then I ran the following command from the admin command prompt: dism.exe /Online /Disable-Feature:Microsoft-Hyper-V 
restarted my machine, ran all commands again and I am now able to see the VM in Oracle VB.
