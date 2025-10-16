# ADR 0002: Adoção de ADRs para Registo de Decisões

**Data:** 2025-08-27

## Contexto

À medida que um projeto evolui, decisões técnicas e de arquitetura importantes são tomadas (ex: escolha de uma biblioteca, definição de um padrão de código). 
Frequentemente, o contexto e a justificação para essas decisões perdem-se com o tempo, ficando apenas na memória da equipe ou em grupos para comunicação entre os membros (ex: whatzap). 
Isto torna difícil para a criação de documentações e entender o porquê que sistema o sistema foi construido de tal forma, podendo levar a que decisões passadas sejam revertidas sem o princípio ser distorcido.

## Decisão

Adotaremos o padrão **"Architecture Decision Records" (ADRs)** para documentar todas as decisões de arquitetura significativas. 
Cada decisão será registada num arquivo Markdown simples, com um formato padronizado (Contexto, Decisão, Consequências), 
e armazenada num diretório `/docs/adr` dentro do repositório do projeto.

## Consequências

**Positivas:**
* **Histórico Imutável:** Teremos um registo cronológico e claro de todas as decisões importantes, versionado junto com o código-fonte.
* **Facilita o Onboarding:** Professores podem ler os ADRs para entender rapidamente a evolução da arquitetura e as razões por trás das escolhas técnicas.
* **Melhora a Comunicação:** Fornece uma base sólida para discussões sobre novas decisões, permitindo-nos consultar o passado para informar o futuro.
* **Baixo Custo:** A criação de um ADR é rápida e utiliza ferramentas que já fazem parte do nosso fluxo de trabalho (Markdown, Git).

**Negativas:**
* **Disciplina Necessária:** Exige que a equipa se lembre ativamente de criar um ADR sempre que uma decisão importante for tomada.
* **Risco de Burocracia:** Se usado para decisões triviais, o processo pode tornar-se burocrático. Deve ser reservado para decisões com impacto significativo.
