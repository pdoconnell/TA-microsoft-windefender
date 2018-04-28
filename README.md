# TA-microsoft-windefender
Microsoft Windows Defender TA for Splunk®. Inputs and extractions for use 
with Splunk®.

# Author information
       Original Author: Patrick O'Connell
       Version/Date: 1.0.6 / April 27, 2018
       Sourcetype: XmlWinEventLog:Microsoft-Windows-Windows Defender/Operational
       Has index-time ops: false

# Update History
       1.0.6 April 27, 2018
       --------
       Updated lookup for event ID messages to match new Microsoft definitions.
       Thanks to Mark Baumgartner of Creighton University for the catch.

       1.0.5 Dec 30, 2017
       --------
       Fixed typo in EventTypes.conf. This makes tags work again. Thanks to
       Chris Keladis from Katana1.

       1.0.4 Nov 1, 2017
       --------
       Fixed wrong file inclusion for certification.

       1.0.3 Oct 31, 2017
       --------
       Added definitions for all magic values found in Defender logs as of today.

       1.0.2 Oct 1, 2017
       --------
       Fixing naming conventions and trademarks per SplunkBase documentation.

       1.0.1 Sep 28, 2017
       --------
       Fixed file_path and file_name extractions. Thanks to people both
       in Slack and the support team working at .Conf 2017.

       1.0.0 Sep 18, 2017
       --------
       Initial release

# Using this TA
       Configuration: Install TA via GUI on all search heads, install
       via your preferred method (manual or Deployment Server) on
       forwarders running on Windows running Windows Defender.

       Ensure that you have at least version 6.2.0 universal forwarders.
       This is because of the Windows XML event log format.

       http://blogs.splunk.com/2014/11/04/splunk-6-2-feature-overview-xml-event-logs/

       For information on Windows Defender event codes, see below.
       https://docs.microsoft.com/en-us/windows/threat-protection/windows-defender-antivirus/troubleshoot-windows-defender-antivirus


# Support
       This is a community supported TA. As such, post to answers.splunk.com
       and reference it. Someone should be with you shortly.

       Pull requests via github are welcome! The repository can be found
       at https://github.com/pdoconnell/TA-microsoft-windefender.
