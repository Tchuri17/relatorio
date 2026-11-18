# Imagens para o memorial

Acervo obtido das quatro wikis fornecidas pelo aluno em 17/11/2026. Os arquivos originais foram preservados. O manifesto [fontes.json](fontes.json) registra a p?gina de origem, URL do arquivo, dimens?es e hash SHA-256 de cada download.

Foram baixados 75 arquivos. A sele??o abaixo ? uma proposta editorial: alternativas e complementos n?o precisam aparecer simultaneamente no memorial. O memorial foi atualizado com oito figuras adicionais de equipe, banco de dados e arquitetura. As imagens j? presentes foram preservadas; a foto existente da AGES II recebeu chamada no texto, legenda e fonte. Os arquivos utilizados est?o identificados no manifesto pelo campo `memorial_file`.

A composi??o recomendada por projeto ? uma foto da equipe, um ou dois modelos de dados, um diagrama de arquitetura e duas ou tr?s telas relevantes. O n?mero final deve acompanhar a necessidade do relato, como nos memoriais de exemplo.

As legendas e os coment?rios abaixo s?o sugest?es para a edi??o futura. A figura dever? ser chamada no par?grafo, numerada automaticamente e acompanhada da fonte. Fotos e telas n?o comprovam, isoladamente, autoria ou participa??o em uma atividade.

## Cuidados de contexto

- ReadRace: a p?gina Design identifica as capturas como telas implementadas ao fim da Sprint 4. S?o diferentes dos prot?tipos j? presentes no reposit?rio e n?o devem ser apresentadas como evid?ncia visual da Sprint 1.
- PlanLine: os mockups web e mobile s?o GIFs animados. Para o PDF, ser? necess?rio escolher quadros representativos e identific?-los como extra?dos da anima??o. A modelagem foi preservada em SVG para manter a qualidade.
- AuthLink: o arquivo 13 cont?m a nota??o de entidades e relacionamentos, embora a wiki use a express?o modelo relacional. A legenda sugerida evita confundir esse desenho com o modelo l?gico do arquivo 14.
- Diagramas e telas retratam a vers?o dispon?vel nas wikis na data da coleta; a cronologia dever? ser conciliada com o relato pessoal.

## AGES I ? PlanLine

[Ver todas as imagens deste projeto](previas/planline.jpg)

### Equipe do projeto PlanLine

[Abrir imagem](planline/01-equipe.jpg) ? [Fonte na wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/home)

**Local sugerido:** Introdu??o.

**Coment?rio sugerido:** Apresenta a equipe respons?vel pelo projeto e contextualiza minha primeira participa??o na AGES.

### Arquitetura de implanta??o do PlanLine

[Abrir imagem](planline/07-diagrama_de_deploy.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/arquitetura)

**Local sugerido:** Arquitetura.

**Coment?rio sugerido:** O diagrama permite explicar a comunica??o entre as aplica??es web e mobile, a API e os servi?os de persist?ncia.

### Modelagem do banco de dados do PlanLine

[Abrir imagem](planline/08-Modelagem_do_Banco_de_dados.drawio.svg) ? [Fonte na wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/banco_dados)

**Local sugerido:** Banco de dados.

**Coment?rio sugerido:** Relacionar as entidades representadas ?s sess?es de vota??o e ? persist?ncia das informa??es do projeto, ap?s conferir os nomes no diagrama.

### Prot?tipo da interface web do PlanLine

[Abrir imagem](planline/09-web.gif) ? [Fonte na wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/mockups)

**Local sugerido:** Prot?tipos.

**Coment?rio sugerido:** A interface web organiza a condu??o da sess?o de planning poker. A imagem poder? acompanhar o relato sobre o menu lateral e as telas de gerenciamento, sem atribuir autoria de toda a tela ao aluno.

### Prot?tipo da interface mobile do PlanLine

[Abrir imagem](planline/10-mobile.gif) ? [Fonte na wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/mockups)

