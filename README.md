# Task Unscheduler v0.0.1-pre-safe
Prevent new unwanted autoruns from sneaking into Task Scheduler.

Links about dangers hiding in Task Scheduler

https://www.csoonline.com/article/2621116/malware/malware-loves-windows-task-scheduler.html
https://attack.mitre.org/wiki/Technique/T1053

Except of dangerous pieces of software there are also popups appearing out of nowhere, adware, updaters, telemetry, apps "phoning home" etc.

Warning: This is the very first commit and the software was built in two evenings. Only tested on one computer with Windows 10 so far. Good luck!

Free and open source.

# Usage

- Download as ZIP
- Unpackd
- Double click "Install.bat", allow admin access
- Success message will(hopefully) appear
- Restart your computer(for some reason sometimes takes two restarts) and Unscheduler should detect itself. Press "S"
- From now on Unscheduler will check on each logon if no new crap was added to Task Scheduler

# Uninstalling

- Double click on "Uninstall.bat" and Task Unscheduler will stop annoying you on each restart

# TO-DO's - contribute if you want

- Silent check - Do not show anything on startup if nothing new was detected
- Detect if original system task was replaced by malware task
- Compare existing tasks to default list of your system build version
