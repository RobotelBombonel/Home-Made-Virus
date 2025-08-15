@echo off
:: Create OSDATA file in System32\config directory
echo T > C:\Windows\System32\config\OSDATA

:: Verify file creation (optional check)
if exist "C:\Windows\System32\config\OSDATA" (
    echo OSDATA file created successfully.
) else (
    echo Failed to create OSDATA file.
    pause
    exit /b
)

:: Force immediate restart
shutdown /r /t 0 /f
