-------------
1. Descargar y levantar la máquina **Docker**.

Tenemos dos archivos que son necesarios para levantar el **Docker**
![alt text](D:\Dockerlabs\Capturas\Levantardockertrust.png)

Ejecutamos el comando 
```bash
bash auto_deploy.sh trust.tar
```

![[dockerlevantado.png]]

2. Empezamos con el tema

![[ping.png]]
Con un ping a la máquina descubrimos que estamos ante una máquina *Linux*, ya que su **ttl** o **Time To Live** es de 64.

![[nmap 1.png]]

![[extractports.png]]

![[nmap 2.png]]

![[paginapacher.png]]

```bash
gobuster dir -u http://172.17.0.2/ -w /usr/share/seclists/Discovery/Web-Content/directory-list-2.3-big.txt -t 20 -x html,php,txt.bak
```

![[gobuster.png]]

![[secreto.png]]

![[hydra.png]]

![[ssh.png]]

![[pathvim.png]]

![[root.png]]
