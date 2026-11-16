# Levantamento de pendências do memorial descritivo

Análise de 16/11/2026, baseada nos arquivos locais do repositório, no PDF compilado e nos seis PDFs indicados. O levantamento não altera o texto LaTeX.

## 1. Diagnóstico

O memorial já tem uma base consistente para AGES I, II e III. A AGES IV tem contexto técnico, preparação, Sprint 1 e conclusão parcial. As maiores lacunas são a trajetória acadêmica/profissional consolidada, as atividades posteriores à Sprint 1, o fechamento da AGES IV e as considerações finais sobre as quatro passagens.

**Escopo confirmado pelo autor: memorial final das quatro AGES.** O texto atual declara explicitamente um recorte até a entrega de 18/09/2026. É necessário estender o relato da AGES IV até o encerramento do período, escrever sua conclusão final e incluir a apresentação da trajetória e as considerações finais. Ainda precisam ser confirmadas a data de encerramento e as sprints já concluídas; acontecimentos futuros não devem ser narrados como realizados.

Os três memoriais de outros alunos servem como referências de organização e profundidade de reflexão. Seus acontecimentos, avaliações e escolhas não são evidências da atuação de Arthur. Os textos de preenchimento dos modelos foram tratados como conteúdo de referência, sem presumir que constituam as regras oficiais vigentes da disciplina.

## 2. Situação de cada parte

| Parte | Situação observada | O que falta resolver |
|---|---|---|
| Capa | Identifica Arthur Fenilli de Souza, período 2023–2026 e AGES I–IV. Há um `\author{Gustavo}` residual. | Corrigir resíduo e conferir identificação, período e título com o modelo vigente. |
| Apresentação da trajetória | Arquivo contém somente orientações e não é incluído no `main.tex`. Parte da história inicial já aparece na introdução da AGES I. | Consolidar formação, experiências profissionais e relação com as quatro AGES. |
| AGES I — Plan Line | Introdução, contexto técnico, Sprints 0–4 e conclusão preenchidos. | Aperfeiçoar a identificação de algumas contribuições individuais, se houver registros disponíveis. |
| AGES II — certificação via blockchain | Introdução, contexto técnico, Sprints 0–4 e conclusão preenchidos. | Corrigir link de banco de dados herdado do Plan Line; completar identificação e cronologia. |
| AGES III — VínculoHub Portal | Capítulo completo diretamente no `main.tex`, com Sprints 0–4 e conclusão. | Especificar melhor algumas contribuições e o desfecho do deploy; confirmar período e interlocutores. |
| AGES IV — ReadRace | Introdução, contexto técnico, Sprint 0, Sprint 1, horas e conclusão parcial preenchidos. | Completar o período posterior ao recorte atual até o encerramento e substituir o fechamento parcial por uma conclusão final. |
| AGES IV — Sprints 2–4 | Os três arquivos contêm apenas instruções do modelo e não são incluídos pelo arquivo de atividades. | Registrar o que realmente aconteceu em cada sprint concluída e incluí-lo na compilação. |
| Considerações finais | Arquivo contém orientações e não é compilado. | Escrever a reflexão transversal sobre formação, competências, visão profissional e avaliação da AGES. |
| Referências | `.bib` contém exemplos fictícios; a seção de referências não é compilada. | Substituir exemplos por fontes efetivamente usadas, inserir citações pertinentes e imprimir as referências. |
| Sumário e elementos auxiliares | Há arquivos preparados para sumário, listas e outros elementos, mas somente a capa é incluída antes dos capítulos. | Conferir o modelo vigente; incluir sumário e demais elementos aplicáveis, sem presumir que todos sejam obrigatórios. |

## 3. Perguntas prioritárias para você responder

### A. Recorte e cronologia

1. **Tipo de entrega confirmado: memorial final das quatro AGES. Qual é a data de encerramento do período que deve entrar?** A definição do tipo de entrega está resolvida; falta somente o limite temporal.
2. **Quais são as datas de início e fim das sprints do ReadRace e quais já terminaram?** Confirmar especialmente Sprint 0 e Sprints 2–4; não descrever etapas futuras como concluídas.
3. **Em que semestre ocorreu a AGES III e quais foram seus períodos formais em AGES II e III?** AGES I está situada em 2023/2 e IV em 2026/2; AGES II contém o encerramento de uma sprint em 24/05/2024, mas falta padronização da cronologia.

### B. Trajetória acadêmica e profissional

