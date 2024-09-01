Squid Windows Installer
==============

> Squid is a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. Squid has extensive access controls and makes a great server accelerator. It runs on most available operating systems, including Windows and is licensed under the GNU GPL.
> <cite> <http://www.squid-cache.org>

This project provides MSI Windows Installer for Squid Proxy Server. It enables Squid installation in just a few clicks. Current build is based on the latest Squid 6.10 build for Cygwin Windows 64 bit.

**Installation instructions**
-----------------------------
* [Download updated forked Squid 6.10 for Windows MSI installer] in the releases page https://github.com/thewriteway/squid-windows/releases/tag/v6.10
* Run it and click "Next" button till the product is installed

Please have a look at the tutorial describing [*How to Install Squid on Windows*](https://docs.diladele.com/howtos/installing_squid_windows/index.html).

**Native HTTP and HTTPS Filtering on Windows**
-----------------------------
In case you need a proxy and web filtering solution for Microsoft Windows with Admin UI, consider taking a look at [**Web Filtering Proxy**](https://webproxy.diladele.com/) project. 

Web Filtering Proxy is a Windows native web filtering solution that seamlessly integrates with Active Directory and provides rich content and web filtering functionality to sanitize Internet traffic passing into home/enterprise networks. It may be used to block illegal or potentially malicious file downloads, remove annoying advertisements, prevent access to various categories of web sites and block resources with adult/explicit content.

The MSI can be downloaded from [download page](https://webproxy.diladele.com/) or installed using Chocolatey ```choco install webproxy``` or Winget ```winget install webproxy``` package managers. Administator guide and various tutorials are available [here](https://webproxy.diladele.com/docs/). 

**Help**
--------

Squid documentation can be found at http://www.squid-cache.org. In case of any errors in the *installer only*, please send an email to support@diladele.com or post your question in the following google group https://groups.google.com/d/forum/web-safety. For squid specific questions please use one of Squid mailing lists http://www.squid-cache.org/Support/mailing-lists.html.

**Contribution guidelines**
---------------------------
Please contact support@diladele.com

**Credits**
-----------
We admire people working on Squid Cache server, who deliver great product to all of us.
