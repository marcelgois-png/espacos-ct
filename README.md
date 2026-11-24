# Espaços do CT

Portal dos espaços do Centro de Tecnologia da UFPB: blocos, salas, plantas por pavimento, setores, pessoas, aulas e demandas por espaço. Protótipo da Direção do CT, no padrão dos portais do CT.

Página: https://marcelgois-png.github.io/espacos-ct/

## O que mostra

- **Blocos**: o mapa do CT com cada bloco como um sólido, com o norte para cima e na escala real; a página de cada bloco traz a planta do térreo e dos andares desenhados, com as salas clicáveis.
- **Ambientes**: cada sala com tipo de espaço, setor, capacidade, área, onde fica na planta, quem ocupa e, nas salas de aula, a grade da semana pelo SIGAA.
- **Setores, Pessoas, Aulas, Demandas, Eventos** e a lista do que ainda está **a corrigir** no inventário.

## Fontes

- Inventário dos espaços físicos do CT (planilha da Direção, versão de 23/11/2026), na estrutura da planilha-modelo v2.
- Turmas do SIGAA de 2022.1 a 2026.2 (extração de 22/10/2026).
- Relatório de demandas por espaços físicos (10/11/2026).
- Planta "USOS E AMBIENTES" (AutoCAD, 09/04/2026), georreferenciada em 24/11/2026 (SIRGAS 2000, UTM 25S).

Os dados estão em revisão. Em caso de divergência, vale a informação do sistema oficial (SIGAA, SIPAC, SIGRH).

## Dados pessoais

Mostra nome, cargo, lotação e sala de trabalho de servidores do CT (informação funcional de servidor público) e os docentes das turmas, como no portal público do SIGAA. Não traz matrícula, CPF nem dados de alunos; estagiários e ocupantes desligados da unidade ficam de fora. A página pede aos buscadores que não a indexem.

## Arquivos

`index.html` (a página) e os dados que ela lê: `dados.json`, `turmas.json`, `mapa.json` (sólidos dos blocos) e `plantas.json` (paredes e salas por pavimento). Gerados pelos scripts guardados na pasta da Direção (01.01.01 Inventário Espacial › Banco de Espaços do CT - scripts).

Direção do Centro de Tecnologia · Universidade Federal da Paraíba
