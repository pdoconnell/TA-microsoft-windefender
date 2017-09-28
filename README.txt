TA-Microsoft-WinDefender v1.0.0
----------------------------       
       
       Original Author: Patrick O'Connell
       Version/Date: 1.0.1 / Sep 28, 2017
       Sourcetype: iXmlWinEventLog:Microsoft-Windows-Windows Defender/Operational
       Has index-time ops: false

Update History
----------------------------
       1.0.1 Sep 28, 2017
       --------
       Fixed file_path and file_name extractions. Thanks to people both
       in Slack and the support team working at .Conf 2017.

       1.0.0 Sep 18, 2017
       --------
       Initial release

Using this TA
----------------------------

       Configuration: Install TA via GUI on all search heads, install
       via your preferred method (manual or Deployment Server) on
       forwarders running on Windows running Windows Defender.

       Ensure that you have at least version 6.2.0 universal forwarders.
       This is because of the Windows XML event log format.
  
       http://blogs.splunk.com/2014/11/04/splunk-6-2-feature-overview-xml-event-logs/

       For information on Windows Defender event codes, see below.
       https://docs.microsoft.com/en-us/windows/threat-protection/windows-defender-antivirus/troubleshoot-windows-defender-antivirus


Support
----------------------------

       This is a community supported TA. As such, post to answers.splunk.com
       and reference it. Someone should be with you shortly.

       Pull requests via github are welcome!

