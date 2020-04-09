# ARP-Spoofer
An arpspoof program designed in python
### Initiate:
```
python arp_spoof.py 
```
### Note: 
* Before Initiating the code rename the `target_ip` and `gateway_ip` variable from code.
  You can get these from the `Network Scanner` repository. So make sure to run the `network_scanner.py` before `arp_spoof.py`
* Now when the code will be running make sure to provide the ipforwarding through the attacker's machine.
    ```
    echo 1 > /proc/sys/net/ipv4/ip_forward
    ```
