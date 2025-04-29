---
created: 2025-04-24T21:07
updated: 2025-04-29T13:05
state: "[[Rascunho]]"
---

# AvaliaINEP

Templates do [Obsidian](https://obdisian.md) para auxílio à avaliação de cursos superiores em Tecnologia Computacional

> **Atenção!**
>
> **Recomenda-se fortemente conferir sempre os conteúdos oficiais.** Este material **jamais** substituirá os procedimentos indicados e orientados pelo INEP. Desatualizações ou inconsistências podem ocorrer naturalmente. **Farei** atualizações **conforme** **atender a** demandas do INEP.
>
> Resolvi compartilhar este material, que **utilizo** durante minhas designações, na esperança de que seja útil **aos** colegas.
>
> Informo também que sou **apenas** um avaliador ad hoc, sem vínculo permanente com o INEP. Sou docente, Cientista da Computação e Engenheiro de Software, com experiência de mercado em **melhoria e auditoria da qualidade de processos em engenharia de software**. O material foi concebido com base em conhecimentos técnicos e experiência com avaliações nestas áreas (Computação e afins). Não atuo como consultor.
>
> Está em constante revisão, ainda é um rascunho. Pedidos de ajustes são bem-vindos através de Pull Requests.

## Organização dos modelos

- `modelos/analise`: Análise dos indicadores de cursos superiores da área de tecnologia computacional, avaliação para autorização (A), reconhecimento (R) e renovação de reconhecimento (RR).
- `modelos/gerais`: Análise preliminar.

Os indicadores possuem um (R) ou (AR) que permitem identificar se é um indicador para avaliação de autorização (A), reconhecimento (R). É importante conferir novamente se o trecho do indicador está correto e igual ao do Formulário Eletrônico (FE) em uso!

## Recomendações de Uso

Este material foi otimizado para uso com o [Obsidian](https://www.google.com/url?sa=E&q=https%3A%2F%2Fobsidian.md%2F).

**Configuração Inicial (Obsidian):**

1. **Instale os Plugins Recomendados:**
	- Note From Form: Para criar notas a partir de modelos predefinidos.		
	- Mermaid Tools (ou similar): Para visualização de diagramas Mermaid.
2. **Configure a Pasta de Modelos:** Defina a pasta modelos deste vault como a sua pasta padrão de modelos nas configurações do Obsidian.
3. **Configure a Pasta de Novas Notas:** Defina o local padrão para salvar novas notas conforme sua preferência (por exemplo, na raiz do vault ou em uma pasta específica).

> Alternativa: VSCode  
>
> O [Visual Studio Code](https://www.google.com/url?sa=E&q=https%3A%2F%2Fcode.visualstudio.com%2F) também pode ser utilizado. Extensões como Foam, Markdown All in One e Markdown Preview Enhanced oferecem funcionalidades semelhantes para trabalhar com notas em Markdown e visualizar diagramas. No entanto, a integração e a experiência de uso podem ser mais fluidas no Obsidian, especialmente com os plugins recomendados.

**Fluxo de Trabalho Sugerido para Avaliação:**

1. **Crie a Pasta da Avaliação:** Para melhor organização, crie uma pasta específica para cada avaliação, usando um padrão como: `123456 RRC SIGLA-IES Nome do curso`.
2. **Siga os Processos Definidos:** Consulte e siga as diretrizes descritas nos documentos [[Processo de avaliação INEP]] e [[TODO list de avaliação INEP]] (localizados na pasta processos).
3. **Análise Preliminar:** Utilize o modelo [[INEP ! AP]] na raiz da pasta da avaliação para registrar sua análise preliminar offline e orientações iniciais.
4. **Resumo Inicial:** Utilize o modelo [[INEP ! Resumo inicial da avaliação]], também na raiz, para consolidar dados iniciais, despacho saneador, etc.
5. **Estruture as Subpastas:** Crie as subpastas Documentacao e Avaliacao dentro da pasta principal da avaliação.
6. **Adicione os Documentos Base:** Na pasta Documentacao, salve os arquivos do PPC e PDI da IES (documentos públicos) para consulta e análise.
7. **Analise os Indicadores:** Na pasta Avaliacao, crie uma nota para cada indicador a ser analisado, utilizando os modelos correspondentes disponíveis na pasta modelos/analise.
8. **Considere as Dependências:** Consulte o diagrama [[Dependências entre indicadores para análise]] (na pasta processos) para um sequenciamento lógico da análise. Este diagrama (Mermaid) ajuda a garantir a coerência entre os indicadores, mostrando como a análise de um pode subsidiar a de outros.

<iframe width="560" height="315" src="https://www.youtube.com/embed/03DgCbd7eDg?si=YOn0SlpcP7DcZoMM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Sobre os diagramas e mapas mentais

![Exemplo de Diagrama](<imagens/README - image 001.png>)

Exemplo de diagrama de dependências entre indicadores de avaliação (disponível completamente em [[Dependências entre indicadores para análise]]).

- As caixas <font color="#00b050">verdes</font> são indicadores da Dimensão I
- As caixas <font color="#95b3d7">azuis</font> são indicadores da Dimensão II
- As caixas <font color="#e5b9b7">vermelhas</font> são indicadores da Dimensão III

### Motivação

> Este diagrama tem um duplo propósito: primeiramente, evitar a reanálise de atributos de indicadores já verificados; segundo, reduzir discrepâncias que podem surgir nas avaliações em dupla. Essas discrepâncias ocorrem com frequência quando cada avaliador analisa um conjunto distinto de indicadores e depois ambos precisam revisar e consolidar os resultados conjuntamente.

### Exemplo de Uso

 1. Recomenda-se iniciar a análise pelos documentos institucionais (neste caso, o PDI da IES).
 2. A partir dessa análise inicial (e de outros artefatos referenciados), obtêm-se subsídios para o indicador 1.1 (Dimensão I). Consulte também o disposto no modelo específico do indicador (disponível em: modelos/analise/INEP ! 1.01 Políticas institucionais no âmbito do curso).
 3. Após consolidar essa análise, obtêm-se dados e informações relevantes para os indicadores subsequentes, como os indicadores 1.13 e 3.18 (conforme ilustrado no diagrama).
 4. **Observe** que as setas no diagrama indicam o fluxo de informações entre os indicadores. Por exemplo, a análise do indicador 1.1 pode utilizar informações do 1.5. **Perceba** ainda que dados do indicador 1.13 também podem subsidiar a análise do 1.1, complementando-a.

<iframe width="560" height="315" src="https://www.youtube.com/embed/IsS4KB2Pxcg?si=AgqybYmIoCBxriRs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
---

**Motivação para o Diagrama:**

Este diagrama foi desenvolvido **porque** percebi que muitos dados e informações relevantes para a avaliação estavam dispersos. Além disso, notei que a sequência em que os indicadores são apresentados no Formulário Eletrônico não corresponde, necessariamente, a uma ordem eficaz **para a análise**. O diagrama visa, portanto, propor um fluxo mais lógico e integrado.

---

## Fontes e Autoria dos Materiais

- **Materiais Oficiais do INEP:** Grande parte do conteúdo disponibilizado, incluindo Glossário, guias de orientação, manuais e outros documentos didáticos, tem como fonte oficial o Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP).

- **Contribuições de Colegas:** Certos artefatos foram gentilmente cedidos ou elaborados por colegas avaliadores. É fundamental garantir a correta atribuição de autoria. Solicitamos que o responsável por esta compilação seja contatado em particular caso identifique alguma referência ausente ou que necessite de correção.
	 
- **Ferramentas de Análise (Autor):** Os modelos, mapas mentais e diagramas foram criados pelo organizador deste material como ferramentas para facilitar a análise de indicadores e a organização das avaliações. Ressalta-se que, embora sejam de elaboração própria, estas ferramentas se baseiam nos conhecimentos e diretrizes estabelecidos pela legislação, normas e publicações oficiais do INEP.

- **Condições de Uso e Atribuição:** A utilização de todos os materiais aqui reunidos é livre e gratuita, visando exclusivamente apoiar as atividades de avaliação. Contudo, é **obrigatório** que a autoria de cada componente (INEP, colegas ou o criador das ferramentas de análise) seja devidamente creditada em qualquer uso ou redistribuição.
