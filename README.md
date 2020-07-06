# WindowsDNS
DNS Configuration File For Windows Server 2016
> set type=all
> _etcd-server-ssl._tcp.template.com
Server:  UnKnown
Address:  fe80::c71:8a41:56c8:9573

_etcd-server-ssl._tcp.template.com      SRV service location:
          priority       = 0
          weight         = 10
          port           = 2380
          svr hostname   = master0.template.com
_etcd-server-ssl._tcp.template.com      SRV service location:
          priority       = 0
          weight         = 10
          port           = 2380
          svr hostname   = master1.template.com
_etcd-server-ssl._tcp.template.com      SRV service location:
          priority       = 0
          weight         = 10
          port           = 2380
          svr hostname   = master2.template.com
master0.template.com    internet address = 192.168.40.12
master1.template.com    internet address = 192.168.40.13
master2.template.com    internet address = 192.168.40.14
>



