# Corrida de Grilos - Multithreading

Trabalho realizado em 2021 para a disciplina "Jogos para Consoles", do **Curso Superior em Tecnologia em Jogos Digitais** no **IFRJ CEPF** (Instituto de Educação, Ciência e Tecnologia do Rio de Janeiro, Campus Eng. Paulo de Frontin).

## Projeto

Corrida de grilos em multithreading, onde cada grilo utiliza uma thread diferente.

Projeto escrito em Java com uso de Eclipse IDE.

## Instruções

### Executando

1. [Baixe e instale o Java](https://www.oracle.com/br/java/technologies/downloads/)
2. Clone ou baixe este projeto:

```
git clone https://github.com/sam-cavalheiro/corrida-grilos-multithreading.git
```

3. Navegue até o diretório onde você clonou ou baixou o projeto:


```
cd pasta/para/o/corrida-grilos-multithreading
```
	
4. Execute:

```
java src/Principal.java
```

### Valor das constantes

Você pode, opcionalmente, trocar as seguintes constantes para personalizar a experiência, e então rodar o `java src/Principal.java` novamente.

- [`src/Principal.java`](src/Principal.java)
	- `int CHEGADA`: O quão distante é a linha de chegada da corrida (em cm).
- [`src/Grilo.java`](src/Grilo.java)
	- `int TAMANHO_MINIMO_PULO`: Tamanho mínimo da aleatorização dos pulos (em cm).
	- `int TAMANHO_MAXIMO_PULO`: Tamanho máximo da aleatorização dos pulos (em cm).
	- `int RESETAR_TEMPO_MINIMO`: Tempo mínimo da aleatorização do tempo de intervalo (sleep) para o próximo pulo (em milissegundos).
	- `int RESETAR_TEMPO_MAXIMO`: Tempo máximo da aleatorização do tempo de intervalo (sleep) para o próximo pulo (em milissegundos).



## Em breve

- [ ] Atualizar projeto com correções feitas posteriormente em outro(s) projeto(s)