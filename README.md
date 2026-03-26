# Open Source Audit — MySQL
## Student Details
| Field | Details |
|-------|---------|
| Name | Abhinav Mishra |
| Registration Number | 24BSA10067 |
| Chosen Software | MySQL (Open Source Relational Database) |

## Project Description
This project is an audit of MySQL as an open-source software.
It explores its origin story, philosophy, dual licensing model,
Linux implementation, FOSS ecosystem, and a detailed comparison
with its proprietary alternative — Oracle Database.

## Shell Scripts

### Script 1 — System Identity Report
Displays system information including kernel version, logged-in
user, uptime, Linux distribution name, and the open-source
license covering the OS.

### Script 2 — FOSS Package Inspector
Checks whether MySQL is installed on the system, displays
package version and details, and prints a philosophy note
about MySQL using a case statement.

### Script 3 — Disk and Permission Auditor
Loops through key system directories and reports permissions,
owner, group, and disk usage of each. Also checks MySQL's
config directory specifically.

### Script 4 — Log File Analyzer
Reads a log file line by line, counts occurrences of a keyword,
and prints the last 5 matching lines as a summary.

### Script 5 — Open Source Manifesto Generator
Asks the user three interactive questions and generates a
personalized open-source philosophy statement, saving it
to a .txt file.

## How to Run Scripts
1. Give permission: chmod +x script.sh
2. Run script: ./script.sh

### Examples
```bash
./script1.sh
./script2.sh
./script3.sh
./script4.sh /var/log/syslog error
./script5.sh
```

## Requirements
- Linux (Ubuntu 22.04 or later)
- MySQL 8.0 installed (sudo apt install mysql-server)
- Bash shell

## Conclusion
MySQL is a powerful and reliable open-source relational database
management system that has powered the internet for decades.
Its dual licensing model, strong community, and real-world
adoption by companies like Facebook, WordPress, and Wikipedia
make it one of the most important open-source projects in
the world. This audit demonstrates how open-source software
can be both freely accessible and commercially sustainable.
the world. This audit demonstrates how open-source software
can be both freely accessible and commercially sustainable.

