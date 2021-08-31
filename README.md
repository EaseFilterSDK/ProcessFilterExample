# [Process Monitoring and Protection SDK](https://www.easefilter.com/Forums_Files/Process-Monitor.htm)
 
The Process Filter Driver is a kernel-mode driver that filters process/thread creation and termination, it provides you an easy way to develop Windows application for the Windows process monitoring and protection. 

## Monitor the process or thread activities in real time
You can register the process or thread events to monitor the process or thread activities.

-  **OnProcessCreation**: Get the notification when the new process was created.
-  **NotifyProcessWasBlocked**: Get the notification when the process creation was blocked.
-  **NotifyProcessTerminated**: Get the notification when the process was terminated.
-  **NotifyThreadCreation**: Get the notification when the new thread was created.
-  **NotifyThreadTerminated**: Get the notification when the thread was terminated.
-  **NotifyProcessHandleInfo**: Get the notification when the process handle operation happens.
-  **NotifyThreadHandleInfo**: Get the notification when the thread handle operation happens.

## Prevent the untrusted process from being launched
With the Process Filter Driver, it allows you to prevent the untrusted executable binaries (malwares) from being launched, protect your data being damaged by the untrusted processes. It also enables your application to get the callback notification for the process/thread creation or termination, from the new process information you can get the parent process Id and thread Id of the new created process, you also can get the exact file name that is used to open the executable file and the command line that is used to execute the process if it is available.

## A C# process filter driver example.

[Read more about process filter example](https://www.easefilter.com/Forums_Files/Process-Monitor.htm)
