# PowerShell - IPv4 Port Scanner

Powerful asynchronus IPv4 Port Scanner for PowerShell.

## Syntax

```powershell
.\IPv4PortScan.ps1 [-ComputerName] <String> [[-StartPort] <Int32>] [[-EndPort] <Int32>] [[-Threads] <Int32>] [[-Force]] [<CommonParameters>]
```

## Example

```powershell
PS> .\IPv4PortScan.ps1 -ComputerName fritz.box -EndPort 500

Port Protocol ServiceName  ServiceDescription               Status
---- -------- -----------  ------------------               ------
  53 tcp      domain       Domain Name Server               open
  80 tcp      http         World Wide Web HTTP              open
``` 
