NOT RESPONSIBLE FOR BRICKED DEVICE

1. put the firmware file in a directory on your computer and run 'python http.server 9000' from that directory
2. navigate to router web command input section and input 'wget -P /tmp http://COMPUTER-IP-ADDRESS-HERE:9000/ZBT-Z2101AX-full-GO2023-04-22-upgrade.bin' and press enter
3. input 'mpt -r write /tmp/ZBT-Z2101AX-full-GO2023-04-22-upgrade.bin /dev/mtd3' and press enter. Say a prayer and wait at least 10 minutes for it to reboot
