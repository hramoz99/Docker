# Docker
<p align="center">
  <img src="https://github.com/hramoz99/Docker/assets/78046279/342bf106-6c93-4b07-ab06-d0875c33c1c6" width="350" alt="Descrição da imagem">
</p>


## Conceitos Fundamentais

- `namespace`

- `cgroups`
  
- `Processos`

## Detalhando os conceitos 
Conhecendo os conceitos básicos de conteiner:

```
namespace: Garantia de isolamento de cada conteiner.
```
```
cgroups: Gerenciamento de sistemas (definir o poder computacional de cada conteiner).
```
```
processos: Cada conteiner é denominado um processo, por esta razão, o consumo de recurso é menor
```

## Níveis do namespace 

`PID:` Provê o isolamento dos processos rodando dentro do conteiner.

`NET:` Provê o isolamento das interfaces de rede.

`IPC:` Provê o isolamento da comunicação entre processos e memórias compartilhada 

`MNT:`  Provê o isolamento do sistema de arquivos/pontos de montagem.

`UTS:` Provê o isolamento do Kernel. Age como se o container fosse outro host
