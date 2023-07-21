<td style="width: 20%;"><img src="https://github.com/Epaminondaslage/OpenPLC/blob/master/img/Logo_CEFET-MG.png" width="20%" /></td>
<p><strong><span style="color: #0000ff;">Automação Industrial</span></strong></p>
<p><strong><span style="color: #0000ff;">Prof Epaminondas Lage</span></strong></p>
<a href="http://lattes.cnpq.br/7787341723868111"> Currículo Lattes LAGE, E. S.</a></p>

# Índice 

* [Introdução](#Introdução)
* [Modbus e  OpenPlC](#Modbus-e-OpenPlC)
* [OpenPLC e Home Assistant](#OpenPLC-e-Home-Assistant)
* [Node-RED](#Node-RED)
* [Repositórios Disponíveis](#Repositórios-Disponíveis)  

# Introdução 

A automação industrial refere-se à aplicação de tecnologia e sistemas para controlar e operar máquinas e processos industriais de forma automatizada. Ela utiliza sensores, atuadores, controladores e software para substituir ou complementar a intervenção humana, visando melhorar a eficiência, a precisão, a segurança e a produtividade nas indústrias.

A automação industrial com software de código aberto, como o Open Source, está revolucionando a forma como as empresas operam e gerenciam seus processos de produção. Ao adotar soluções de automação industrial de código aberto, as empresas podem aproveitar uma variedade de benefícios, como flexibilidade, personalização e redução de custos.

Com o uso de software de automação industrial de código aberto, as empresas têm a liberdade de personalizar e adaptar as soluções às suas necessidades específicas. Isso permite que elas desenvolvam sistemas altamente flexíveis e escaláveis, que podem ser facilmente modificados para atender a novos requisitos e demandas do mercado.

Além disso, a automação industrial de código aberto geralmente oferece uma ampla comunidade de desenvolvedores que colaboram e contribuem com melhorias contínuas. Isso significa que as empresas podem se beneficiar das últimas inovações e correções de bugs, sem depender exclusivamente de um único fornecedor.

Um projeto notável nesse contexto é o OpenPLC. O OpenPLC é um projeto de código aberto que oferece uma plataforma flexível e acessível para a implementação de automação industrial baseada em software e hardware abertos. Ele permite a criação e personalização de controladores lógicos programáveis (PLCs) de acordo com requisitos específicos.

O OpenPLC emprega o conceito de software PLC, em que o software é executado em um computador ou dispositivo em vez de um hardware dedicado. Ele é compatível com várias plataformas, incluindo Linux, Windows e Raspberry Pi, oferecendo flexibilidade na escolha do ambiente de execução.

O Editor OpenPLC é o software que roda em seu computador (Windorws, Mac ou Linux) usado para criar programas para o PLC. É muito simples de usar e suporta todas as cinco linguagens definidas no padrão IEC 61131-3: Ladder Logic (LD), Function Block Diagram (FBD), Instruction List (IL), Structured Text (ST) e Sequential Function Chart ( SFC).

# Modbus e  OpenPlC

O OpenPLC e o Modbus são duas tecnologias amplamente utilizadas no campo da automação industrial. 

O Modbus é um protocolo de comunicação utilizado para a troca de informações entre dispositivos de automação industrial. Ele opera em uma estrutura cliente-servidor, onde um dispositivo "mestre" (cliente) pode se comunicar com vários dispositivos "escravos" (servidores). O Modbus é amplamente utilizado para a comunicação entre controladores lógicos programáveis, sensores, atuadores e outros dispositivos em um ambiente industrial.

Uma combinação comum é o uso do OpenPLC para criar a lógica de controle e, em seguida, a comunicação com os dispositivos e equipamentos industriais por meio do protocolo Modbus. Essa integração permite que o OpenPLC se comunique com uma ampla variedade de dispositivos Modbus existentes no mercado, tornando-o uma opção versátil e poderosa para aplicações de automação industrial. Além disso, a natureza aberta e de código aberto tanto do OpenPLC quanto do Modbus oferece a possibilidade de personalização, ajustes e colaboração da comunidade, contribuindo para a melhoria contínua e a expansão dessas tecnologias.

# OpenPLC e Home Assistant

A integração entre o Home Assistant, o OpenPLC atrvés do protocolo Modbus oferece uma poderosa solução para automação residencial. O Home Assistant atua como uma plataforma centralizada para gerenciar dispositivos e serviços de automação residencial, enquanto o OpenPLC, usando o protocolo Modbus, fornece a capacidade de controlar equipamentos industriais e dispositivos que usam esse protocolo.

Através da integração com o OpenPLC via Modbus, o Home Assistant pode estender sua funcionalidade para além dos dispositivos de automação residencial padrão, permitindo que os usuários controlem e monitorem equipamentos industriais, como sensores, atuadores e outros dispositivos compatíveis com o protocolo Modbus.

Essa combinação oferece uma automação residencial mais versátil e abrangente. Os usuários podem criar lógicas personalizadas usando o OpenPLC para controlar dispositivos industriais e, ao mesmo tempo, usar o Home Assistant para criar automações e cenas que interagem com todos os dispositivos, tanto os da automação residencial quanto os do ambiente industrial.

Por exemplo, é possível criar uma automação que, quando detectar uma alta temperatura no sistema de aquecimento (monitorado pelo OpenPLC via Modbus), acione o ar condicionado ou um ventilador (controlado pelo Home Assistant) para equilibrar a temperatura do ambiente.

# Node-RED 

O Node-RED é uma plataforma de automação baseada em fluxos, que permite a criação visual de automações e integrações. Com o Node-RED, os usuários podem criar fluxos de automação arrastando e conectando blocos de ações, eventos e condições. Ele também oferece suporte a uma ampla variedade de integrações e extensões, tornando-o uma ferramenta poderosa para criar automações complexas e interações personalizadas entre dispositivos e serviços.

Ao combinar essas três ferramentas, os usuários podem criar um sistema de automação residencial altamente personalizado e flexível. Por exemplo, o Home Assistant pode ser usado como a interface principal para controlar dispositivos de iluminação, termostatos e câmeras de segurança, enquanto o OpenPLC pode ser usado para controlar equipamentos industriais em um ambiente de oficina. O Node-RED pode então ser usado para criar automações complexas que interagem entre esses dispositivos e serviços, permitindo cenários sofisticados que atendam às necessidades específicas dos usuários.

# Repositórios Disponíveis  

* <a href="https://github.com/Epaminondaslage/OpenPLC">Open PLC</a>
* <a href="https://github.com/Epaminondaslage/openplc-modbus">OpenPLC e ModBus</a>
* <a href="https://github.com/Epaminondaslage/HomeAssistant-NodeRED">Home Assistant</a>
* <a href="https://github.com/Epaminondaslage/HomeAssistant-OpenPLC">Home Assistant e OpenPLC</a>
* <a href="https://github.com/Epaminondaslage/OpenPLC/tree/master/primeirodiagrama">Primeiro diagrama no OpenPLC</a>
* <a href="https://github.com/Epaminondaslage/OpenPLC/tree/master/cargaruntime">Runtime do OpenPLC no Raspberry</a>
* <a href="https://github.com/Epaminondaslage/Diagramas-de-comandos-eletricos-de-motores">Diagramas de Comandos Elétricos</a>

