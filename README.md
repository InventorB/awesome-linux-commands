**Network(ifupdown)**  
/etc/network/interfaces
auto slow0 
iface slow0 inet static
        address 10.0.0.250
        gateway 10.0.0.1

**/etc/ssh/sshd_config**  
PermitRootLogin
GatewayPorts

**Rsync**  
rsync -avz PATH USER@IP:PATH
-n test run
-v verbose
-z compression
-a archive perms
-i itemized list
