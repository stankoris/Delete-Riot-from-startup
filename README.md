Open regedit (Win + R > regedit)

Navigate to HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run; delete keys named "RiotClient", "Riot Vanguard", or similar pointing to Riot paths

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run; delete keys named "RiotClient", "Riot Vanguard", or similar pointing to Riot paths.

Also check HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StartupApproved\Run for binary entries to delete.

Restart to apply changes. 

!!! wrong edits can cause issues. !!!
