# ProcessFilterExample
 A C# process filter driver example.

The Process Filter Driver is a kernel-mode driver that filters process/thread creation and termination, it provides you an easy way to develop Windows application for the Windows process monitoring and protection. 

With the Process Filter Driver, it allows you to prevent the untrusted executable binaries (malwares) from being launched, protect your data being damaged by the untrusted processes. It also enables your application to get the callback notification for the process/thread creation or termination, from the new process information you can get the parent process Id and thread Id of the new created process, you also can get the exact file name that is used to open the executable file and the command line that is used to execute the process if it is available.
