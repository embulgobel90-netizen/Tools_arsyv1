proot-distro list
proot-distro login arsy          # Full 1-10GB 100 tools
proot-distro login arsy-lite     # Lite 9000KB 5 tools: nmap/PHP/wireshark/nikto/Linux

psi add Arsy        # login full
psi add arsy-lite   # login lite
psi add py4         # python3
psi add w4k         # wireshark
psi add n1m         # nmap
psi add Arsy -ghc   # clone from github
