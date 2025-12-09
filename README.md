# The-Mega-hacking-group-project-of-death
Comp357- Final Project. This is the Browser Exploitation Framework

For this lab creation use Kali Linux, update the command sudo apt update and sudo apt full-upgrade before starting, as shown below.
For this lab you will need to install beef on kali. Use the command sudo apt install -y beef-xss. 

To run use the command beef-xss shows below show that is active and running and chose a password of your choice.
Once you start, it will ask you to make a new password. It will then activate the beef and automatically take you to the graphical interface, where you can enter your username and password.
It is an information page and direct you to all the practice hooks.

For this lab, we will use the website's demo page to run some of the commands. In addition to the two lab websites, also create a sample page where you can input information. For example, a copy of the code is available in a GitHub repository.  One thing to note in the code is that there is a script used to hook the webpage. 

The BeEF control panel using the loopback IP 127.0.0.1:3000. 
Once you have your code and webpage. Perform some safe attacks on safe test environment from BeEF and on our own. 
 
Attack Report: Browser Exploitation Framework 
Use the demos website provided. Follow the steps on the page and check the logs. Check the logs, the command that used were social engineering commands. More detail in the report.

Purple Team Mitigation Report
For the Purple Team exercise, we just saw how a website with no security measures can be impacted. There is another html called scpwebpage located in the GitHub if you like to use it. Will execute the webpage and see what happens. After putting CSP protected code BeEF cannot hook the website to collect log or execute malicious code. This is a good way to defend your website along with using other method like WAF.  Even with the Hook Me option the website is showing on the BeEF control panel as shown below.