**Local sugerido:** Prot?tipos.

**Coment?rio sugerido:** A vers?o mobile apresenta a vota??o dos participantes, complementando o papel da aplica??o web durante a sess?o.

## AGES II ? Certifica??o por meio de Blockchain

[Ver todas as imagens deste projeto](previas/blockchain.jpg)

### Equipe do projeto Certifica??o por meio de Blockchain

[Abrir imagem](blockchain/04-WhatsApp_Image_2024-03-15_at_9.19.05_PM.jpeg) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/home)

**Local sugerido:** Introdu??o.

**Coment?rio sugerido:** Contextualiza a equipe do projeto tamb?m identificado pela marca AuthLink nas telas.

### Diagrama de componentes do AuthLink

[Abrir imagem](blockchain/11-diagrama-componentes.drawio__1_.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/arquitetura)

**Local sugerido:** Arquitetura.

**Coment?rio sugerido:** Explicar a separa??o entre interface, API, persist?ncia e opera??es na blockchain.

### Vis?o geral da arquitetura do AuthLink

[Abrir imagem](blockchain/12-AuthLink-arquitetura-overview.drawio.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/arquitetura)

**Local sugerido:** Arquitetura ? alternativa.

**Coment?rio sugerido:** Relacionar a autentica??o com Firebase, a API Spring Boot, o PostgreSQL e a rede Ethereum; usar apenas se acrescentar informa??o ao diagrama de componentes.

### Modelo de entidades e relacionamentos do AuthLink

[Abrir imagem](blockchain/13-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Banco-de-Dados)

**Local sugerido:** Banco de dados.

**Coment?rio sugerido:** O desenho permite discutir as entidades e rela??es modeladas no projeto. A wiki o chama de modelo relacional; a legenda final deve descrever a nota??o efetivamente apresentada.

### Modelo l?gico do banco de dados do AuthLink

[Abrir imagem](blockchain/14-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Banco-de-Dados)

**Local sugerido:** Banco de dados.

**Coment?rio sugerido:** O modelo aproxima a discuss?o da estrutura de tabelas, das chaves e da organiza??o dos dados; relacionar ao relato da modelagem realizada em dupla.

### Prot?tipo de cadastro de funcion?rio

[Abrir imagem](blockchain/20-cadastro-funcionario.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups)

**Local sugerido:** Prot?tipos / atividades.

**Coment?rio sugerido:** Relacionar a tela ? opera??o de cadastro descrita na Sprint 1, distinguindo a implementa??o do endpoint da autoria da interface.

### Prot?tipo de gerenciamento de funcion?rios

[Abrir imagem](blockchain/21-remocao-funcionario.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups)

**Local sugerido:** Prot?tipos / atividades.

**Coment?rio sugerido:** A listagem permite contextualizar a desativa??o l?gica de funcion?rios, explicando a preserva??o dos certificados vinculados no relato da Sprint 3.

### Prot?tipo de consulta de certificado

[Abrir imagem](blockchain/23-consulta-certificado.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups)

**Local sugerido:** Prot?tipos.

**Coment?rio sugerido:** A consulta exemplifica o objetivo do produto de permitir a verifica??o de certifica??es.

### Diagrama de implanta??o do AuthLink

[Abrir imagem](blockchain/31-Diagrama-de-deploy.drawio.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Infraestrutura)

**Local sugerido:** Arquitetura ? complemento.

**Coment?rio sugerido:** Usar se a infraestrutura for discutida no texto; evitar repetir a mesma explica??o do diagrama de componentes.

## AGES III ? V?nculoHub Portal

[Ver todas as imagens deste projeto](previas/vinculohub.jpg)

### Equipe do projeto V?nculoHub Portal

[Abrir imagem](vinculohub/06-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/home)

**Local sugerido:** Introdu??o.

**Coment?rio sugerido:** Apresenta o grupo respons?vel pela plataforma de conex?o entre organiza??es sociais e empresas.

