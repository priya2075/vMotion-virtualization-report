

<div align="center">
<h1>vMotion-virtualization-report</h1>

#

### 📺 <a href="https://www.youtube.com/watch?v=BaRsem3CE8Q&ab_channel=Preeya">Click here to watch vMotion live migration for this report</a>
### 📒 <a href="https://github.com/priya2075/vMotion-virtualization-report/blob/main/Virtualization%20Report%20-%20Project%20-%202022.pdf">View the report</a>
</div>

#

### Objective for this project 
#### For application server [location: Maldives | NET.framework]
- Configure "SGMgmtClient" VMware ESXi-200 (Main) and install .NET framework for Windows Server 2012
- Create user administrator and monitoring
- Set up alerts for management (benchmark, alert type, triggers, & conditions)
- This "SGMgmtClient" should ping to all client devices, Sinagpore server and Frankfurt server, & Frankfurt backup.

#

#### For web server [location: Singapore (HQ) | Apache]
- Install VCSA, NAS Storage (Linux), OS Linux Debian GNU, and Apache
- Synchronize NTP time.windows.com
- And this server should ping to all client devices, Maldives and Frankfurt servers, & Frankfurt backup

#

#### For storage server and backup server [location: Frankfurt (HQ) | MySQL database]
- Setup VMware ESXi-220 (backup)
- Add the VMware ESXi-220 (backup) to CRME-DC in the vSphere Web client.
- Install MySQL database on Windows Server 2012
- And this server should ping to all client devices, Singapore and Maldives
- This setup must manage backup and recovery procedures
  - Storage: *live storage migration* 
- Must manage moving VMs to off-site servers
  - Backup: offline migration and *live migration*
