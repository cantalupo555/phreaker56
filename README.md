# phreaker56

### O que são esses scripts?

Esses scripts são pequenos programas executáveis escritos em linguagem shell script para simplificar ou automatizar tarefas em servidores VPS, Cloud ou Dedicado que rodem as distribuições Linux Debian e Ubuntu. Alguns deles também podem funcionar com o CentOS.

------------------------------------------

### VPS Manager 2.0

O VPS Manager 2.0 é conjunto de scripts feitos pra configurar automaticamente Proxy Squid e OpenSSH em servidores Linux, além de instalar comandos para facilitar o gerenciamento de usuários.<br>
Documentação: [VPS Manager 2.0 - Documentação.pdf](https://github.com/cantalupo555/phreaker56/blob/master/vpsmanager/VPS%20Manager%202.0%20-%20Documenta%C3%A7%C3%A3o.pdf)<br><br>
Comandos para instalar:

Primeiramente, atualize o sistema:

```bash
sudo apt-get update
sudo apt-get dist-upgrade -y
```

Agora execute:

```bash
wget https://raw.githubusercontent.com/cantalupo555/phreaker56/master/vpsmanager/vpsmanagersetup.sh
chmod +x vpsmanagersetup.sh
./vpsmanagersetup.sh
```
------------------------------------------

### TCP Tweaker 1.0

O TCP Tweaker 1.0 um script experimental que altera algumas configurações de rede do sistema Linux para melhorar a velocidade e estabilidade da conexão Proxy, VPN ou Túnel SSH. Caso as alterações não melhorem a navegação e estabilidade, basta executar o script novamente para desfazê-las.<br>
Comandos para executar:

```bash
wget https://raw.githubusercontent.com/cantalupo555/phreaker56/master/tcptweaker/tcptweaker.sh
chmod +x tcptweaker.sh
./tcptweaker.sh
```
------------------------------------------
