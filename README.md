# Roleta de Prêmios — Postos Certo

Projeto estático, responsivo e pronto para GitHub Pages.

## Prêmios
- Picolé
- Água mineral
- Café
- Suco
- Doce
- Tente mais uma vez

Todos começam com a mesma chance.

## Publicar no GitHub Pages
1. Crie um repositório chamado `roleta-postos-certo`.
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. Abra **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch **main** e a pasta **/(root)**.
6. Salve e aguarde o endereço do GitHub Pages.

## Alterar probabilidades
Abra `js/roleta.js` e edite o campo `weight`.
Todos em `1` = chances iguais.

Exemplo: `Picolé weight: 2` e `Café weight: 1` faz Picolé ter o dobro do peso relativo do Café.

## Importante
Esta versão é 100% estática: o sorteio acontece no navegador. Ela não impede múltiplas tentativas por recarregamento da página e não controla estoque/resgate. Para uso com controle real de uma tentativa por cliente, códigos únicos ou estoque de prêmios, será necessário um backend.
