Questão 01 - A respeito das camadas do modelo OSI avalie as afirmações seguintes e corrija a(s) errada(s):
II está incorreta. A camada de Enlace de dados é responsável por organizar bits. Comprimir dados e outras tarefas são tratadas em camadas superiores, não na camada de Enlace de dados.
Questão 02 - Cite e faça um breve resumo sobre cada camada do modelo OSI e do modelo TCP/IP. Ao final explique a diferença entre os dois modelos:
Camada Física: Esta camada lida com a transmissão de bits brutos.
Camada de Enlace de Dados: Esta camada organiza os bits, fornece endereçamento físico, detecta e corrige erros que podem ocorrer na camada física.
Camada de Rede: Responsável pela roteamento de dados entre redes diferentes.
Camada de Transporte: Fornece a comunicação de redes, gerenciamento do controle de fluxo e e de congestionamento.
Camada de Sessão: Gerencia, estabelece e encerra conexões entre aplicações em diferentes dispositivos.
Camada de Apresentação: compressão e criptografia dos dados de forma compreensíveis pelo sistema receptor.
Camada de Aplicação: Fornece serviços de rede aos processos de aplicação.
Diferença entre os modelos 
A principal diferença entre os dois modelos está na estrutura e na quantidade de camadas. O modelo OSI possui sete camadas, enquanto o modelo TCP/IP possui apenas quatro. 

Questão 03 - Você foi contratado para fornecer uma consultoria sobre topologias de redes de computadores.
Topologia em Estrela: Todos os dispositivos estão conectados a um único ponto central. Se algum dispositivo falhar, os outros ainda podem funcionar normalmente.
Topologia em Anel: Cada dispositivo está conectado a exatamente dois outros dispositivos, formando um "anel" de conexões. Se um dispositivo falhar, pode interromper a comunicação em todo o anel.
Topologia em Barramento: Todos os dispositivos estão conectados a um único cabo de transmissão, chamado de barramento. Os dados são enviados e recebidos por todos os dispositivos conectados ao barramento. Se o cabo principal falhar, toda a rede pode ficar inoperante.
Topologia em Malha: Cada dispositivo está conectado a todos os outros dispositivos na rede. No entanto, pode ser caro e complexo de implementar.
Topologia em Árvore: Uma combinação da topologia em estrela e em barramento. Os dispositivos são organizados em uma hierarquia. Isso permite expansão e escalabilidade.
Por ser mais simples e fácil em estrela pode ser a melhor opção. Ela é fácil de entender e administrar, devido à sua estrutura centralizada problemas podem ser facilmente identificados.
Questão 04 - Avalie as alternativas e corrija a(s) errada(s):
III está incorreta. WAN é uma rede de computadores que abrange uma grande área geográfica, conectando dispositivos em locais distantes, como cidades, países ou mesmo continentes. 

Questão 05 - Diferencie IPv4 do IPv6 e explique o motivo do surgimento do mais recente entre eles.
IPv4 utiliza endereços de 32 bits, o que limita o número total de endereços possíveis a aproximadamente 4,3 bilhões.
IPv6 utiliza endereços de 128 bits, permitindo um número muito maior de endereços possíveis, cerca de 3,4 × 10^38, o que é praticamente ilimitado.
o surgimento do IPv6 foi principalmente a exaustão dos endereços IPv4 disponíveis. Com o aumento exponencial de dispositivos conectados à Internet, a quantidade limitada de endereços IPv4 se tornou um problema. 

Questão 06 - Você foi até a casa do seu primo mais novo e ele te pediu ajuda por não estar conseguindo conectar o celular na internet. Ao acessar as configurações do dispositivo você se depara com a seguinte situação:
O que está causando a não conexão do dispositivo? Considerando que ip deva se manter estático, qual sua solução para resolver o problema?
Questão 07 - Considere a seguinte imagem usuário de um computador recebeu uma instrução para configurar endereço IP 192.168.100.15/16, em notação CIDR. Qual será o correto preenchimento do Endereço IP e da Máscara de sub-rede?
Questão 08 - Dado o ip 200.128.164.226. A máscara dessa rede é255.255.255. 192.Determine o prefixo da rede IPv4 na qual o host está ligado demonstrando todos os passos utilizados.
em binário:
255.255.255.192 = 11111111.11111111.11111111.11000000
200.128.164.226 = 11001000.10000000.10100100.11100010
11001000.10000000.10100100.11000000 (Prefixo de rede)
Convertendo de volta para decimal, obtemos a rede:
200.128.164.192
Questão 09 - A respeito do endereçamento IP e considerando a rede192.168.1.0/28
A) máscara de sub-rede para um prefixo /28 em binário é:
11111111.11111111.11111111.11110000
Em decimal:
255.255.255.240
Questão 10 - Em uma rede IPv4, um administrador precisa criar sub-redes para acomodar 50 hosts em cada uma. Qual seria a máscara de sub-rede mais apropriada a ser utilizada para atender a essa demanda?
