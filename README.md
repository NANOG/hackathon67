# hackathon67

Welcome!

This wiki serves as the home for resources & documentation for NANOG 67's Hackathon (http://nanog.org/meetings/nanog67/hackathon).


## Getting Started with the Virtual Private Server (VPS)
Each group will have a Virtual Private Server (VPS) assigned to collaborate on for the duration of the hackathon.  Login credentials will be provided at the Hack's opening.  Use of the VPS is not required and simply provided as a convenience.

The VPS will be running Ubuntu 14.04 LTS Server with current versions of Python, GoLang, and Perl installed.  MySQL server is also installed with appropriate Python modules for database access.

To access the VPS, connect using SSH and the credentials provided.  Each VPS runs a local "mosh-server" as well which provides a more reliable SSH-connection for use across un-predicatble network connections.  See mosh.mit.edu for more detail and to grab a free client.  If you have trouble connecting to the VPS via Mosh, note that Mosh uses UDP over non-standard ports -- so it may be blocked by your corporate VPN.
