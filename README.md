# Faculdade_IESB
Projeto de Implementação de Segurança

Objetivo
Implementar uma solução de firewall para os serviços de correio eletrônico e servidor web.

Justificativa
Os serviços necessários a qualquer empresa dependem de uma solução robusta de firewall para garantir a segurança do seu ativo mais importante: a informação. Será utilizado um servidor web de alta disponibilidade e correio eletrônico opensource de ampla utilização no mercado brasileiro.

Etapas

1- Para este projeto será utilizado o Virtual Box, como ambiente de virtualização e serão criadas as seguintes máquinas virtuais: o firewall PfSense, o servidor web Apache e correio eletrônico, Zimbra, e por último uma máquina cliente.

2- Inicialmente o será instalado o PfSense com configurações padrões e adequadas conforme demanda e implementação dos outros serviços na rede.

3- O servidor web e correio eletrônico serão instalados no Debian 9, principalmente por se tratar de uma distro que tem como premissa a segurança de seus pacotes.

4- Será implementado neste servidor GNU/Linux o Apache 2 e o Zimbra

5- E por último será instalado uma máquina cliente com Windows 7/ Linux para teste das soluções implementadas.

Conclusão 

O PfSense será a camada de proteção desta pequena rede e todo o tráfego passará por ele, garantindo a segurança dos serviços implementados. O Apache é um dos servidores web mais utilizados no mercado, e além de ser opensource é necessário para a instalação do Zimbra, como correio eletrônico.
