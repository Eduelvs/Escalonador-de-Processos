# Escalonador de Processos

Este projeto implementa um escalonador de processos em C, simulando diferentes algoritmos de escalonamento de CPU. O objetivo é demonstrar o funcionamento de algoritmos clássicos de escalonamento, como FIFO, Round Robin, SJF, entre outros.

## Funcionalidades

- Simulação de múltiplos algoritmos de escalonamento de processos.
- Entrada de processos via arquivo ou manualmente.
- Exibição de estatísticas como tempo de espera, turnaround e ordem de execução.

## Algoritmos Implementados

- FIFO (First In, First Out)
- SJF (Shortest Job First)
- Round Robin
- Outros (dependendo da implementação)

## Requisitos

- GCC (compilador C)
- Make (opcional, caso exista um Makefile)

## Como compilar

```bash
gcc -o escalonador main.c
```
Ou, se houver um Makefile:
```bash
make
```

## Como executar

```bash
./escalonador
```

Siga as instruções exibidas no terminal para inserir os processos e escolher o algoritmo de escalonamento.

## Estrutura do Projeto

- `main.c`: Código-fonte principal do simulador.
- `README.md`: Este arquivo de documentação.

## Contribuição

Sinta-se à vontade para abrir issues ou pull requests com melhorias, correções ou sugestões.

## Licença

Este projeto está sob a licença MIT.
