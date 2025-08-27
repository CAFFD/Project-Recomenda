# **ADR 0003: Adoção de Diagramas como Código com Mermaid**

**Data:** 2025-08-27

## Contexto

A documentação da arquitetura de software requer diagramas (ex: Modelo C4, fluxogramas) para ser eficaz. A abordagem tradicional envolve a criação destes diagramas em ferramentas visuais externas (ex: Visio, draw.io), exportando-os como imagens estáticas. Estas imagens são difíceis de manter atualizadas, não são versionadas de forma eficiente com o Git e criam uma desconexão entre a documentação e o código.

## Decisão

Adotaremos a abordagem de **"Diagramas como Código"** utilizando a sintaxe **Mermaid**. Todos os diagramas de arquitetura serão escritos como texto dentro de blocos de código em ficheiros Markdown no repositório (ex: `docs/arquitetura.md`). A renderização visual será feita automaticamente por plataformas que suportam Mermaid, como o GitHub.

## Consequências

**Positivas:**
* **Documentação Viva:** Os diagramas evoluem junto com o código. As alterações na arquitetura podem ser submetidas na mesma *pull request* que as alterações no código, facilitando a revisão.
* **Versionamento Eficiente:** Sendo texto, os diagramas são facilmente versionados com o Git, permitindo ver o histórico de alterações de forma clara.
* **Consistência e Rapidez:** É mais rápido editar uma linha de texto do que manipular formas numa ferramenta visual, e o estilo dos diagramas permanece consistente.
* **Não requer software adicional:** A criação e visualização são feitas com as ferramentas que já utilizamos (editor de texto e GitHub).

**Negativas:**
* **Curva de Aprendizagem:** A equipa precisa de aprender a sintaxe básica do Mermaid.
* **Limitações Visuais:** O Mermaid é menos flexível do que uma ferramenta de desenho dedicada. Diagramas muito complexos ou com um estilo visual muito específico podem ser difíceis de criar.
