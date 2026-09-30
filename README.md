<h1 align="center">Marcos Roberto Ries</h1>

<p align="center">
  Estudante de Ciência da Computação · Cachoeirinha, RS
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

<br>

Estudo engenharia de dados e construo projetos próprios para aprender na prática. Meu foco é modelagem de dados, SQL e construção de pipelines.

Tenho experiência profissional em suporte e infraestrutura de TI, em dois estágios, um deles em uma secretaria do Governo do Estado do RS.

Construí um fluxo de dados completo em duas etapas: um pipeline que extrai dados da API do Banco Central e carrega no PostgreSQL com carga incremental, e uma camada de transformação com dbt sobre esses dados.

<br>

## Projetos

<table>
<tr>
<td width="50%" valign="top">
<h4><a href="https://github.com/MarcosRies/elt-dbt-bcb-postgres">elt-dbt-bcb-postgres</a></h4>
<p>Camada de transformação com dbt Core sobre os dados do Banco Central carregados no PostgreSQL.</p>
<p><strong>O que foi feito</strong></p>
<ul>
<li>Modelos organizados em camadas de staging e marts</li>
<li>Testes de qualidade de dados: not_null, unique, relationships e accepted_values</li>
<li>Modelo incremental</li>
<li>Documentação gerada pelo dbt, com lineage dos modelos</li>
</ul>
<p>
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
</p>
</td>
<td width="50%" valign="top">
<h4><a href="https://github.com/MarcosRies/pipeline-sgs-postgres">pipeline-sgs-postgres</a></h4>
<p>Pipeline que extrai séries temporais da API do Banco Central (SGS), trata e carrega no PostgreSQL. Roda quantas vezes for necessário sem duplicar dados.</p>
<p><strong>O que foi feito</strong></p>
<ul>
<li>Extração de API pública com distinção entre falha e período sem dados</li>
<li>Conversão de tipos, descarte de registros inválidos e deduplicação do lote</li>
<li>Carga incremental via tabela de staging e <code>ON CONFLICT</code></li>
<li>Chave primária composta <code>(codigo_serie, data)</code> para impedir duplicidade</li>
</ul>
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h4><a href="https://github.com/MarcosRies/spotify-star-schema-postgres">spotify-star-schema</a></h4>
<p>Modelagem dimensional em star schema a partir de base pública.</p>
<p><strong>O que foi feito</strong></p>
<ul>
<li>Tabelas dimensão e fato, com definição de granularidade e chaves</li>
<li>Scripts DDL versionados e testados contra banco real</li>
<li>Carga em Python com credenciais em variáveis de ambiente, consultas parametrizadas e controle de transação</li>
</ul>
<p>
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
</p>
</td>
<td width="50%" valign="top">
<h4><a href="https://github.com/MarcosRies/analisador-csv-spotify">analisador-csv</a></h4>
<p>Leitura, limpeza e análise exploratória de base de dados em CSV.</p>
<p><strong>O que foi feito</strong></p>
<ul>
<li>Tratamento de inconsistências e valores ausentes</li>
<li>Análise exploratória sobre a base tratada</li>
<li>Documentação do processo e das decisões de limpeza</li>
</ul>
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
</p>
</td>
</tr>
</table>

<br>

## Tecnologias

**Banco de dados** — SQL, PostgreSQL, modelagem relacional e dimensional

**Transformação** — dbt Core: camadas de staging e marts, testes de dados, modelo incremental

**Linguagem** — Python, aplicado a manipulação de dados e integração com banco

**Bibliotecas** — pandas, SQLAlchemy, psycopg2, requests

**Versionamento** — Git e GitHub

<br>

## Contato

<p>
  <a href="https://www.linkedin.com/in/riesmarcos/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:marcos.hg600@gmail.com">
    <img src="https://img.shields.io/badge/E--mail-333333?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
