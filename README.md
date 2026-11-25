# Petshop Amigo Fiel — Fase 2 (PUCRS Online)
Autor: Lucas Guidi Leite

Continuação da Fase 1: mantém catálogo e páginas existentes, acrescentando CSS responsivo, JavaScript, carrossel, relógio e formulário demonstrativo de cadastro e agendamento.

## Como publicar
Envie **todo o conteúdo da pasta site/** para a raiz do repositório https://github.com/lucasguidii/PETSHOP-FSW-FASE1, sobrescrevendo as seis páginas HTML anteriores. Envie também a nova página agendamento.html e a pasta assets/ completa. No GitHub Pages, use branch main e pasta /(root).

## Como testar
1. Abra index.html, clique nas setas do carrossel e no menu.
2. Abra as páginas de produtos e confira as seis imagens SVG locais.
3. Abra agendamento.html, teste os campos obrigatórios, e-mail, CPF de 11 dígitos, data passada, seleção de serviço e modalidade.
4. Confira acessibilidade via teclado: Tab, foco visível, link "Pular para conteúdo" e textos alternativos.
5. Atualize no GitHub Pages: https://lucasguidii.github.io/PETSHOP-FSW-FASE1/

## Limitações
O projeto é exclusivamente front-end. Não existe backend, pagamento, armazenamento, disponibilidade nem reserva real. CPF é validado quanto a formato de 11 dígitos, não quanto aos dígitos verificadores. Dados de cadastro não são enviados nem armazenados. Informações e preços são fictícios.

## Ajustes em relação à Fase 1
- Estilos consistentes e responsivos com CSS moderno; 
- Carrossel com controle manual e automático, com respeito a redução de movimentos;
- Atualização temporal de relógio, validação de datas e resumo de preços em JavaScript;
- Cadastro do tutor e do pet (input, checkbox, number, email, radio, required, select, date e textarea);
- Banho ou tosa; tele-busca ou entrega no local;
- Texto alternativo, navegação via teclado, rótulos de formulário, foco visível e região de status;
- Links relativos e imagens locais, sem dependência de CDN.
