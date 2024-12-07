# Projeto: Memória RAM

Este repositório contém projetos Quartus, códigos VHDL e simulações referentes à prática de diferentes implementações de uma memória RAM de 32 palavras de 4 bits, realizados em uma FPGA da série DE0-CV.

# Integrantes
- Fernando Lucas Vieira Souza - 12703069
- Artur Oliveira Arraes - 14745532

## Estrutura do Projeto

**Parte 1:**
- Implementação de uma memória RAM de 32 palavras de 4 bits usando módulos predefinidos do Quartus e com o código memoria.txt, fornecido pelo exercício
- Simulação e verificação do circuito.

**Parte 2:**
- Criação um programa em VHDL que instancia a mesma memória RAM, mas recebe dados por meio das chaves da FPGA e exibe seus conteúdos em displays de 7 segmentos.
- Simulação e verificação do circuito.
- Simulação no Quartus e exibição dos dados da memória em displays de 7 segmentos

**Parte 3:**
- Implementação da memória RAM sem os módulos predefinidos do Quartus, mas usando um array de 32 elementos, onde cada elemento é um vetor de 4 bits.
- Simulação e verificação do circuito.
- Simulação no Quartus e exibição dos dados da memória em displays de 7 segmentos


**Parte 4:**
- Implementação de uma memória RAM mais especializada que recebe dois endereços: um para operações de escrita na memória, e outro para operações de leitura.
- Uso do modelo predefinido do Quartus denominado RAM: 2-PORT e criação de um arquivo MIF para inicializar essa memória com determinados valores.
- Uso de um contador de 1 segundo como o endereço de leitura, fazendo com que os dados da memória sejam lidos automaticamente
- O endereço de escrita de memória e seu respectivo dado que será escrito pode ser controlado a partir das chaves da FPGA.
- Um botão é usado para resetar o contador
- Simulação e verificação do circuito.
- Simulação no Quartus e exibição dos dados da memória em displays de 7 segmentos
  

## Instruções de Execução
1. No Quartus, abra o projeto da parte desejada.
2. Compile o arquivo VHDL correspondente.
3. Realize as simulações no ModelSim ou Technology Map Viewer.
4. Teste o circuito na placa, as atribuições de pinos para a FPGA já estão definidas.
