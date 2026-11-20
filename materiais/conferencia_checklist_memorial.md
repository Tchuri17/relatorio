# Conferência editorial com o checklist do memorial

Atualizado em **18/11/2026**, após a revisão editorial solicitada pelo autor. A versão anterior deste arquivo era um diagnóstico de pendências; este registro apresenta o trabalho realizado e os limites preservados.

Fonte dos critérios: `C:/Users/Arthur/Downloads/AGES-Checklist-MemorialDescritivo-v1.pdf`, duas páginas. Documento revisado: `relatorio_ages/main.tex` e seus arquivos incluídos. Os resultados verificáveis da compilação estão em [validacao_editorial.json](validacao_editorial.json).

## Estrutura — itens 1 a 24

| Itens | Resultado da revisão |
|---|---|
| 1 | Capa, resumo, sumário, apresentação, quatro capítulos de projetos, considerações finais e referências integrados à compilação. |
| 2 | Dedicatória, agradecimentos e epígrafe são opcionais; não foram incluídos textos genéricos do modelo. |
| 3–4 | Capa identifica instituição, escola, curso, AGES, autor, título, local e ano. O título informa 2023–2026 e AGES I a IV. Os metadados do PDF também identificam autor e documento. |
| 5 | Resumo em parágrafo único com palavras-chave ao final. |
| 6 | Lista de ilustrações gerada a partir das 17 legendas. |
| 7 | Não se aplica: não há tabelas no memorial; por isso não foi criada lista de tabelas vazia. |
| 8 | Lista de 30 siglas usadas, com as definições ligadas ao texto. |
| 9 | Sumário gerado pelo LaTeX, incluindo as sprints, com numeração atualizada após a compilação. |
| 10–12 | Hierarquia e numeração geradas pelo LaTeX. Capítulos começam em novas páginas; todas as páginas, exceto a capa, exibem número. |
| 13 | Apresentação atualizada com as experiências profissionais, oitavo semestre e direção atual para gestão. |
| 14 | Um capítulo por projeto. O conteúdo da AGES III foi reconciliado e transferido para seus arquivos próprios, eliminando a duplicidade de fontes de edição. |
| 15 | Os quatro projetos apresentam contexto, stakeholders, período, orientação e fotografia da equipe. Datas confirmadas, datas previstas e início estimado da Sprint 0 da AGES II continuam diferenciados. |
| 16–17 | As cinco subseções de desenvolvimento foram mantidas nos quatro projetos. Links foram organizados e as fontes institucionais integradas à bibliografia. |
| 18 | AGES II inclui modelo lógico, entidades, relacionamentos e relato do desenvolvimento da modelagem nas sprints. |
| 19 | AGES III descreve componentes, responsabilidades, autenticação, persistência e implantação, com figura e relato da atuação pessoal. |
| 20 | Os quatro projetos possuem telas comentadas. Foram acrescentadas três imagens reais das wikis: votação do Plan Line, emissão de certificados do AuthLink e painel de ONG do VínculoHub. |
| 21 | Tecnologias descritas por função, com referências à documentação oficial e às fontes dos projetos. As entradas fictícias do modelo foram substituídas. |
| 22–23 | As 20 sprints foram mantidas em subseções próprias. A seção de atividades inicia em nova página e as Sprints 1 a 4 também começam em novas páginas. Cada sprint ocupa ao menos uma página do PDF, sem criação de novas atividades para aumentar o texto. |
| 24 | Cada conclusão reúne avaliação técnica, autocrítica, comunicação, relação com disciplinas e aprendizados. O autor escolheu o ReadRace como melhor experiência por gestão e evolução pessoal; essa preferência aparece na comparação dos quatro projetos. |

## Conteúdo — itens 1 a 21

| Itens | Resultado da revisão |
|---|---|
| 1 | Terminologia revisada, com tradução de termos recorrentes quando apropriado e destaque dos estrangeirismos. Nomes próprios de produtos e identificadores de código foram preservados. |
| 2 e 8 | Revisão de concordância, pontuação, grafias e trechos repetitivos, com atenção aos capítulos antigos. Foram corrigidos nomes como PostgreSQL, Ethereum e Spring Boot. |
| 3–7 | Mantidas fonte, tamanho, alinhamento e espaçamento globais. Títulos e hierarquia organizados em todos os capítulos. Listas e referências usam apresentação adequada à sua função. |
| 9–10 | Todas as 17 figuras possuem legenda e indicação de fonte. As fontes da apresentação final e do termo de abertura também foram incluídas nas referências. |
| 11–12 | Revisão visual geral das páginas e inspeção da disposição das figuras. Foram removidas repetições que geravam páginas com poucos parágrafos e ajustadas as posições das figuras. Diagramas completos foram preservados, com arquivos de imagem mantidos para consulta ampliada. |
| 13–16 | Numeração sequencial pelo LaTeX, rótulos únicos, chamadas das figuras no texto e lista de ilustrações sincronizada. |
| 17 | Não se aplica enquanto não houver tabelas. |
| 18–20 | Siglas usadas foram inventariadas; as definições são apresentadas na primeira ocorrência correspondente e na lista. Não há entradas de siglas sem uso no texto. Nomes de produtos não foram tratados automaticamente como siglas a desenvolver. |
| 21 | Mantidas frases de apresentação antes das enumerações de fluxos, funcionalidades e repositórios. |

## Referências — itens 1 a 4

Bibliografia gerada com Biber e estilo `biblatex-abnt`, em ordem alfabética. São 49 entradas efetivamente citadas: documentação oficial das tecnologias, fontes institucionais dos projetos, repositório do ReadRace e dois documentos fornecidos pelo autor. A validação confere a correspondência entre chaves citadas e entradas da bibliografia, sem referências fictícias ou entradas não utilizadas.

As referências à documentação geral não alteram as versões históricas relatadas nos projetos. Fontes de projetos e documentos anexados sustentam a descrição da implementação; a documentação oficial sustenta a explicação da função de cada tecnologia.

## Verificação e limites

- Compilação com pdfLaTeX, Biber e novas passagens de pdfLaTeX para estabilizar sumário, referências e siglas.
- Conferência de legendas, fontes, chamadas de figuras, arquivos de imagem, citações, siglas e referências cruzadas.
- Conferência de numeração visível e de texto dentro das margens em todas as páginas.
- Inspeção visual geral antes e depois dos ajustes de paginação, com nova conferência das aberturas de sprint e dos elementos iniciais e finais.
- O registro de validação descreve o estado do documento; os testes dos projetos de software não foram executados nesta revisão.
- A estimativa histórica de 15 segundos, os marcos de cronograma e os limites dos testes do ReadRace permanecem explícitos. Não foram convertidos em medições ou entregas não comprovadas.
- Os complementos factuais ainda possíveis estão em [levantamento_pendencias_relatorio.md](../levantamento_pendencias_relatorio.md). Não são tarefas editoriais repetidas nem condições para inventar novos relatos.

## Procedência das novas imagens

A seleção desta revisão está documentada em [fontes_imagens_revisao_editorial.json](fontes_imagens_revisao_editorial.json). As telas do AuthLink e VínculoHub são cópias das imagens reunidas nas wikis; a tela do Plan Line é o primeiro quadro da demonstração em GIF. Nenhuma delas foi gerada por IA. A comparação da biblioteca do ReadRace mantém a origem já registrada na apresentação final.
