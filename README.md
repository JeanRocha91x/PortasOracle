<center>
<img src="https://guidocutipa.blog.bo/wp-content/uploads/2021/08/oracle-cloud.jpg" height="300" width="500">
</center>

# PORTAS ORACLE
Comandos para liberar portas

# COMADO PARA ATUALIZAR
```
sudo apt-get update
```

# INSTALANDO FIREWALL
```
sudo apt install firewalld
```

# LIBERANDO PORTAS
```
sudo firewall-cmd --zone=public --permanent --add-port=443/tcp; && 
sudo firewall-cmd --zone=public --permanent --add-port=80/tcp; && 
sudo firewall-cmd --zone=public --permanent --add-port=81/tcp; && 
sudo firewall-cmd --zone=public --permanent --add-port=8080/tcp; && 
sudo firewall-cmd --zone=public --permanent --add-port=8799/tcp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7300/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7100/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7200/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7400/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7500/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=8344/tcp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7295/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7296/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7297/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7298/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=7299/udp; && 
sudo firewall-cmd --zone=public --permanent --add-port=5454/tcp; && 
sudo firewall-cmd --zone=public --permanent --add-port=5000/tcp;
```

# RECARREGAR
```
sudo firewall-cmd --reload
```

# LISTA DAS PORTAS
```
sudo firewall-cmd --zone=public --list-ports
```
