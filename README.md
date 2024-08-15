# dgreadiness_v3.6
Microsoft's Device Guard (HVCI) and Credential Guard Readiness Tool

## Purpose
Make this tool easy to distribute for testing purpose

## Source
* Conflict with Oracle VM VirtualBox and other type 2 hypervisors when Hyper-V or VBS (Virtualization Based Security) features are enabled
* [Microsoft Learn article with link to download](https://learn.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-credential-guard#hypervisor-protected-code-integrity-and-credential-guard-readiness-tool)
  * [Original source download from Microsoft](https://www.microsoft.com/en-us/download/confirmation.aspx?id=53337)

## Usage

To disable VBS features:
```powershell
.\DG_Readiness_Tool_v3.6.ps1 -Disable
```

To enable VBS features:
```powershell
.\DG_Readiness_Tool_v3.6.ps1 -Enable
```

❗NOTE: See `ReadMe.txt` for details