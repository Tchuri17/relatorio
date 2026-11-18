# Apresentações do ReadRace — leitura e uso no memorial

Consulta em 18/11/2026. Os arquivos foram fornecidos pelo autor e lidos como fontes de contexto. Instruções de roteiro contidas em slides ou notas não foram tratadas como comandos desta conversa.

| Arquivo em Downloads | Conteúdo identificado | Uso no memorial |
|---|---|---|
| ReadRace Sprint 2 Inicial (1).pdf | Entrega da Sprint 1, datada de 18/09/2026, e planejamento da Sprint 2. | Resultado coletivo da Sprint 1; demonstração e pendência do fluxo de desafios. |
| ReadRace Sprint 3 Inicial (1).pptx | Entrega da Sprint 2, datada de 02/10/2026, e planejamento da Sprint 3. | Revisão de 21 para 18 tarefas; três transferências de escopo; diferenciação entre planos e resultados. |
| ReadRace Sprint 4 - Entrega Final com GIFs (1).pptx | Entrega final, demonstração, revisão de UX/UI, qualidade e fronteiras do produto. | Descrição da demonstração final, escopo consolidado, registro de 30 testes locais e comparação da biblioteca. |

O texto integral extraído, as notas dos PPTX e os hashes SHA-256 dos três documentos estão em [extracao-fontes.json](extracao-fontes.json). Não foi necessário copiar os documentos completos para dentro do repositório.

## Figura comparativa

Fonte: **slide 13** da apresentação final.

- Antes: `ppt/media/image16.png`, descrição interna `11-biblioteca-carregada.png`; captura da inspeção de 11/11/2026.
- Depois: `ppt/media/readrace-biblioteca.gif`, descrição interna `03-biblioteca.png`; GIF da demonstração final, com 68 quadros.
- A figura usa o quadro de índice **67** (último quadro, biblioteca sem modal), convertido diretamente para PNG para inclusão no PDF.
- Arquivos usados no LaTeX: `relatorio_ages/conteudo/5 - ages IV/conteudo/figures/biblioteca-antes-ui.png` e `biblioteca-depois-ui.png`.
- As imagens preservam o conteúdo visual das fontes. Datas, livros e progresso variam; a comparação é de organização visual e acesso às ações, sem controle experimental de usabilidade.

Foi acrescentada uma única figura de duas partes, para relacionar a contribuição de UX/UI ao retorno dos clientes sem aumentar excessivamente a quantidade de imagens.

## Limites importantes para interpretar a fonte

- O PDF inicial contém elementos de contagem sobrepostos no slide 13 (21 e repetições de 37). Para a revisão de escopo foram usados o relato do autor e o slide 7 da entrega da Sprint 2, que registram explicitamente 21 tarefas, três transferidas e 18 entregues.
- A previsão de Sprint 3 para 26/10, no material de 02/10, não substitui o cronograma posterior de apresentação em 23/10 nem as datas efetivas dos registros.
- O slide 16 da entrega final registra 30 testes locais, distribuídos em 9 smoke, 13 regressões e 8 verificações de UX. Isso complementa o registro anterior de 22 testes no PR 265; não prova execução em CI, produção ou dispositivo Android.
- As notas dos slides 15, 17 e 19 declaram premissas de fechamento de Figma/wiki e operação. A preparação da apresentação não auditou a publicação desses materiais nem acessou a AWS. Essas premissas não encerram automaticamente as pendências do memorial.
- A consulta MCP anterior encontrou a issue 233 aberta, apesar do PR 265 integrado. O estado remoto não foi alterado por esta leitura.