### Arquitetura de infraestrutura do V?nculoHub Portal

[Abrir imagem](vinculohub/61-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Arquitetura-VinculoHub)

**Local sugerido:** Arquitetura.

**Coment?rio sugerido:** Explicar os servi?os da aplica??o e sua implanta??o em ambiente AWS, com cont?ineres, banco de dados e armazenamento.

### Modelo conceitual do banco de dados do V?nculoHub Portal

[Abrir imagem](vinculohub/62-Conceitual_4.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Banco-de-Dados)

**Local sugerido:** Banco de dados.

**Coment?rio sugerido:** A modelagem contextualiza as rela??es entre organiza??es, empresas, projetos e os demais elementos do neg?cio.

### Modelo l?gico do banco de dados do V?nculoHub Portal

[Abrir imagem](vinculohub/63-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Banco-de-Dados)

**Local sugerido:** Banco de dados ? alternativa.

**Coment?rio sugerido:** Selecionar o modelo que melhor ajude a explicar a atua??o do aluno; manter legibilidade dos nomes das tabelas na p?gina final.

### Prot?tipo do cadastro institucional de ONG

[Abrir imagem](vinculohub/67-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design)

**Local sugerido:** Prot?tipos / atividades.

**Coment?rio sugerido:** O fluxo de cadastro ajuda a explicar as depend?ncias entre dados institucionais, autentica??o e onboarding discutidas na Sprint 1.

### Prot?tipo do dashboard da ONG

[Abrir imagem](vinculohub/74-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design)

**Local sugerido:** Prot?tipos.

**Coment?rio sugerido:** O painel re?ne informa??es e a??es da organiza??o e permite contextualizar a experi?ncia dos usu?rios do perfil ONG.

### Prot?tipo do dashboard empresarial

[Abrir imagem](vinculohub/75-image.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design)

**Local sugerido:** Prot?tipos.

**Coment?rio sugerido:** O painel empresarial complementa o da ONG e evidencia os diferentes perfis contemplados pela plataforma.

## AGES IV ? ReadRace

[Ver todas as imagens deste projeto](previas/readrace.jpg)

### Equipe do projeto ReadRace

[Abrir imagem](readrace/05-WhatsApp_Image_2026-08-28_at_21.32.35.jpeg) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/home)

**Local sugerido:** Introdu??o.

**Coment?rio sugerido:** Apresenta o time do projeto; o nome do arquivo registra 28 de agosto de 2026, sem que isso comprove a data exata da captura.

### Arquitetura da aplica??o ReadRace

[Abrir imagem](readrace/32-diagrama-arquitetura-v2.drawio.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/arquitetura)

**Local sugerido:** Arquitetura.

**Coment?rio sugerido:** Relacionar o aplicativo, a API em camadas e as integra??es externas ? descri??o t?cnica do projeto.

### Arquitetura de implanta??o do ReadRace

[Abrir imagem](readrace/33-diagrama-deploy-v2.drawio.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/arquitetura)

**Local sugerido:** Arquitetura ? complemento.

**Coment?rio sugerido:** Explicar a organiza??o da implanta??o somente no n?vel necess?rio para contextualizar a experi?ncia, sem atribuir ao aluno a constru??o dessa infraestrutura.

### Modelo relacional do ReadRace

[Abrir imagem](readrace/34-Modelo_Relacional_ReadRace.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/banco-de-dados)

**Local sugerido:** Banco de dados.

**Coment?rio sugerido:** Relacionar o esquema ? revis?o de coer?ncia entre dados e user stories. O arquivo retrata a vers?o atual da wiki e n?o comprova a estrutura existente na Sprint 1.

### Biblioteca pessoal do ReadRace

[Abrir imagem](readrace/43-meus-livros.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design)

**Local sugerido:** Telas implementadas.

**Coment?rio sugerido:** A biblioteca organiza os livros do usu?rio e d? acesso ao registro de leitura. A wiki identifica esta captura como resultado do fim da Sprint 4.

