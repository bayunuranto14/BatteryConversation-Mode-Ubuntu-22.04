<h2> Battery Conversation Mode Ubuntu 22.04 LTS</h2>
<h3>Switch Conversation Mode Battery for Ubuntu 22-04</h3>
<p>How to fixed battery stuck <60% in Ubuntu 22.04 . Tested by me </p>


<b>Tutorial : </b><br/>
<i>from terminal :</i>

--<b> sudo su </b>(for access root) <br/>
write password

--<b>Reading the current status:


<code>cat /sys/bus/platform/drivers/ideapad_acpi/VPC2004:00/conservation_mode </code> <br/><br/>
-- <b>Enable Conservation mode: </b> <br/>

 <code>echo 1  >  /sys/bus/platform/drivers/ideapad_acpi/VPC2004:00/conservation_mode</code><br/><br/>
-- <b>Disable conservation mode: </b> <br/>
<code>echo 0  > /sys/bus/platform/drivers/ideapad_acpi/VPC2004:00/conservation_mode </code>


<a href="https://askubuntu.com/questions/1038471/problem-with-lenovo-battery-threshold">Source Link  </a>
