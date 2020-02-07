## SourceSec Security Research Group's Miranda UPNP Administration Tool

Miranda is a Python-based Universal Plug-N-Play client application designed to discover, query and interact with UPNP devices, particularly Internet Gateway Devices (aka, routers). It can be used to audit UPNP-enabled devices on a network for possible vulnerabilities. Some of its features include:

Interactive shell with tab completion and command history
Passive and active discovery of UPNP devices
Customizable MSEARCH queries (query for specific devices/services)
Full control over application settings such as IP addresses, ports and headers
Simple enumeration of UPNP devices, services, actions and variables
Correlation of input/output state variables with service actions
Ability to send actions to UPNP services/devices
Ability to save data to file for later analysis and collaboration
Command logging
Miranda was built on and for a Linux system and has been tested on a Linux 5.4 kernel with Python 3.8. However, since it is written in Python, most functionality should be available for any Python-supported platform. Miranda has been tested against IGDs from various vendors, including Linksys, D-Link, Belkin and ActionTec. All Python modules came installed by default on a Linux Mint 5 (Ubuntu 8.04) test system.

For more information about UPNP, visit the UPNP Forum.

For information regarding UPNP vulnerabilities, see UPNP Hacks and GNUCitizen.

Check out the Plug-N-Play Network Hacking article at the Ethical Hacker Network site. This is great use-case for the tool as well as the basics of UPNP.