### Tela de detalhe do livro no ReadRace

[Abrir imagem](readrace/44-livro-detalhe.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design)

**Local sugerido:** Telas implementadas.

**Coment?rio sugerido:** O detalhe re?ne informa??es da obra e o progresso do leitor. Relacionar ao trabalho relatado pelo aluno sem apresentar esta captura posterior como evid?ncia da Sprint 1.

### Registro de progresso de leitura no ReadRace

[Abrir imagem](readrace/45-registrar-progresso.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design)

**Local sugerido:** Telas implementadas.

**Coment?rio sugerido:** O registro de p?gina permite explicar a regra de c?lculo de XP e a preven??o de pontua??o repetida. Captura identificada pela wiki como sendo do fim da Sprint 4.

### Perfil do leitor no ReadRace

[Abrir imagem](readrace/56-perfil.png) ? [Fonte na wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design)

**Local sugerido:** Telas implementadas ? alternativa.

**Coment?rio sugerido:** O perfil re?ne n?vel e estat?sticas do leitor. Conferir a diferen?a entre perfil pr?prio e perfil de outro usu?rio antes de associar esta tela ? atividade individual.

## ?ndice de todos os arquivos

| Projeto | Arquivo | P?gina de origem |
|---|---|---|
| planline | [01-equipe.jpg](planline/01-equipe.jpg) | [Wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/home) |
| planline | [02-1694646530152-5492bb67-86cf-433d-a521-fe9c63be75dd_1.jpg](planline/02-1694646530152-5492bb67-86cf-433d-a521-fe9c63be75dd_1.jpg) | [Wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/home) |
| blockchain | [03-image.png](blockchain/03-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/home) |
| blockchain | [04-WhatsApp_Image_2024-03-15_at_9.19.05_PM.jpeg](blockchain/04-WhatsApp_Image_2024-03-15_at_9.19.05_PM.jpeg) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/home) |
| readrace | [05-WhatsApp_Image_2026-08-28_at_21.32.35.jpeg](readrace/05-WhatsApp_Image_2026-08-28_at_21.32.35.jpeg) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/home) |
| vinculohub | [06-image.png](vinculohub/06-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/home) |
| planline | [07-diagrama_de_deploy.png](planline/07-diagrama_de_deploy.png) | [Wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/arquitetura) |
| planline | [08-Modelagem_do_Banco_de_dados.drawio.svg](planline/08-Modelagem_do_Banco_de_dados.drawio.svg) | [Wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/banco_dados) |
| planline | [09-web.gif](planline/09-web.gif) | [Wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/mockups) |
| planline | [10-mobile.gif](planline/10-mobile.gif) | [Wiki](https://tools.ages.pucrs.br/planline/wiki/-/wikis/mockups) |
| blockchain | [11-diagrama-componentes.drawio__1_.png](blockchain/11-diagrama-componentes.drawio__1_.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/arquitetura) |
| blockchain | [12-AuthLink-arquitetura-overview.drawio.png](blockchain/12-AuthLink-arquitetura-overview.drawio.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/arquitetura) |
| blockchain | [13-image.png](blockchain/13-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Banco-de-Dados) |
| blockchain | [14-image.png](blockchain/14-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Banco-de-Dados) |
| blockchain | [15-image.png](blockchain/15-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Banco-de-Dados) |
| blockchain | [16-image.png](blockchain/16-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Banco-de-Dados) |
| blockchain | [17-cadastro-empresa.png](blockchain/17-cadastro-empresa.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [18-cadastro-empresa-adm.png](blockchain/18-cadastro-empresa-adm.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [19-cadastro-empresa-analise.png](blockchain/19-cadastro-empresa-analise.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [20-cadastro-funcionario.png](blockchain/20-cadastro-funcionario.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [21-remocao-funcionario.png](blockchain/21-remocao-funcionario.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [22-image.png](blockchain/22-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [23-consulta-certificado.png](blockchain/23-consulta-certificado.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [24-pesquisa-certificado.png](blockchain/24-pesquisa-certificado.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [25-revogacao-certificado.png](blockchain/25-revogacao-certificado.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [26-emissao-certificado.png](blockchain/26-emissao-certificado.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [27-emissao-certificado-confirmacao.png](blockchain/27-emissao-certificado-confirmacao.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [28-image.png](blockchain/28-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [29-image.png](blockchain/29-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [30-image.png](blockchain/30-image.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Design/Mockups) |
| blockchain | [31-Diagrama-de-deploy.drawio.png](blockchain/31-Diagrama-de-deploy.drawio.png) | [Wiki](https://tools.ages.pucrs.br/certifica-o-por-meio-de-blockchain/blockchain-wiki/-/wikis/Infraestrutura) |
| readrace | [32-diagrama-arquitetura-v2.drawio.png](readrace/32-diagrama-arquitetura-v2.drawio.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/arquitetura) |
| readrace | [33-diagrama-deploy-v2.drawio.png](readrace/33-diagrama-deploy-v2.drawio.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/arquitetura) |
| readrace | [34-Modelo_Relacional_ReadRace.png](readrace/34-Modelo_Relacional_ReadRace.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/banco-de-dados) |
| readrace | [35-entrada.png](readrace/35-entrada.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [36-entrar.png](readrace/36-entrar.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [37-criar-conta.png](readrace/37-criar-conta.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [38-feed-social.png](readrace/38-feed-social.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [39-feed-comunidades.png](readrace/39-feed-comunidades.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [40-comunidade.png](readrace/40-comunidade.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [41-comentarios.png](readrace/41-comentarios.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [42-criar-comunidade.png](readrace/42-criar-comunidade.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [43-meus-livros.png](readrace/43-meus-livros.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [44-livro-detalhe.png](readrace/44-livro-detalhe.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [45-registrar-progresso.png](readrace/45-registrar-progresso.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [46-buscar.png](readrace/46-buscar.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [47-pagina-clube.png](readrace/47-pagina-clube.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [48-ranking-clube.png](readrace/48-ranking-clube.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [49-forum-clube.png](readrace/49-forum-clube.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [50-chat-clube.png](readrace/50-chat-clube.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [51-quiz.png](readrace/51-quiz.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [52-solicitacoes-clube.png](readrace/52-solicitacoes-clube.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [53-desafios.png](readrace/53-desafios.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [54-desafios-amigos.png](readrace/54-desafios-amigos.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [55-desafiar-amigo.png](readrace/55-desafiar-amigo.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [56-perfil.png](readrace/56-perfil.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [57-conquistas.png](readrace/57-conquistas.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [58-mascotes.png](readrace/58-mascotes.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [59-configuracoes-perfil.png](readrace/59-configuracoes-perfil.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| readrace | [60-seguidores.png](readrace/60-seguidores.png) | [Wiki](https://tools.ages.pucrs.br/2026-2/6lmnp/readrace/readrace-wiki/-/wikis/design) |
| vinculohub | [61-image.png](vinculohub/61-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Arquitetura-VinculoHub) |
| vinculohub | [62-Conceitual_4.png](vinculohub/62-Conceitual_4.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Banco-de-Dados) |
| vinculohub | [63-image.png](vinculohub/63-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Banco-de-Dados) |
| vinculohub | [64-image.png](vinculohub/64-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [65-image.png](vinculohub/65-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [66-image.png](vinculohub/66-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [67-image.png](vinculohub/67-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [68-image.png](vinculohub/68-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [69-image.png](vinculohub/69-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [70-image.png](vinculohub/70-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [71-image.png](vinculohub/71-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [72-image.png](vinculohub/72-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [73-image.png](vinculohub/73-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [74-image.png](vinculohub/74-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
| vinculohub | [75-image.png](vinculohub/75-image.png) | [Wiki](https://tools.ages.pucrs.br/vinculo-hub/wiki/-/wikis/Design) |
