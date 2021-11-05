# icommands in cyverse discobery environment rstudio

Run the following in the `terminal` of RStudio to get the quantigene data for analysis.

`iinit`

Enter the host name (DNS) of the server to connect to: `data.cyverse.org`

Enter the port number: `1247`

Enter your irods user name: `shripad`

Enter your irods zone: `iplant`

Then enter the password and load the data using:

`iget -rPT /iplant/home/shripad/quantigene-analysis/ ./`
