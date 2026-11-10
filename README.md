# Código Baobá

Curso gratuito de **Lógica de Programação** em formato de jogo, do site **Mestres Griôs**.

O aluno entra como estagiário(a) na Baobá Tech, uma startup de logística em Salvador, programa o robô Bit, escreve Python de verdade com testes automáticos, resolve mistérios no servidor e termina com projetos de portfólio prontos para o GitHub.

## Como jogar

Abra o `index.html` no navegador (ou pelo GitHub Pages). Não precisa de cadastro: o progresso fica salvo no próprio navegador.

## Conteúdo

**Parte 1: do zero ao intermediário**

| Capítulo | Tema |
|---|---|
| Prólogo | O griô e o baobá |
| Dia 1 | Algoritmos |
| Dia 2 | Variáveis e tipos |
| Dia 3 | Operadores |
| Dia 4 | Decisões |
| Dia 5 | Repetição |
| Dia 6 | Listas |
| Dia 7 | Funções |
| Madrugada | Depuração: o fantasma do servidor |
| Black Friday | A entrevista |

**Parte 2: nível avançado**

| Capítulo | Tema |
|---|---|
| Semana 1 | Textos (strings) |
| Semana 2 | Dicionários e CSV |
| Semana 3 | Laços aninhados e matrizes |
| Semana 4 | Busca e ordenação |
| Semana 5 | Recursão |

Cada capítulo tem prova rápida (para quem já sabe), aula em **Por quê? / Como? / O quê?**, atividade interativa, 3 exercícios de Python com testes automáticos, revisão e um búzio escondido. Os capítulos abrem em sequência.

**Projetos de portfólio** (o aluno faz 1, 2 ou os 3 de cada parte):

- Parte 1: Calculadora de Frete, Corretor de Quiz, Estoque da Cantina
- Parte 2: Rastreador de Pedidos, Ordenador de Rotas, Analisador de Vendas

## Tecnologia

- Um único arquivo `index.html`, com CSS e JavaScript embutidos
- Python no navegador com [Pyodide](https://pyodide.org) (carregado do CDN jsDelivr), rodando num Web Worker para que um loop infinito não trave o jogo
- Trilha sonora gerada com Web Audio e vozes dos personagens com a síntese de fala do navegador
- Progresso salvo no `localStorage` (chave `mg_codigo_baoba_v3`)

## Publicar no GitHub Pages

Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.

## Créditos

Criado por Márcia Rodrigues Campos para a Mestres Griôs.
