# Inventário de TI

Sistema simples para controlar equipamentos de TI de uma empresa (notebooks, desktops, monitores, impressoras, access points, switches e periféricos), feito em HTML, CSS e JavaScript puro, sem bibliotecas e sem servidor.

> Esta é uma versão de demonstração com **dados fictícios**. Ela foi refeita do zero, inspirada em uma ferramenta interna de controle de inventário que desenvolvi durante meu trabalho em suporte de TI.

## Funcionalidades

- Cadastro, edição e exclusão de equipamentos (patrimônio, equipamento, tipo, setor, responsável e status)
- Status: Em uso, Em estoque, Manutenção e Baixado
- Painel com o total de equipamentos por status
- Busca por patrimônio, equipamento, responsável ou setor
- Filtros por status e por tipo
- Exportação da lista filtrada em CSV (abre no Excel)
- Dados salvos no navegador com `localStorage`
- Layout escuro e responsivo

## Como usar

Baixe o arquivo `index.html` e abra no navegador. Não precisa instalar nada.

## Tecnologias

HTML5, CSS3 e JavaScript (ES6+).

## Ideias para evoluir

- Histórico de movimentação (quem usou cada equipamento)
- Campo de garantia e data de compra
- Importação de CSV
- Versão com banco de dados
- Login com perfil de editor e perfil de visitante (somente leitura)

## Autor

Matheus Rorato, estudante de Análise e Desenvolvimento de Sistemas, com experiência em suporte de TI.
