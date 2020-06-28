# **Redes de Computadores Abordagem Top Down - Resumo**

## O que é a Internet?

A internet é uma rede de computadores que interconecta incontáveis dispositivos de computação ao redor do mundo.

- Redes de computadores, se tornou um termo desatualizado visto que não são apenas computadores que se conectam a internet atualmente.
- Todos equipamentos conectados a internet são denominados **hospedeiros (hosts)** ou **Sistemas finais**.
- Sitemas finais se conectam através de **enlaces (links) de comunicação** e **comutadores (switches) de pacotes**
  - Enlaces podem ser de tipos diferentes: Cabos coaxiais, fios de cobre, fibra óptica, ondas de rádio.
  - Dependendo do tipo de enlace as taxas de transferência podem variar, sendo medido em bits por segundo.
  - Há diferentes tipos de comutadores de pacotes, mas os proeminentes são os roteadores e os switches (**comutadores de camada de enlace**).
- Quando um sistema final deseja enviar dados a outro sistema final, o emissor segmenta os bytes e adiciona bytes de cabeçalho a cada segmento. Os **pacotes**.
- Os dois tipos de comutadores citados acima encaminham os pacotes aos seus destinos finais.
- Os switches são geralmente usados em redes de acesso.
- Os roteadores são geralmente usados em núcleo da rede.
- O caminho através de enlaces e comutadores que um pacote percorre é chamado de rota ou caminho.
- Sitemas finais acessam a internet por meio de **Provedores de Serviço de Internet (Internet Service Providers) - ISPs**.
  - ISPs residenciais como empresa de TV a cabo ou telefonia
  - ISPs corporativos, de universidades.
  - ISPs que fornecem acesso sem fio em aerportos, hóteis, cafés e outros locais públicos.
  - ISP são redes de comutadores de pacotes e enlaces de comunicação.
  - Eles fornecem diferentes maneiras de acesso a Internet, como acesso resedencial de banda larga como modem a cabo ou **DSL (Linha Digital de Assinante)**
  - Acesso por LAN de alta velocidade, acesso sem fio e acesso por modem discado de 56 kbits/s.
  - ISPs tambem devem se interconectar. Eles se conectam em níveis, do mais baixo pro mais alto, nacionais e internacionais como: Level 3 Communications, AT&T, Sprint, NTT. 
  - ISPs de alto nível consiste em roteadores de alta velocidade interconectados por links de fibra óptica de alta velocidade. 
  - Cada rede ISP, seja de qualquer nível, é gerenciada de forma indenpendente executando o protocolo IP, obedecendo convenções de nomeação e endereço.
- Sistemas finais, os comutadores de pacotes e outras peças da Internet executam protocolos, que controlam o envio e recebimento de informações. O **TCP (Transmission Control Protocol)** e o **IP (Internet Protocol)** são dois dos mais importantes da Internet. 
  - O protocolo IP especifica o formato dos pacotes que serão enviados e recebidos entre roteadores e sistemas finais.
  - Esses principais protocolos são conhecidos como **TCP/IP**.

