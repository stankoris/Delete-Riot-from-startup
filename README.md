Open regedit (Win + R > regedit)

<img width="398" height="203" alt="image" src="https://github.com/user-attachments/assets/f7d62130-1703-462e-abb4-8b7a30005e98" />


Navigate to HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run; delete keys named "RiotClient", "Riot Vanguard", or similar pointing to Riot paths 

<img width="485" height="747" alt="image" src="https://github.com/user-attachments/assets/36e0754d-7cbc-4e6d-ab0e-df0ac0e3fad0" />


HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run; delete keys named "RiotClient", "Riot Vanguard", or similar pointing to Riot paths.

Also check HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StartupApproved\Run for binary entries to delete.

Restart to apply changes. 

!!! wrong edits can cause issues. !!!
