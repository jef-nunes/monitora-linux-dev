## Sobre
Monitores de sistema "conky" personalizados. O objetivo é fornecer um monitoramento de informações úteis em ambiente de desenvolvimento Linux. A configuração personalizada consiste em 2 arquivos distintos:

#### 1. monitor_principal:
Mostra informações de armazenamento, memória e processamento da máquina

#### 2. monitor_de_rede:
Mostra informações relativas à rede e conectividade da máquina.

## Exemplo de uso
Exemplificando como utilizar esse tema, utilizando dois terminais:
No terminal 1:
```shell
conky --config monitor_principal
```
No terminal 2:
```shell
conky --config monitor_de_rede
```
