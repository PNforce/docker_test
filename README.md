# mynode

Docker演示工程

lesson8
postgress admin4 使用，建立新伺服器
1.遇到localhost 192.168.0.1 or 192.168.11.20 無法用，在cmd 打docker inspect webdb，觀察docker內部ip，改打172.17.0.2
2.
可以順利連上
"Networks": {
                "bridge": {
                    "IPAddress": "172.17.0.2",
