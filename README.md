# Turn-of-remote-desktop-connection-certified-alert-when-use-RDP-connection-in-Windows

Open Command Prompt with Administrator permission and coppy + Hit Enter:
reg add "HKEY_CURRENT_USER\Software\Microsoft\Terminal Server Client" /v "AuthenticationLevelOverride" /t "REG_DWORD" /d 0 /f
