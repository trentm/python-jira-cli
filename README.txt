
                          Python CLI for JIRA

Matt Doar
Consulting Toolsmiths
http://www.pobox.com/~doar

This CLI is an example of using Python and the JIRA SOAP API to
interact with JIRA from the command line. There is also another Atlassian CLI
written in Java at https://plugins.atlassian.com/plugin/details/6398

Usage:

First make sure that SOAP access to your JIRA instance is enabled via 
Admin, General Configuration, Accept remote API calls

After download you shouldn't need to install anything, just unpack the
package and run

python ./jira

at the command line and a list of the available commands should appear. For example:

python ./jira -s http://localhost:8080 projects

should prompt you to log in with your JIRA userid and password and
then display a list of the available JIRA projects.

Windows users can do the same thing with: 

C:\Python25\python.exe .\jira -s http://localhost:8080 projects

Versions:

The CLI should now work with JIRA versions from 3.4 to 4.2.
