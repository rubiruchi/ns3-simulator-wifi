# ns3-simulator-wifi
Simular uma Rede sem fio 802.11 no modo infraestruturado com uma ponto de acesso.


Como parte da avaliação da disciplina de MO655 - Gerência de Redes do programa de Pós graduação em Ciência da Computação do Instituto de Computação da Unicamp, este relatório apresenta os passos executados na construção de uma simulação de rede sem fio utilizando o simulador NS-3. A simulação consiste na avaliação de dispositivos que se comunicação através de uma rede sem fio, enviando pacotes para um servidor ligado ao ponto de acesso (AP) sem fio, utilizando modelos de tráfego em rajada e CBR. Para avaliar variados cenários, redes formadas exclusivamente por nós móveis e nós estáticos foram construídas, além de avaliar o desempenho dos modelos de tráfego por rajada e CBR nessas redes. Resultados mostraram, através das métricas vazão, perda de pacotes e tempo de atraso na entrega de pacotes, que redes realizando tráfego em rajada apresentaram um volume de pacotes perdidos e uma vazão inferiores às redes configuradas somente com nós utilizando CBR. A utilização de nós móveis afetou pouco o desempenho dos nós utilizando CBR, porém, para tráfego em rajada houve uma decréscimo de desempenho nas redes avaliadas.

## Table of contents

- **Dataset/**: Dados capturados durante 30 simulações de cada cenário avaliado;
- **Report/**: Relatório do projeto;
- **Results/**: Gráficos gerados a partir dos dados capturados;
- **Virtual Machine/**: Arquivos de configuração Vagrant e Docker para a montagem do ambiente de simulação.
- **script_de_execucao.R**: Script em R para a execução de todos os cenários avaliados na simulação;
- **script_de_graficos.R**: Script em R para a geração dos gráficos;
- **wifi_infra.cc**: Código em C++ desenvolvido para a simulação no NS-3.
