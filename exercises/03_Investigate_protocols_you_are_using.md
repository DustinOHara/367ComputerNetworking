## investigate applications and protocols on your computer

This week, you learned about TCP and UDP, the two most common protocols for sending data across a network. Both of these protocols are frequently used today, and each have benefits and drawbacks.

In this lab, you will investigate an application/program you use regularly to determine which protocol it uses. Use terminal commands to answer the following questions. You may search online only for appropriate commands and their documentation.

 

What application are you investigating?
Does this application use TCP or UDP? This should be determined by using terminal commands. Include all commands used.
Discuss (1-2 paragraphs) why the protocol (TCP/UDP) is appropriate for this application.
 

Hints:

The netstat command will display which ports are actively being used by TCP/UDP. Netstat can be configured to also display the PID associated with each connection.
There are various commands which display the processes associated with each PID, such as “tasklist” on Windows or “ps” on Mac/Linux
Most commands will only display information on active connections and programs. During your investigation, make sure the program you are investigating is running.
 

OS specific netstat documentation:
Windows: https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/netstat (Links to an external site.)
Mac/Linux: https://linux.die.net/man/8/netstat
