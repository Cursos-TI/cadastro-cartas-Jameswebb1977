# Projetos de Programação em C

Coleção de projetos educacionais desenvolvidos durante o curso de programação em linguagem C, com foco em lógica, estruturas de dados e desenvolvimento de jogos.

## Estrutura do Projeto

### `/trabalhos`
Contém 4 trabalhos/desafios diferentes:

1. **cadastro_supertrunfo_logicadojogo_intermediario.c**
   - Cadastro de cartas para o jogo Super Trunfo
   - Coleta dados de duas cartas (estado, código, cidade, população, área, PIB, pontos turísticos)
   - Calcula densidade populacional e PIB per capita
   - Implementa lógica intermediária de comparação entre cartas
   - Nível: Intermediário

2. **cadastro_supertrunfo_logicajdojogo_mestre.c**
   - Versão avançada do cadastro Super Trunfo
   - Implementa lógica completa do jogo com comparações entre cartas
   - Inclui sistema de superpoder
   - Aplicação de todos os atributos para determinar vencedor
   - Nível: Mestre

3. **jogo-BatalhaNaval.c**
   - Implementação do clássico jogo Batalha Naval
   - Tabuleiro 10x10 (dimensões padrão)
   - Posicionamento de navios horizontais e verticais
   - Exibição do tabuleiro com coordenadas alfanuméricas (A-J, 0-9)
   - Nível: Intermediário

4. **movimento_pecasXadrez_nivelMestre.c**
   - Sistema de movimento de peças de xadrez
   - Implementa movimento de múltiplas peças: Torre, Bispo, Rainha, Cavalo
   - Utiliza recursão para movimentos verticais
   - Utiliza loops aninhados para movimentos diagonais
   - Demonstra diferentes abordagens algorítmicas
   - Nível: Mestre

## Conceitos Aplicados

- **Variáveis e Tipos de Dados**: int, float, char, arrays
- **Estruturas de Controle**: if/else, loops, recursão
- **Arrays Multidimensionais**: matrizes (tabuleiros)
- **Funções**: modularização de código
- **Operadores**: aritméticos, lógicos, de comparação
- **Lógica de Programação**: algoritmos, estruturas de decisão

## Como Usar

1. Compile o arquivo desejado:
```bash
gcc -o programa arquivo.c
```

2. Execute o programa compilado:
```bash
./programa
```

**Exemplo:**
```bash
gcc -o super_trunfo cadastro_supertrunfo_logicajdojogo_mestre.c
./super_trunfo
```

## Autor

Milton Ribeiro

