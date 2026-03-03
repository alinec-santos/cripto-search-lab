# Criptografia-Casamento-Padroes

Este projeto foi desenvolvido como Trabalho Pratico 3 da disciplina de Projeto e Analise de Algoritmos na Universidade Federal de Vicosa (UFV) - Campus Florestal. O programa implementa solucoes para dois problemas: casamento exato de padroes em textos e criptografia baseada em cifra de deslocamento.

## 1. Funcionalidades

### Tarefa A - Casamento de Padroes
Implementacao de dois algoritmos para busca exata de padroes em arquivos texto:
- **Shift-And**: Algoritmo bit a bit para padroes curtos (ate 32 caracteres)
- **KMP (Knuth-Morris-Pratt)**: Algoritmo classico com pre-processamento do padrao

Funcionalidades:
- Buscar padrao em arquivo texto
- Medicao do tempo de execucao em nanossegundos
- Comparacao de desempenho entre os algoritmos

### Tarefa B - Criptografia (Cifra de Deslocamento)
Operacoes de criptografia e descriptografia baseadas em deslocamento de caracteres:

- **Criptografar arquivo**: Desloca caracteres usando chave fornecida
- **Descriptografar arquivo**: Restaura conteudo original com a mesma chave
- **Criptografar com chave aleatoria**: Gera chave aleatoria para criptografia
- **Analise de frequencia**: Calcula frequencia percentual de caracteres
- **Adivinhar chave**: Tenta deduzir a chave usada por analise de frequencia (baseado na lingua portuguesa)

## 2. Ferramentas e Tecnologias

- **Linguagem:** C
- **Compilador:** GCC
- **Medicao de tempo:**
  - `clock_gettime()` (Linux/macOS) - precisao nanossegundos
  - `QueryPerformanceCounter()` (Windows) - alta resolucao
- **Estruturas:** Mascaras de bits, vetores, alocacao dinamica

## 3. Compilacao e Execucao

### Compilar:
```bash
make
```
### Executar:
```bash
./programa