4. **Quando você ingressou no curso e em qual semestre está agora?** O início do período da capa não comprova a data de ingresso.
5. **Quais estágios, empregos ou projetos profissionais teve durante a graduação?** Para cada experiência relevante: período, função, principais responsabilidades e tecnologias. A AGES III diz que você já trabalhava como desenvolvedor, mas não contextualiza essa experiência.
6. **Como a AGES influenciou sua entrada ou evolução no mercado e como o trabalho influenciou sua participação na AGES?** Há um começo dessa relação no texto, mas falta a ligação entre as quatro etapas.
7. **Houve pesquisa, extensão, monitoria, voluntariado, cursos ou hackatonas relevantes?** Incluir somente o que aconteceu e contribui para entender sua evolução.

### C. Atividades posteriores à Sprint 1 do ReadRace

Responder o roteiro abaixo separadamente para cada sprint que fizer parte do período do relatório:

8. **Qual era o objetivo da sprint e o que ficou sob sua responsabilidade?** Separar compromisso da equipe de responsabilidade individual.
9. **O que você efetivamente fez?** Incluir implementação, revisão, planejamento, acompanhamento, mentoria, negociação de escopo, testes, documentação e apresentação, conforme sua atuação real.
10. **Quais entregas sustentam esse relato?** Anotar links ou identificadores de issues/PRs, documentos, slides, decisões, demonstrações e datas. Nem toda contribuição de gestão terá um PR.
11. **Qual foi a dificuldade mais relevante, o que você fez a respeito e qual foi o resultado?** Registrar um episódio concreto em vez de somente dizer que houve problemas de comunicação.
12. **O que foi entregue e o que permaneceu pendente?** Distinguir código integrado, funcionalidade demonstrada e entrega aceita pelos stakeholders.
13. **Qual foi o feedback dos stakeholders e o que mudou a partir dele?** Indicar decisão ou alteração concreta quando existir registro.
14. **Qual aprendizado e qual autocrítica você tira dessa sprint?** Explicar também o que faria diferente.

### D. Continuidade das pendências já anunciadas no próprio relatório

15. **Como ficaram os squads criados para a Sprint 2?** Qual você acompanhou, com quem dividiu a responsabilidade, como verificava o andamento e como tratava bloqueios?
16. **A divisão em squads reduziu a concentração de tarefas perto do prazo?** Dar um exemplo observado; se não funcionou, explicar o que precisou mudar.
17. **As cinco tarefas do fluxo de desafios entre amigos transferidas para a Sprint 2 foram concluídas?** Em qual sprint, por quem e com que participação sua?
18. **Como evoluíram XP, níveis, streaks, conquistas e placar de desafios?** O texto atual distingue corretamente o cálculo de XP da gamificação completa. Manter essa distinção ao descrever a evolução.
19. **O usuário fixo da Sprint 1 foi substituído por autenticação real?** Qual solução entrou, quando e qual foi sua participação? Login por Google no escopo não comprova implementação.
20. **Quais interações sociais passaram a funcionar e quais continuaram fora da entrega?** O relato inicial descreve consulta e deixa interações para evolução.
21. **Como ficaram as apresentações e sua dificuldade com a timidez?** Você assumiu mais falas, conduziu alguma apresentação ou recebeu algum feedback? Comparar com o desafio registrado nas primeiras sprints.
22. **Como você usou agentes de IA na prática?** Qual parte orientou ou revisou, que erro ou ambiguidade encontrou e que decisão continuou sob sua responsabilidade? O texto cita automações, mas poderia aprofundar sua experiência individual.

### E. Resultado da AGES IV e qualidade da entrega

23. **Qual é o estado real do ReadRace no encerramento do período?** O que funciona, o que foi demonstrado, o que foi aceito e o que continuou pendente?
24. **Quais itens do escopo original foram entregues, adiados ou retirados por acordo?** Conferir autenticação, biblioteca, progresso, gamificação, desafios, feed, clubes, ranking, estatísticas, recomendações, mascote e administração. Não é necessário implementar tudo para relatar honestamente o resultado.
25. **O app foi disponibilizado de que forma e para quem?** Distinguir execução local, Expo Go, build instalável, distribuição em loja e uso efetivo. Confirmar também o estado do backend implantado, da Google Books API e do S3, que aparece apenas como previsto na wiki.
26. **Quais testes e validações você executou ou acompanhou?** Descrever fluxos, falhas descobertas e correções. Números de cobertura e de testes só devem entrar quando houver evidência correspondente ao período.
27. **Houve validação com leitores além dos stakeholders?** Se houve, registrar participantes, procedimento e resultados disponíveis. Se não houve, apresentar incentivo à leitura e contribuição social como objetivos ou impacto esperado, sem afirmar impacto comprovado.
28. **Há registros de horas depois de 17/09/2026?** As 31h37min36s atuais são apresentadas como atividades fora de aula em 16 lançamentos, agregados por data. Atualizar apenas com registros adicionais, preservando essa delimitação.

### F. Fechamento da trajetória

