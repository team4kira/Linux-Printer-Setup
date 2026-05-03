# Linux-HP_Printer-Setup
A Guide to setting up your HP Printer on Linux
Steps in Terminal: 
1. sudo pacman -S cup-filters
2. sudo pacman -S cups-filters system-config-printer hplip
3. sudo pacman -S cups
4. sudo systemctl enable --now cups
5. sudo pacman -S simple-scan
6. sudo pacman -S hplip simple-scan sane
7. scanimage -L
8. sudo sane-find-scanner
9. sudo hp-plugin
10. sudo systemctl restart cups
11. setup (process will setup printer, fax and scanner and identify printer you are using HP)
12. simple-scan (to open scanner)
13. system-config-printer (to open printer configuration) 
