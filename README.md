# Projeto: Máquina de estado finito

Este repositório contém projetos Quartus, códigos VHDL e simulações referentes à prática de diferentes implementações de uma máquina de estado finito, realizados em uma FPGA da série DE0-CV.

# Integrantes
- Fernando Lucas Vieira Souza - 12703069
- Artur Oliveira Arraes - 14745532

## Estrutura do Projeto

**Parte 1:**
- Implementação de uma memória de estado simples que detecta 4 entradas iguais consecutivas.
- O sinal z é atualizado para 1 quando o input w permanece com o valor 0 ou 1 por 4 ciclos de clock consecutivos. Enquanto w permanecer nesse mesmo sinal, z permanecerá ligado. Assim que w mudar de sinal, z será desligado. 
- Simulação e verificação do circuito.

**Parte 2:**
- Implementação de um tradutor de código morse usando uma máquina de estados.
- Simulação e verificação do circuito.
- Simulação no Quartus e exibição dos dados da memória em displays de 7 segmentos

## Instruções de Execução
1. No Quartus, abra o projeto da parte desejada.
2. Compile o arquivo VHDL correspondente.
3. Realize as simulações no ModelSim ou Technology Map Viewer.
4. Teste o circuito na placa, as atribuições de pinos para a FPGA já estão definidas.
