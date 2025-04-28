---
created: 2025-04-24T21:07
updated: 2025-04-28T17:32
---
# AvaliaINEP

Templates do Obsidian para auxílio à avaliação de cursos superiores em Tecnologia Computacional

Está em constante revisão, ainda é um rascunho. 😊
PRs são bem-vindos.

## Organização dos modelos

- `modelos/analise`: Análise dos indicadores de cursos superiores da área de tecnologia computacional, avaliação para autorização (A), reconhecimento (R) e renovação de reconhecimento (RR).
- `modelos/gerais`: Análise preliminar.

Os indicadores possuem um (R) ou (AR) que permitem identificar se é um indicador para avaliação de autorização (A), reconhecimento (R). É importante conferir novamente se o trecho do indicador está correto e igual ao do Formulário Eletrônico (FE) em uso!

## Recomendação de uso

- Uso no Obsidian com os seguintes plugins:
  - Note From Form
  - Mermaid
- Configure no Obsidian a pasta `modelos` como pasta padrão de modelos.
- Configure no Obsidian a pasta para notas conforme sua necessidade ou preferência.

> Dica
> O VSCode também pode ser utilizado, pois existem extensões como o 'Foam', o 'Markdown all in one' e o 'Markdown Preview Enhanced' que permitem simular o uso do VSCode de maneira semelhante ao Obsidian, embora o primeiro seja melhor. 😊

Ao realizar uma avaliação, recomenda-se:

1. Criar pasta para a sua avaliação no formato `123456 RRC SIGLA-IES Nome do curso`, para fins de organização;
2. Seguir o disposto em [[Processo de avaliação INEP]] e o [[TODO list de avaliação INEP]] (estão na pasta `processos`);
3. Na raiz da pasta usar o modelo [[INEP ! AP]] para análise preliminar offline, com orientações;
4. Na raiz da pasta usar o modelo [[INEP ! Resumo inicial da avaliação]] para análise dos dados iniciais, despacho saneador etc.
5. Adicionar as pastas 'Documentação' e 'Avaliação';
6. Em 'Documentação' apensar o PPC e o PDI para análise textual (são documentos públicos);
7. Em 'Avaliação' colocar cada indicador que será analisado, conforme constam os modelos da pasta `modelos\analise`;
8. Recomenda-se seguir [[Dependências entre indicadores para análise]] (na pasta `processos`) para sequenciamento lógico da análise. O diagrama é baseado no Mermaid e é muito útil para consolidar a coerência de toda a análise a ser realizada, pois a análise de um indicador contribuirá para elucidação de outros indicadores posteriores.

