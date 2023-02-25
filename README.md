#基于逗比大神的ocserv一键脚本,怀念大神

自用一键脚本

``` bash
wget -N --no-check-certificate https://raw.githubusercontent.com/lgdglgc/ocserv88/master/ocserv.sh && chmod +x ocserv.sh && bash ocserv.sh
``` 



#修改 /var/lib/ocserv/profile.xml 文件中的内容可以将服务器的配置推送给客户端
``` bash
vi /var/lib/ocserv/profile.xml
``` 
``` bash
<ServerList>

                <HostEntry>

                    <HostName>服务器描述1</HostName>

                    <HostAddress>server1_ipaddress:port</HostAddress>

                </HostEntry>

                <HostEntry>

                    <HostName>服务器描述2</HostName>

                    <HostAddress>server2_ipaddress:port</HostAddress>

                </HostEntry>

</ServerList>
``` 
