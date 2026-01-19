Open regedit (Win + R > regedit).

<img width="398" height="203" alt="image" src="https://github.com/user-attachments/assets/f7d62130-1703-462e-abb4-8b7a30005e98" />


Navigate to HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Run; delete keys named "RiotClient", "Riot Vanguard", or similar pointing to Riot paths.

<img width="485" height="747" alt="image" src="https://github.com/user-attachments/assets/36e0754d-7cbc-4e6d-ab0e-df0ac0e3fad0" />


HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Run; delete keys named "RiotClient", "Riot Vanguard", or similar pointing to Riot paths.

<img width="495" height="112" alt="image" src="https://github.com/user-attachments/assets/35135e9f-d2a7-4876-b9c9-d664dc23a6b5" />


Also check HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StartupApproved\Run for binary entries to delete.

<img width="737" height="148" alt="image" src="https://github.com/user-attachments/assets/9d5c2b63-8be7-4349-a07e-863ee9bb5396" />


Restart to apply changes. 

!!! wrong edits can cause issues. !!!
