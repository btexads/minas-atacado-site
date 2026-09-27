# Minas Atacado — Prévia estática

Versão navegável para aprovação visual antes da implementação final.

## Publicação no Cloudflare Pages

1. Crie um repositório no GitHub e envie **o conteúdo desta pasta** para a raiz do repositório.
2. No Cloudflare, abra **Workers & Pages → Create → Pages → Connect to Git**.
3. Autorize o GitHub e selecione o repositório.
4. Framework preset: **None**.
5. Build command: deixe em branco.
6. Build output directory: `/` (raiz). Se a interface não aceitar `/`, deixe o diretório de saída padrão para site estático sem build conforme a tela apresentada.
7. Faça o deploy. O Cloudflare fornecerá uma URL `*.pages.dev`.

## O que funciona nesta prévia

- Navegação entre páginas
- Catálogo público com 34 produtos
- Busca e filtro por categoria
- Página individual do produto
- Carrinho de demonstração salvo no navegador
- Cadastro, login e formulário corporativo em modo visual/demonstração
- Catálogo PDF
- WhatsApp

## O que ficará para produção

Autenticação real, banco de dados, aprovação de clientes, tabelas de preço protegidas no servidor, painel administrativo, pedidos persistentes, importação XLSX/CSV e integrações de mensuração.
