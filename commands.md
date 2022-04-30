| Command                                              | Action                               |
|------------------------------------------------------|--------------------------------------|
| net user                                             | Display local users                  |
| net user /domain                                     | Display domain users                 |
| net user ["username"] /domain                        | Enumerate user in domain             |
| net localgroup                                       | Display local groups                 |
| net localgroup /domain                               | Display domain user groups           |
| net localgroup ["groupname"] /domain                 | Enumerate group in domain            |
| net group                                            | Get domain groups (works only on DC) |
| net group /domain                                    | Enumerate domain groups              |
| net group ["groupname"] /domain                      | Enumerate specific group             |
| net use                                              | Enumerate shares                     |
| net start                                            | Show services that are started       |
| netstat                                              | Enumerate TCP connections            |
| netsh firewall show state                            | Enumerate Windows Firewall           |
| ipconfig                                             | Get IP info                          |
| route print                                          | Print routing table                  |
| tasklist /svc                                        | Enumerate running processes          |
| hostname                                             | Get hostname                         |
| set                                                  | Environment variables                |
| systeminfo | findstr /B /C:"OS Name" /C:"OS Version" | Enumerate OS and Version             |
| Schtasks /query /fo LIST /v                                   | Enumerate scheduled tasks         |
| whoami /priv                                                  | Enumerate your privileges         |
| echo %logonserver%                                            | Get Domain Controller name        |
| dir /s *password*                                             | Filesearch                        |
| findstr /s /n /i /p [wordhere]*                               | Filesearch                        |
| findstr /si pass *.txt | *.xml| *.ini                         | Filesearch                        |
| net user [username] [password] /add /domain                   | Add user                          |
| net group "Enterprise Admins" [username] /add /domain         | Add user to Domain Group          |
| net localgroup "Remote Desktop Users" [username] /add /domain | Add user to local group in Domain |