29. **Como mudou sua visão de Engenharia de Software entre o começo do curso e agora?** Relacionar programação, entendimento do problema, qualidade, pessoas e entrega com exemplos seus.
30. **Quais competências técnicas e interpessoais mais evoluíram em cada AGES?** O texto já permite uma linha inicial: descoberta do backend em I; banco de dados e Spring em II; apoio técnico, autenticação e reflexão sobre motivação em III; gestão e comunicação em IV. Falta validar essa síntese com sua percepção atual e os acontecimentos posteriores.
31. **Quais disciplinas ajudaram em decisões concretas dos projetos?** Informar o nome da disciplina, o conceito e onde foi aplicado; evitar uma lista genérica de matérias.
32. **O que repetiria e o que faria diferente ao liderar um novo projeto?** Relacionar com acompanhamento, distribuição de tarefas, autonomia, comunicação e interesse pelo negócio.
33. **Que críticas, elogios e sugestões concretas você tem para a AGES?** Apoiar em suas experiências, sem reproduzir as avaliações dos memoriais de referência.
34. **Que direção profissional pretende seguir e como as quatro AGES influenciaram essa escolha?** Não presumir que assumir gestão em IV signifique desejar carreira gerencial.

## 4. Complementos pontuais de AGES I, II e III

Esses capítulos não precisam ser recomeçados. As perguntas abaixo tornam o relato mais preciso, sobretudo onde há descrição coletiva ou pouco identificável.

| Local | Pergunta ou confirmação |
|---|---|
| AGES I, Sprint 2 | Além do estudo de Node.js, houve uma tarefa específica sua? Se a contribuição foi pequena, o relato pode manter essa avaliação sem inventar entregas. |
| AGES I, Sprint 3 | O CRUD que você implementou era de qual entidade e quais operações ficaram sob sua responsabilidade? Há MR, issue ou captura disponível? |
| AGES II, introdução | Qual o nome oficial do projeto, o período completo e a identificação do stakeholder Edimar, conforme os registros? |
| AGES II, banco de dados | Qual o link correto da documentação do banco do projeto blockchain? O link atual aponta para o Plan Line. |
| AGES II, Sprint 4 | Há evidência do comportamento antes/depois das operações assíncronas? Sem medições, evitar transformar a estimativa de 15 segundos em resultado quantitativo comprovado. |
| AGES III, introdução | Quem eram os stakeholders e qual foi o período do projeto? |
| AGES III, Sprint 1 | A pendência da tela de cadastro do primeiro projeto da ONG foi resolvida depois? Qual foi sua contribuição nesse fechamento? |
| AGES III, Sprint 2 | Quais telas, tarefas ou decisões você realizou diretamente? O texto descreve entregas do squad e acompanhamento, mas identifica pouco o trabalho individual. |
| AGES III, Sprint 3 | Qual foi a tabela sugerida, por qual necessidade e qual foi o desfecho? Quais partes da listagem/download de documentos você implementou? |
| AGES III, Sprint 4 | Qual débito técnico do painel administrativo você tratou e quais ajustes fez na listagem de notificações? |
| AGES III, encerramento | Os ajustes de deploy mencionados como próximos passos chegaram a ser resolvidos? Qual foi o estado aceito na entrega? |

Informações pessoais de saúde já aparecem na AGES II. Na revisão editorial, preservar apenas o nível de detalhe que você queira manter no memorial; não é necessário ampliar esse relato para preencher uma lacuna técnica.

## 5. Correções identificáveis sem novas respostas pessoais

