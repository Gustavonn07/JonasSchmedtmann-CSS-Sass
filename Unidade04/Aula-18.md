<!-- Linhas de comando (Instalar Sass) -->

# Requisitos:
1. Possuir node.js instalado para baixar via npm (Pode instalar em nodejs.org)
2. Usar o terminal com node

# Passo a passo:
1. Crie um pacote JSON. (Onde npm vai escrever os pacotes que usaremos):
    - `npm init`
    - Escreva o nome e a descrição do pacote

2. Instale Sass:
    - `npm install node-sass --save-dev`

3. Crie o CSS main e o Scss compilador:
    - `sass input.scss output.scss`

4. Coloque o CSS para compilar o Scss:
    - `--watch input.scss:output.css`

5. Use o Sass!