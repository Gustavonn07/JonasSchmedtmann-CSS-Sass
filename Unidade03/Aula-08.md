<!-- Análise do CSS (01) -->

# Resumo:
O CSS funciona com uma divisão de 2 fatores principais:
1. Seletor (O que vamos estilizar).
2. Bloco de declarações (Os estilos que sera usado).

## Tipos de estilos: 
1. Desenvolvedor (O que os dev criam como estilização).
2. Usuário (O que o user muda no estilo).
3. Navegador (Pré-definições do navegador).

# Análise por cascade:
O CSS é um estilo em modo cascada, que combina os tipos de estilos e resolve conflitos usando uma ordem de importância em modelo cascada:

Importância > Especificações > Ultima declaração.

## Importância:
1. Declarações dadas como !important pelo Usuário.
2. Declarações dadas como !important pelo Desenvolvedor.
3. Declarações do Desenvolvedor.
4. Declarações do Usuário.
5. Declarações do Navegador.

## Especificações: 
1. Estilos inline (no HTML).
2. IDs.
3. Classes / Pseudo-Classes / Atributos.
4. Elementos / Pseudo-Elementos.

## Ultima declaração: 
O ultimo elemento declarado.