1. **Conectar as partes já previstas na estrutura.** Após sua redação, incluir apresentação e considerações finais no `main.tex`. Incluir as sprints adicionais no arquivo de atividades da AGES IV somente quando forem preenchidas e pertinentes ao recorte.
2. **Resolver a duplicidade da AGES III.** O capítulo ativo está no `main.tex`; os arquivos separados não são incluídos. Os placeholders de sprint nesses arquivos não significam ausência de relato no PDF. Centralizar a versão válida para evitar editar o arquivo errado.
3. **Corrigir o link incompatível da AGES II.** A existência do erro já está demonstrada; apenas o endereço substituto depende da fonte correta.
4. **Remover resíduos do template.** Corrigir `\author{Gustavo}` e substituir as entradas fictícias do `.bib`. Os exemplos de `util/util.tex` não entram no documento e não devem ser confundidos com conteúdo publicado.
5. **Preparar referências reais.** As fontes já identificadas incluem repositórios, wiki local, termo de abertura, diagramas e Figma. Documentar origem e consulta efetivas, sem copiar datas de acesso dos exemplos. URLs no corpo não substituem uma seção de referências organizada.
6. **Preparar sumário e conferir elementos exigidos.** O PDF atual tem 53 páginas, começa os capítulos logo após a capa e termina na conclusão parcial da AGES IV. A contagem de páginas não é sinal de completude. As referências fornecidas usam uma estrutura mais completa, mas a exigência formal atual deve vir da orientação vigente.
7. **Revisar figuras e tabelas.** Padronizar títulos, fontes e chamadas no texto. A foto da AGES II está sem fonte explícita. A AGES IV tem figura de arquitetura e protótipos, mas não há diagrama do modelo de dados incluído nem captura identificada como resultado implementado. Selecionar material legível e pertinente, caso disponível.
8. **Revisar linguagem e terminologia.** Corrigir grafia e consistência, especialmente na AGES II; padronizar PostgreSQL, Ethereum, Spring Boot, nomes de perfis e títulos de seções. Explicar siglas na primeira ocorrência ou usar o mecanismo de siglas já previsto.
9. **Manter rastreabilidade individual.** Os oito PRs citados para a Sprint 1 já estão identificados. Acrescentar referências diretas às evidências de gestão, revisão de modelagem, slides e registros de horas quando disponíveis. Menções a consultas anteriores ao GitHub são afirmações do relatório, não verificações remotas refeitas nesta análise.
10. **Atualizar o fechamento para o memorial final.** Rever a introdução parcial, substituir a conclusão parcial e atualizar expressões de expectativa depois de incorporar os resultados posteriores. Distinguir o que foi alcançado no encerramento das melhorias que permaneceram para o futuro.

## 6. O que os anexos acrescentam

- **Memoriais de Henrique e Gabriel:** exemplos de trajetória integrada, descrição das quatro AGES e reflexão sobre acompanhamento, divisão em squads, comunicação e competências. Mostram inclusive percepções diferentes sobre um mesmo projeto; isso reforça que a avaliação deve ser pessoal e fundamentada.
- **Memorial de Eduardo:** exemplo de relação entre experiência profissional e AGES, atuação de gestão descrita por decisões e consequências, e fechamento da formação.
- **Modelo compilado de andamento ReadRace:** roteiro de estrutura, evidência individual e autoavaliação; ainda contém campos a preencher e não resolve a sua trajetória nem as sprints posteriores.
- **Compilado de informações gerais ReadRace:** oferece contexto extensionista de Cultura, ODS 4 e impacto esperado. Esses pontos podem enriquecer a introdução sem depender de novas respostas, desde que atribuídos à fonte.
- **Termo de abertura:** estabelece proposta, clientes, turma, escopo inicial e exclusões. Serve para comparar o planejado com o efetivamente entregue, sem presumir que todo o escopo tenha sido implementado.

Os gráficos de evolução usados nos memoriais são exemplos opcionais. Não foi encontrada uma exigência de produzir um radar; eventual gráfico deve refletir sua autoavaliação, com critérios claros.

## 7. Roteiro enxuto para reunir as respostas

Começar por quatro blocos, sem necessidade de responder todas as perguntas de uma vez:

1. **Recorte:** memorial final confirmado; informar encerramento do período e datas das sprints.
2. **Linha do tempo pessoal:** ingresso no curso, períodos das quatro AGES e experiências profissionais relevantes.
3. **Uma ficha por sprint adicional:** objetivo; minha responsabilidade; o que fiz; evidência; dificuldade; ação; resultado; feedback; aprendizado.
4. **Fechamento:** estado do produto; resultado dos squads; evolução pessoal; relação com disciplinas; avaliação da AGES; direção profissional.

Depois disso, resolver os complementos de AGES I–III e executar a revisão editorial e de compilação.

## 8. Fontes locais consultadas

Arquivos principais: `relatorio_ages/main.tex`, capítulos e sprints em `relatorio_ages/conteudo/`, arquivos auxiliares de estilo e bibliografia, as quatro páginas Markdown da wiki local e `relatorio_ages/main.pdf`.

PDFs fornecidos:

- `C:/Users/T-Gamer/Downloads/Memorial Descritivo - Henrique Reis Kops.pdf`
- `C:/Users/T-Gamer/Downloads/Memorial Descritivo -_Gabriel_Castro.pdf`
- `C:/Users/T-Gamer/Downloads/Memorial_Descritivo_Eduardo_Ballico.pdf`
- `C:/Users/T-Gamer/Downloads/modelo_compilado_relatorio_andamento_readrace.pdf`
- `C:/Users/T-Gamer/Downloads/compilado_informacoes_gerais_projeto_readrace.pdf`
- `C:/Users/T-Gamer/Downloads/Termo de Abertura do Projeto-6LM6NP-ReadRace (1).pdf`

Os repositórios externos citados no memorial não integram o checkout local analisado. O levantamento não verifica seu estado atual nem presume acesso aos documentos originais de horas, slides e gestão apenas mencionados no texto.
