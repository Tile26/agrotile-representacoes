# Plano de implementação do AgroTile

## Etapa 1 — Aplicação e persistência
- Definir a stack após verificar o ambiente.
- Implementar autenticação segura.
- Configurar banco de dados e migrações.
- Não armazenar segredos no Git.

## Etapa 2 — Cadastros
- Categorias.
- Produtos, preços e estoque mínimo.
- Clientes e rotas.

## Etapa 3 — Operação
- Vendas com itens e pagamentos.
- Histórico de compras por cliente.
- Baixa de estoque transacional.
- Cancelamentos com estorno consistente.

## Etapa 4 — Relatórios
- Fechamento por período.
- Faturamento por rota.
- Vendas por cliente e produto.

## Regras
- Persistência no servidor.
- Valores monetários em centavos.
- Validar permissões no servidor.
- Não excluir histórico financeiro silenciosamente.
- Testar antes de publicar