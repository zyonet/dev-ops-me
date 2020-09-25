# Windows Tools

## [rundll32.exe](https://www.tenforums.com/tutorials/77458-rundll32-commands-list-windows-10-a.html?__cf_chl_jschl_tk__=17e3f26288bd26d18e95a15f10f860a7a2c406dc-1601059515-0-ATl_NC49C7eMiOk7g-oapZDQ4OMt5bgVJOyNn8rBzcMUlKKRzZugX78fEmE31zJXxmsz_598ENSx4ArUoNtJq0Eo31A00tiymKTkPLW-vD7DboTEvFNmy82ik3CdRJPfs1519vLelINg0gVlQcyGiNnI0DiblE26tDUyfgJ9Fa4pLZXJYLNpMmyMkKvm_tz-YWvovbXVJtPF7SjZ3Kw8JxYHgvbXKdXWPVJu7o6qLgBSd9zHwSzmTJE0DALtqtWLNldOsCc3DIpZvq2STuyyDvfzQWakg_TS_uZas233QOhFR3sIQjUSv9xPfUw3J0IOQkmN0taZtrj-tRNgeb1AEUWNGRTP33ShPucTOj_SBPeWKrk9JJUXc9s3uevPI8OfYy9sjZCCm3Gg0UoY8prWYj1LepD7oyyHUbCvzWlVYQzn)

| Function | Rundll32 Command |
| :--- | :--- |
| Add Network Location Wizard | Rundll32.exe %SystemRoot%\system32\shwebsvc.dll,AddNetPlaceRunDll |
| Control Panel | Rundll32.exe shell32.dll,Control\_RunDLL |
| Environment Variables | Rundll32.exe sysdm.cpl,EditEnvironmentVariables |
| File Explorer Options - Search tab | Rundll32.exe shell32.dll,Options\_RunDLL 2 |
| Internet Explorer - delete all browsing history | Rundll32.exe InetCpl.cpl,ClearMyTracksByProcess 255 |
| Network Connections | Rundll32.exe shell32.dll,Control\_RunDLL ncpa.cpl |
| System Properties - Advanced tab | Rundll32.exe shell32.dll,Control\_RunDLL Sysdm.cpl,,3 |
| User Accounts | Rundll32.exe shell32.dll,Control\_RunDLL nusrmgr.cpl |
| Windows Features | Rundll32.exe shell32.dll,Control\_RunDLL appwiz.cpl,,2 |
| Windows Firewall | Rundll32.exe shell32.dll,Control\_RunDLL firewall.cpl |

