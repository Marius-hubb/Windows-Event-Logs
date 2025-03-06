<h1>Configure, View, and Analyze Windows Event Logs</h1>

<h2>Description</h2>

The objective of this lab is to learn how to configure, view, and analyze Windows security logs.
<h2>Lab walk-through:</h2>

#### Enable Audit policy
- Open Local Security Policy
- Local Policies > Audit Policy > Enable Audit logon events

<p align="center"><img src="https://i.imgur.com/CJDUu5N.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>
<br />

#### Viewing Events in Event Viewer
- Open Event Viewer
- Windows Logs > Security
<p align="center"><img src="https://i.imgur.com/aW1OEnU.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 
- in the right panel we can filter the log for event ID 4625 (logon failure):
<p align="center">
<img src="https://i.imgur.com/SX3S1Ue.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center"><img src="https://i.imgur.com/RfgZZ7G.png" height="50%" width="80%" alt="Disk Sanitization Steps"/>

- C:\Windows\System32\winevt\Logs to view the system logs:
<p align="center"><img src="https://i.imgur.com/pwVpKyD.png" height="50%" width="80%" alt="Disk Sanitization Steps"/><br />

We can double-click on any log to view a detailed information about the captured event.br />

This concludes the demonstration showing how to configure, view and analyze Windows event logs.
