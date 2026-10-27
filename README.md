# Acompanhamento Financeiro

Dashboard financeiro estático, responsivo e em português (pt-BR), preparado para publicação no Netlify.

## Como executar
Abra `index.html` no navegador. Não há dependências ou etapa de build.

## Funcionalidades iniciais
- Indicadores de saldo, receitas, despesas e percentual de economia.
- Gráfico comparativo de receitas e despesas.
- Resumo de despesas por categoria.
- Lista de transações recentes.
- Formulário para adicionar receitas e despesas.
- Filtro entre este mês e todo o período.
- Persistência local no navegador via `localStorage`.

## Importante
Os registros iniciais são **dados ilustrativos de demonstração**, não dados bancários reais. As transações que você adicionar ficam salvas apenas no navegador/dispositivo utilizado; não existe backend nem sincronização entre dispositivos nesta versão.

## Publicar no Netlify
1. No Netlify, escolha **Add new site → Import an existing project**.
2. Conecte o GitHub e selecione `Gustavo-Gmae-Conv/Acompanhamento_financeiro`.
3. Configure a branch de produção como `main`.
4. Como é um site estático simples, deixe o comando de build vazio e o diretório de publicação como `.` (raiz do repositório).
5. Inicie a publicação.

Cada novo commit na branch configurada poderá acionar uma nova publicação automática.
