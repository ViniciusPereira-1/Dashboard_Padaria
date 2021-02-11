# Dashboard - Padaria Trevo Dourado - 1.0
## DESCRIÇÃO
Dashboard em Excel, criada durante um minicurso, referente às vendas de uma padaria **fictícia**.
_______________________________________________________________________________________________
## Estruturação de nomeação:
### Intervalos e Macros
*bd_Main* -> Refere-se a Base de Dados em sua totalidade.

*td_XXXX* -> Intervalo das tabelas dinâmicas (ambas as colunas).

*seg_XXXX* -> Refere-se às segmentações de dados.

*tline_XXXX* -> Segmentação de linha do tempo.

*macro_XXXX* -> Refere-se às macros.

### Tabelas

*tab_XXXX* -> Tabelas regulares.

*tabD_XXXX* -> Tabelas Dinâmicas.
_______________________________________________________________________________________________
# VERSÃO ATUAL
### 1.1 - Melhorias Visuais e mais informações

**Referentes à Dashboard**

  *Mudanças:*
  - Melhorias nos ícones representativos nos gráficos de barras.
  - Agora apresenta o nome da companhia fictícia.
  
  *Implementação:*
  - Inclusão de exibições visuais total de itens vendidos, do faturamento total e da média de faturamento por item;
  - Inclusão de mais ícones e imagens decorativas.
  
  *Pendentes:*
  - Melhorias visuais na planilha Índice.
  
_______________________________________________________________________________________________
### HISTÓRICO
### 1.0 - Dashboard Funcional

**Referentes à Dashboard**

  *Mudanças:*
  - Inserção de mais três gráficos na Dashboard: Faturamento por categoria, Vendas por Item e Gráfico ABC.
  - Reestruturação da estrutura gráfica da dashboard (this is a buff).
  - Melhoria dos ícones representativos nos gráficos de barras.
  
  *Implementação:*
  - Filtros por Ano e Mês, além de uma timeline para intervalos específicos de tempo, que filtram e atualizam os gráficos.
  - Filtros específico de categorias para o gráfico de Vendas por Item.
  - Botões de "Atualizar Dados" e "Limpar Filtros" com a utilização de macros. 
  
**Referentes à Tabelas Dinâmicas**

  *Implementação:*
  - Inserção de uma tabela dinâmica (td_ABC) de Vendas por Itens associada exclusivamente ao gráfico ABC. Isto permite que os outros gráficos sejam filtrados sem causar anomalidades neste gráfico.
  
  *Pendentes:*
  - Inserção de mais ícones representando os produtos.
  - Melhorias visuais na planilha Índice.
  
### 0.5 - Construção da base de dados e início Dashboard

  - Transformação dos dados .csv em uma tabela bem formatada e legível.
  - Construção das tabelas dinâmicas de apoio, e da Tabela ABC dos produtos.
  - Construção da planilha de Índice, com botões.
  - Construção da estrutura gráfica da Dashboard, com a inserção do primeiro gráfico dinâmico.

