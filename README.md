# Dados para aplicações relacionadas a COVID-19 na CPLP, `dados-v1`

---

**REPOSITORIO `covid-taskforce-cplp/dados-v1` ARQUIVADO. Conteúdo antigo será
mantido por tempo indeterminado questões históricas**. Visite
<https://github.com/covid-taskforce-cplp/dados-covid> para acessar repositório
v2+ e <https://dados-covid.etica.ai/> para acesso via API.

---

[![goodtables.io](https://goodtables.io/badge/github/covid-taskforce-cplp/dados-v1.svg?1)](https://goodtables.io/github/covid-taskforce-cplp/dados-v1)
**Referências de APIs e conjuntos de dados para aplicações relacionadas ao
Coronavirus COVID-19. Foco na CPLP - Comunidade dos Países de Língua
Portuguesa:** Angola 🇦🇴, Brasil 🇧🇷, Cabo Verde 🇨🇻, Guiné Equatorial 🇬🇶,
Guiné-Bissau 🇬🇼, Macau 🇲🇴, Moçambique 🇲🇿, Portugal 🇵🇹, São Tomé e Príncipe
🇵🇹 e Timor-Leste 🇹🇱.

<!--
Google Docs:
  - README: https://docs.google.com/document/d/1pVZis7QkvCfdZu0aTJUE1rSB3ICKyGdkBM_9h3T8soM/edit
  - Pasta deste repositório: https://drive.google.com/drive/u/1/folders/1v8tQ3fV9r7u4KZxRtpIRKyxaKCR7Ok63
-->

Este repositóri usa padrão [DataPackage](https://specs.frictionlessdata.io/).
**Pré-visualize usando o [DataPackage Viewer: /covid-taskforce-cplp/dados-v1](https://data.okfn.org/tools/view?url=https%3A%2F%2Fgithub.com%2Fcovid-taskforce-cplp%2Fdados-v1)**.
_Vide [bug #11](https://github.com/covid-taskforce-cplp/dados-v1/issues/11)_ 

----

> **TL;DR: mesmo que você não faça parte do [@covid-taskforce-cplp](https://github.com/covid-taskforce-cplp)
  porém está desenvolvendo aplicações relacionadas ao COVID-19 este repositório
  contém recomendações do que está pronto para uso.**
  [Você também pode sugerir alterações ou propor novos datasets aqui](https://github.com/covid-taskforce-cplp/dados-v1/issues).

----

<!-- TOC depthFrom:2 depthTo:5 -->

- [APIs](#apis)
    - [Casos de COVID-19](#casos-de-covid-19)
        - [Global](#global)
            - [NovelCOVID/API](#novelcovidapi)
        - [Brasil](#brasil)
            - [brasil.io](#brasilio)
    - [Hospital, dados relacionados (*)](#hospital-dados-relacionados-)
    - [Glossario (*)](#glossario-)
    - [População, por faixa de idade (*)](#população-por-faixa-de-idade-)
- [Fontes de informação, outros](#fontes-de-informação-outros)
    - [datasus.saude.gov.br](#datasussaudegovbr)
    - [Por documentar](#por-documentar)
- [Ferramentas de Apoio](#ferramentas-de-apoio)

<!-- /TOC -->

----


## APIs

### Casos de COVID-19
> **Nossa recomendação padrão**: construa APIs usando uma opção que tenha dados
  a nível global, e então (casos exista) adicione mais detalhes com uma API
  que tenha detalhes do respectivo país.

#### Global

##### NovelCOVID/API
- **GitHub**: <https://github.com/NovelCOVID/API>
- **Painel**: Não aplicável
- **Documentação API**: <https://documenter.getpostman.com/view/8854915/SzS7R6uu?version=latest>
- **Funcionalidades**:
  - Casos confirmados de COVID-19
  - Mortes confirmadas de COVID-19
  - Histórico ao longo do tempo
  - Nível de detalhamento:
    - Nível de país
    - (Algumas regiões apenas) nível de província/estado/unidade federativa
      - Nenhum país da CPLP tem informações em nível mais detalhado do que de país

#### Brasil

> **Nossa recomendação padrão (2020-03-30)**: use a API do brasil.io e não perca
  tempo tentando minerar os dados do <https://covid.saude.gov.br/>.

##### brasil.io
- **Painel**: <https://brasil.io/api/dataset/covid19>
- **Documentação API**: <https://brasil.io/dataset/covid19/caso>
- **GitHub**: <https://github.com/turicas/covid19-br>

<!--
 ##### covid.saude.gov.br
- **GitHub**: Não aplicável
- **Painel**: <https://covid.saude.gov.br/>
-->

### Hospital, dados relacionados (*)

> Não implementado. Ver também:
> - <https://data.humdata.org/dataset/world-bank-indicators-of-interest-to-the-covid-19-outbreak>
> - https://datasus.saude.gov.br/>

### Glossario (*)

> Potencialmente converter um ou mais dos seguintes recursos para .csv/.json e
> dar créditos às fontes:
> - <https://www.kff.org/glossary/covid-19-outbreak-glossary/>
> - <https://www.rochester.edu/coronavirus-update/terminology/>
> - <https://www.cbc.ca/news/health/covid19-glossary-1.5510230>
> - <https://www.google.com/search?q=covid+glossary>


### População, por faixa de idade (*)
> Não implementado

## Fontes de informação, outros

### datasus.saude.gov.br
- **Site**: <https://datasus.saude.gov.br/>

### Por documentar

- <https://datasus.saude.gov.br/>
- <https://ourworldindata.org/coronavirus>
- <http://data.un.org/Host.aspx?Content=API>
- <https://data.humdata.org/>
  - <https://hxlstandard.org/>
- <https://covid-19-apis.postman.com/>
- <https://github.com/dadosgovbr/catalogos-dados-brasil>

<!--
- https://github.com/github/covid19-dashboard
-->

## Ferramentas de Apoio
Veja [ferramentas.md](ferramentas.md).
