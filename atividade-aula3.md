O objetivo  foi verificar a conectividade de rede da máquina virtual Ubuntu Server, identificar suas interfaces de rede e seus endereços IP e testar a comunicação com outros dispositivos e
com a internet e compreender o funcionamento básico do roteamento foram utilizados os comandos  ping, ip addr, ip route e sudo apt update e Também foi
realizada uma tentativa de instalação e execução do traceroute, utilizada pra investigar o caminho percorrido pelos pacotes até um destino.
tambem foram estudadas as diferenças entre os modos de rede NAT e Bridge do VirtualBox, considerando a atribuição de endereços IP, o gateway utilizado e apossibilidade de acesso à máquina virtual pelo computador host.
máquina virtual criada no Oracle VM VirtualBox, os comandos usados para Inspeção das Interfaces e Rotas:ip addr show,ip link, ip route,netplan status.
Testes de Conectividade em Camadas:ping -c 4 127.0.0.1,ping -c 4 <IP-da-sua-VM>,ping -c 4 10.0.2.2,ping -c 4 8.8.8.8,ping -c 4 google.com.
Rastreamento de Rotas:sudo apt update,sudo apt install -y traceroute,traceroute 8.8.8.8.
Alternar para o Modo Placa em Ponte:ip addr show,ip route,ping -c 4 8.8.8.8.
foi necessário verificar a conexão da máquina virtual com a internet e analisar as configurações de rede e Para isso, foram utulizados os comandos de teste de 
conectividade e consulta de rotas.
Também foi realizada uma tentativa de instalação e execução do traceroute para analisar o caminho dos pacotes até o destino.
Os comandos usuados permitiram verificar as interfaces de rede, os endereços IP e o gateway padrão da máquina virtual. com o gateway e com endereços externos
Também foi possível analisar a conexão com a internet e estudar as diferenças entre os modos NAT e Bridge do VirtualBox. Os testes com ping foram utilizados para verificar a comunicação
com a própria máquina com o gateway e com endereços externos. Também foi possível analisar a conexão com a internet e estudar as diferenças entre os modos NAT e Bridge do VirtualBox.
 
