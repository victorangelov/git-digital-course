## Anotações da aula de redes

* ipv4: formado por 32 bit´s  dividido em 4 octetos varia de 0 a 255
* exemplo: 1   1   1  1  1  1  1  1 .11111111.11111111.11111111
           128 64 32 16  8  4  2  1 
* exemplo: 192.168.1.1
* exemplo 255.255.255.255.255
* rede do computador 127.0.0.0

* NAT: faz com que equipamentos internos consigam se comunicar com a rede externa através de 1 único ip público e com que a rede externa consiga entregar para a rede interna para vários dispositivos conectados. 

* IPV6: formado por 128 bit´s dividido em 16 pares. 
* exemplo: 1050:0000:0000:0000:0005:0600:300c:326b(11050)

# Cálculo de sub-Rede
segmentar a rede, poder usar QOS quality of service, banda maior para quem precisar para poderem se comunicar
* Classes de rede
* Classe A 1 a 127  máscara 255.0.0.0, B 128 a 191 máscara 255.255.0.0, C 192 a 223 máscara 255.255.255.0 = mais utilizada 


# Domínio

# Principais comandos de redes de computadores
## prompt de comando cmd
* Ping: teste de comunicação entre hosts, protocolo icnp
* Ipconfig: informações sobre a rede
* cls: limpa a tela
* flush dns: Limpar o cache dns da máquina
* nslookup google.com.br: responde qual servidor dns retornou uma solicitação. 
* tracert google.com.br: verificar quantos saltos deu para chegar num determinado site. 
* router print: tabela de rotas ipv4
* netstat: mapear quais portas estão sendo utilizada pelo nosso computador

# Segurança da Informação
