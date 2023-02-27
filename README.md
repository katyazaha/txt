|            TASK                                                                 |         COMMANDS                                    |
|---------------------------------------------------------------------------------|:---------------------------------------------------:|
| 1. Create remote repository named TXT on web interface                          | ```New repository```                                |
|                                                                                 | ```Create repository```                             |
| 2. Clone repository on local host                                               | ```git init```                                      |
|                                                                                 | ```git clone https://github.com/katyazaha/txt.git```|  
| 3. Inside repository TXT create file named new.txt                              | ```touch new.txt```                                 |
| 4. Add file to github                                                           | ```git add new.txt```                               |
| 5. Commite file                                                                 | ```git commit -m "new"```                           |
| 6. Send file to github repository                                               | ```git push```                                      |
| 7. Modify file new.txt                                                          | ```vim new.txt```                                   |
| 8. Send changes to github                                                       | ```git add new.txt```                               |
|                                                                                 | ```git commit -m "about_me"```                      | 
|                                                                                 | ```git push```                                      |
| 9. Create file preferences.txt                                                  | ```touch preferences.txt```                         |
| 10. Add info about your preferences to file preferences.txt                     | ```vim preferences.txt```                           |
| 11. Create file sklls.txt and add info about your skills                        | ```touch skills.txt```                              |
|                                                                                 | ```vim skills.txt```                                |
| 12. Send both files to github                                                   | ```git add .```                                     | 
| 13. On web interface create file bug_report.txt                                 | ```Add file```                                      |
|                                                                                 | ```Create new file```                               |
| 14. Make Commit changes (save)                                                  | ```Commit new file```                               |
| 15. Modify file bug_report.txt on web interface, add bug-report in TXT format   | ```Edit this file```                                |
| 16. Make Commit changes (save) on web interface                                 | ```Commit new file```                               |
| 17. Sinchronize remote and local TXT repository                                 | ```git fetch```                                     |
|                                                                                 | ```git pull```                                      |