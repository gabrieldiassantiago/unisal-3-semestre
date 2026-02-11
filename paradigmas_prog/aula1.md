# Aula 1: paradigmas de programação

# Paradigma imperativo:
Resumo
------
É centrado no conceito de um estado (modelado por variações, tipo uma sequência de instruções que vão alterar o estado de alguma coisa do programa. Ele necessariamente não calcula o resultado que você deseja, mas especifica um "passo a passo" de como o computador consegue chegar nesse estado.

Características principais:
ENTRADA >= PROGRAMA => SAÍDA
            ESTADO
- Os estados podem mudar, variavéis e estrutura de dados são atualizadas ao longo do tempo
- A sequência de passos, é tipo listar todas as coisas que serão executados, sem desvios e repetições.
- Você consegue ter um controle do fluxo, o uso de condicionais (if/else), laços (for/while)
- Funções e procedimentos podem alterar um estado externo (isto é, ele pode acessar coisas fora dele mesmo e acessar outras coisas), *arquivos, variaveis, estados*
- 
# Threads 
É um conceito da computação que diz que as coisas podem ser executadas ambas ao mesmo tempo na mémoria, isso é, separar em processos.. (você pode abrir o chrome, o photoshop e outra aba do chrome), ambos ao mesmo tempo.. eles compartilharam o mesmo espaço de memoria (variaveis etc), mas eles tem pilhas de execução totalmente isoladas uma das outras. 

## Processo vs Thread
- Processo é o espaço em si isolado e sozinho, é mais custosa, IPC (comunicação).
- A thread compartilha a mesma memoria, como dito em cima, comunicação é direta, mas ainda sim exige que seja sincronizado para evitar condições de corrida 

