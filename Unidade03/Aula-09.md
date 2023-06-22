<!-- Análise do CSS (02) -->

# Análise por cascade:
O CSS é um estilo em modo cascada, que processa valores como porcentagem, rem, em,...
Qualquer tipo existente de valor é convertido em píxels.

## Ordem de processamento:

1. Valor declarado (Valor dito pelo dev).
2. Valor para cascada (Valor lido pelo navegador).
3. Valor específico (Valor sem alterações).
4. Valor computado (Valor convertido de realtivo para absoluto).
5. Valor usado (Valor convertido para leitura da cascada).
6. Valor final (Valor arredondado e final).