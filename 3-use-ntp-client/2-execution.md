# 3.2 Execution result

Perform a 'Periodic Update' or touch the 'Execute now' button to execute NTP time synchronization.

If you use a port number other than 123 as the NTP port number, a message box as shown below will appear. Touch 'Enter' to execute NTP time synchronization to that port, otherwise touch 'Cancel'.

<p align="center">
 <img src="../_assets/ntp-change-port-no.png"></img>
 <em><p align="center">Figure 3.3 Use a value other than 123 as the NTP port number</p></em>
</p>

Depending on the results of executing NTP time synchronization, a message box as shown below will appear.

<p align="center">
 <img src="../_assets/ntp-complete.png"></img>
 <em><p align="center">Figure 3.4 Results of NTP Time Synchronization(Success)</p></em>
</p>

NTP time synchronization was executed successfully.

<p align="center">
 <img src="../_assets/ntp-fail.png"></img>
 <em><p align="center">Figure 3.5 Results of NTP Time Synchronization(Fail)</p></em>
</p>

NTP time synchronization failed.

{% hint style="info" %}
* Make sure you entered the IP address (IPv4) of the NTP server correctly.
* Be careful not to enter a port number that is in use elsewhere as the NTP port number. We recommend using NTP standard port 123.
* If you do not want to execute periodic time synchronization, enter 0 for 'Update interval'.
{% endhint %}

