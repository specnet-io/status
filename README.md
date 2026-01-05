# SPECNET.IO SYSTEMs STATUS
These are very basic CURL checks that the server is scheduled to simply check in.  
 - If the server misses X checks, it should appear as down.
 - Using https://healthchecks.io

When one of these services is marked as down, a notice should also trigger in our discord.
 - https://discord.com/channels/221068604760784897/1457615094849605643

# JDC (Jimmy Datacenter) Hosting
## Hardware
![firewall-status](https://healthchecks.io/b/2/e5b2f523-b930-4c88-a184-ca4cd9079c58.svg)
<br>Overall Internet Status
<br>

![proxmox1-status](https://healthchecks.io/b/2/4aa29b49-81ff-4dbd-81b6-6f4e60c6a42e.svg)
<br>Primary Proxmox Server
<br>

![proxmox2-status](https://healthchecks.io/b/2/a8e67f23-a681-4d89-b287-71d91d47287e.svg)
<br>Secondary Proxmox Server
<br>** GAME SERVERS ARE HERE **
<br>** GAME SERVERS ARE NOT ON NFS-BACKED STORAGE DUE TO I/O REQs**

![nas-status](https://healthchecks.io/b/2/2acb26cb-26b8-4442-9b6d-713281921476.svg)
<br>Network Attached Storage (drive, photos, nfs, smb, sftp)
<br>** MAY AFFECT VMs running on NFS backed storage **

## Virtual
![windows-game-host](https://healthchecks.io/b/2/842499c7-4178-4826-a952-9786fd93fd2a.svg)
<br>Enshrouded
<br>

![linux-game-host](https://healthchecks.io/b/2/0cfd9dc4-38ee-45f2-93a0-5448b46c8896.svg)
<br>Satisfactory
<br>Wreckfest
<br>Factorio