# Open Roster SFTP AD Sync Tool
 Sync from OpenRoster students.csv export located on SFTP to AD

### Requirements
- Windows 10 or Windows Server
- Active Directory Powershell Module
- WinSCP (Includes 5.17.10 in Repo)
- For automation, task scheduled to call OpenRosterSFTPSync.ps1 with appropriate permissions

### Installation
- Download or clone repository to specified server
- Install WinSCP if not already (5.17.10 DLL and Installation included in repo)
- Run SettingsEditor.ps1 to generate db and configure your settings
- Run either manually OpenRosterSFTPSync.ps1 or schedule a task
