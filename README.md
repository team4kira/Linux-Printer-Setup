# Linux-Printer-Setup
A Guide to setting up your HP Printer on Linux
Steps in Terminal: 
1. sudo pacman -S cup-fulters
2. sudo pacman -S cup-filters system-config-printer hplip
3. sudo pacman -S cups-filters system-config-printer hplip
4. sudo pacman -S cups
5. sudo systemctl enable --now cups
6. sudo pacman -S simple-scan
7. sudo pacman -S hplip simple-scan sane
8. scanimage -L
9. sudo sane-find-scanner
10. sudo hp-plugin
11. sudo systemctl restart cups
12. hp-setup (process will setup printer, fax and scanner and identify printer you are using HP)
13. simple-scan (to open scanner)
14. system-config-printer (to open printer configuration) 
