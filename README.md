# Tutorial TRIGRS — Parte 1: instalação, compilação e primeira rodada (Windows)

Tutorial em português (R Markdown, publicado no RPubs) mostrando como instalar o compilador
gfortran, compilar o código-fonte oficial do **TRIGRS 2.1** (USGS) no Windows e rodar o exemplo
tutorial, com visualização dos resultados no R (`terra`).

- **Tutorial renderizado (RPubs):** _link a adicionar após a publicação_
- **Fonte:** [`tutorial_trigrs.Rmd`](tutorial_trigrs.Rmd)
- **Dados:** [`exemplo_01/`](exemplo_01/) — exemplo tutorial oficial do USGS com os arquivos de
  inicialização já corrigidos (`tr_in.txt`) e resultados prontos (`Resultados/`), para que o
  `.Rmd` possa ser reproduzido sem rodar o modelo.

## Como reproduzir

1. Clone o repositório.
2. Abra `tutorial_trigrs.Rmd` no RStudio e faça *Knit* (requer o pacote `terra`), **ou** siga o
   tutorial para compilar o TRIGRS e refazer a rodada você mesmo.

Os executáveis não são versionados (`.gitignore`) — o tutorial ensina a compilá-los a partir do
código-fonte oficial: <https://code.usgs.gov/usgs/landslides-trigrs>.

## Contexto

Material de apoio à pesquisa de mestrado de Érico de Castro Borges (orientação: Cássio G.
Rampinelli) sobre acoplamento entre mapeamento físico de estabilidade de encostas (TRIGRS) e
estimativa de volumes de fluxo de detritos pela metodologia GIDES/JICA, com estudo de caso na
região serrana do Rio de Janeiro e incorporação de cenários de mudança climática.

Partes 2 e 3 (bacia real em Nova Friburgo/RJ e cenários climáticos) serão adicionadas neste
repositório.

## Licença e créditos

O TRIGRS é um software de domínio público do U.S. Geological Survey (Baum, Savage & Godt).
Os dados em `exemplo_01/data` acompanham a distribuição oficial do TRIGRS 2.1.0.
