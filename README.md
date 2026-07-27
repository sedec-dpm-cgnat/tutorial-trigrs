# Minicurso TRIGRS

Minicurso em formato **livro Quarto** sobre mapeamento de estabilidade de encostas
deflagradas por chuva com o modelo **TRIGRS 2.1** (USGS) — da instalação do compilador no
Windows à aplicação em bacia real, com visualização dos resultados no R.

**📖 Site do minicurso:** <https://sedec-dpm-cgnat.github.io/tutorial-trigrs/>

## Conteúdo

- **Parte 1 (disponível):** visão teórica didática (talude infinito + infiltração
  transiente) com fluxograma geral da metodologia, instalação do gfortran, compilação do
  código-fonte oficial, anatomia do exemplo tutorial, primeira rodada (TopoIndex + TRIGRS)
  e visualização dos resultados no R (`terra`).
- **Parte 2 (em construção):** bacia do Hospital São Lucas, Nova Friburgo/RJ — preparação de
  grades no QGIS e calibração com o inventário do megadesastre de janeiro/2011.
- **Parte 3 (em construção):** acoplamento TRIGRS → volumes de fluxo de detritos (Vdy1/Vdy2,
  metodologia GIDES/JICA).
- **Parte 4 (em construção):** cenários de mudança climática na chuva de projeto.

## Contexto

Material desenvolvido no âmbito da pesquisa de mestrado de **Érico de Castro Borges**
(Programa de Mestrado Profissional em Defesa e Segurança Civil/UFF), com co-orientação de
**Cássio Guilherme Rampinelli, PhD** (DPM/SEDEC/MIDR) e orientação do
**Prof. Marcos Barreto de Mendonça, PhD** (UFRJ). O repositório funciona
como caderno de laboratório da pesquisa: cada etapa vencida vira um capítulo, e o histórico
de commits registra o caminho completo.

## Como reproduzir / contribuir

- Os dados do exemplo estão em [`exemplo_01/`](exemplo_01/) (com os arquivos de inicialização
  já corrigidos e os resultados prontos).
- Para renderizar o livro localmente: `quarto render` (requer Quarto e R com o pacote `terra`).
- O fluxo de contribuição (novos capítulos, commit, push → publicação automática no GitHub
  Pages) está documentado no apêndice
  [Como adicionar capítulos](https://sedec-dpm-cgnat.github.io/tutorial-trigrs/91-como-contribuir.html).

## Licença e créditos

O TRIGRS é software de domínio público do U.S. Geological Survey (Baum, Savage & Godt).
Os dados em `exemplo_01/data` acompanham a distribuição oficial do TRIGRS 2.1.0.
