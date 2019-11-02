# windows-bluetooth-adaptor

There are 2 ways to disable-enable bluetooth adaptor for windows ( tested on windows 10)


1st for non PRO or Enterprise version. create trigger Task Scheduler to enable bluetooth adaptor via PowerShell 
import file enablebluetooth.xml at Task Scheduler 
to disable import trigger at Task Scheduler 

2nd for PRO or Enterprise version. 
through gpeditor edit windows start script put the runena.cmd file or edit the exist one &  to disable import trigger at Task Scheduler (i didnt had time to impliment solution through gp so if you have solution free to post it)
