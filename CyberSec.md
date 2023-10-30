- **Ping: Pra que ele serve? Como pinga um PC?**

  Resposta: Ele serve pra testar se o pc/servidor destino pode enviar e receber mensagens do pc origem. 
Se você quiser pingar uma máquina de ip = 3.0.0.2, basta você usar o comando acima no Windows: 

       ping 3.0.0.2
- **Pra que serve o comando "enable"?**
  
  Resposta: Ele serve pra você entrar no modo previlegiado de um aparelho Cisco.
  No modo privilegiado você pode mudar as principais configurações do aparelho como interfaces permitidas e tivas, acesso SSH, configurações de segurança, ETC.

- **Pra que serve o comando "enable password teste"?**
  
  Resposta: Serve pra o aparelho Cisco pedir uma senha quando você quiser entrar no modo privilegiado. Caso você não faça isso,
  qualquer pessoa poderá entrar livremente no modo privilegiado.

- **Pra que serve os comandos "#line console 0" e "#password cisco"?**

  Resposta: Servem pra o aparelho Cisco pedir uma senha quando você tenta usar o prompt de comando MESMO no modo não-privilegiado.

- **Pra que eu preciso inserir um IPv4 em uma interface?**

  Resposta: Para uma interface poder ser acessada AO SE USAR A INTERNET, ela deve ter um endereço IPv4 ou IPv6. Se ela não tiver uma interface com IPv4
  configurada, ela não poderá ser acessada PELA INTERNET.

- **Pra que configurar um aparelho pra conexão Telnet?**

  Resposta: "O Telnet é um protocolo que permite iniciar uma sessão e utilizar um computador
  remoto como se estivesse ligado directamente ao mesmo numa rede local." (IBM, 2021)
  
- **Pra que serve a configuração de segurança nas portas de um switch?**

  Resposta: Pra evitar que o switch se conecte a aparelhos de endereço MAC desconhecidos e potencialmente perigosos.

- **O que acontece se um switch com configuração de segurança ativa mudar para um aparelho desconhecido?**

  Resposta: A interface conectada no aparelho novo NÃO IRÁ FUNCIONAR!

- **Pra que serve criptografar as senhas de terminal e enable?**

  Resposta: Inicialmente as senhas são guardadas em texto simples em aparelhos Cisco, podendo ser visualizadas nas configurações atuais do sistema. Para evitar isso e aumentar a segurança, essas senhas podem ser criptografadas no modo privilegiado.

- **Qual é a diferença entre o protocolo HTTP e o HTTPS?**

  Resposta: Ambos são protocolos de transferência de informações na internet, mas o HTTPS faz a transferência de forma criptografada.
  Isso é fundamental pra uso em transporte de informações importantes e sigilosas, como informações bancárias, médicas, militares, etc.

- **O que é uma "Lista de controle de acesso"?**

  Resposta: É um conjunto de regras que permite ou impede acesso a uma determinada rede.

- **Como um mapa de IP feito de forma correta ajuda a proteger uma rede?**

  Resposta: Uma rede deve ter somente a quantidade de IPs necessários para a execução de uma tarefa. Se uma rede for atacada, somente os aparelhos
  daquela parte da rede serão afetados.  

- **O que é a máscara de uma rede?**

  Resposta: É uma sequência de 1s e 0s que indica o endereço da rede (feito pelos 1s) e o endereço de host (feito pelos 0s).

  Por exemplo. Uma rede 192.0.2.130 de máscara 255.255.255.0 tem como rede 192.0.2.0 e o host como 0.0.0.130
