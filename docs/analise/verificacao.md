# Verificação

## 1. Introdução
<p align="justify">&emsp;&emsp;A verificação é uma etapa do processo que busca garantir que os produtos de trabalho selecionados cumpram os seus requisitos especificados. Durante o desenvolvimento de um software, basicamente qualquer documento ou artefato pode ser verificado.</p>

<p align="justify">&emsp;&emsp;Normalmente, busca-se responder as seguintes perguntas: tem algo errado no nosso modelo em termos de notação, processo e/ou procedimentos? O modelo está de acordo com o que se espera dele? Sendo assim, normalmente, a verificação é um processo que só interessa aos engenheiros de software, sem a necessidade de envolver o cliente.</p>

## 2. Metodologia

### 2.1 Inspeção
<p align="justify">&emsp;&emsp;Há diversas formas de se realizar uma verificação, porém, o grupo seguiu a de Inspeção.</p>

<p align="justify">&emsp;&emsp;Basicamente, na Inspeção, são feitos checklists que buscam encontrar defeitos nos documentos desenvolvidos. Os itens de cada um dos checklists estão de acordo com o que esperaria do artefato e sua notação em si.</p>

### 2.2 Fagan

<p align="justify">&emsp;&emsp;A equipe seguiu os seis passos de Fagan para um método de inspeção:</p>

- Planejamento: definir os artefatos a serem inspecionados em quem faria a inspeção de qual;
- Visão geral: entendimento de cada um dos documentos;
- Planejamento: criação dos checklists a partir do que foi levantado como necessário;
- Correção: após analisar os resultados, uma correção foi feita para cada um dos artefatos;
- Acompanhamento: com o fim de inspeção, é possível continuar o acompanhamento de cada um dos artefatos. 

#### 2.3 Planejamento
| Artefato | Criador do Checklist | Inspetor |
| :------: | :------------------: | :-----------: |
| Rich Picture              | Paulo  | Carlos |
| Personas                  | Victor | Carlos |
| Perfil de Usuário         | Felipe | Victor |
| Brainstorm                | Victor | Pedro  |
| Introspecção              | Victor | Pedro  |
| Observação                | Victor | Pedro  |
| Entrevista                | Victor | Pedro  |
| MoSCoW                    | Felipe | Lucas  |
| 100 Dólares               | Carlos | Lucas  |
| Resultado Elicitação      | Pedro  | Lucas  |
| Cenários                  | Pedro  | Felipe |
| Léxicos                   | Lucas  | Felipe |
| Casos de Uso              | Paulo  | Felipe |
| Especificação Suplementar | Lucas  | Victor |
| NFR Framework             | Victor | Paulo  |
| Backlog + Histórias       | Pedro  | Victor |
| Validação                 | Carlos | Paulo  |
| Backward-From             | Victor | Felipe |
| Forward-From              | Victor | Lucas  |

## 3. Inspeção

### 3.1 Legenda
<p align="justify">&emsp;&emsp;Para cada item de cada um dos checklists, foram escritos "Sim" caso o item se encontrasse presente no artefato e "Não" caso contrário.</p>

### 3.2 Rich Picture
| Item        | Inspeção |
| :-------    | :------: | 
| Há legenda? | Sim |
| O ator principal está do lado direito? | Sim |
| Todos os elementos estão presentes? (atores, delimitação de sistema, operações, setas, bancos de dados) | Sim |
| O(s) ator(es) está fora da fronteira do sistema? | Sim |
| Os fluxos fazem sentido? | Sim |
| Há título? | Sim |

#### 3.2.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.3 Personas
| Item | Inspeção |
| :-------    | :------: | 
| Há a descrição se a persona é primária, secundária ou anti-persona para todas as personas? | Não |
| As personas possuem identidade? (Foto e Nome) | Sim |
| Foi feita uma descrição (objetivos, tarefas, ambiente, expectativas) acerca de cada uma das personas? | Sim |
| Todas as personas são condizentes com pessoas? | Sim |
| As imagens encontradas são de pessoas não existentes? | Sim |

#### 3.3.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Um item do checklist não foi atendido, o que resultou em uma taxa de 80% de satisfação nesse artefato.</p>

<p align="justify">&emsp;&emsp;Com isso, o problema encontrado foi corrigido ao aidicionar o tipo da persona (primária, secundária ou anti-persona) a cada uma delas presentes no documento.</p>

### 3.4 Perfil de Usuário
| Item | Inspeção |
| :-------    | :------: | 
| Os perfis de usuários estão separados entre espectador e criador de conteúdo? | Sim |
| Os perfis de usuários possuem experiência, nível de alfabetização e faixa etária? | Sim |

#### 3.4.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.5 Brainstorm
| Item | Inspeção |
| :-------    | :------: | 
| Há uma lista de todos os participantes da reunião? | Sim |
| Os requisitos estão bem escritos e claros? | Sim |
| Todos os léxicos estão linkados? | Sim |
| Há um registro de horário e dia da reunião? | Sim |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | Sim |
| Há a gravação da reunião? | Não |
| Todos os requisitos possuem um ID? | Sim |

#### 3.5.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Um item do checklist não foi atendido, o que resultou em uma taxa de 85% de satisfação nesse artefato.</p>

<p align="justify">&emsp;&emsp;O problema encontrado ainda não foi corrigido, uma vez que a equipe não gravou a reunião.</p>

### 3.6 Introspecção
| Item | Inspeção |
| :-------    | :------: | 
| Os requisitos estão bem escritos e claros? | Sim |
| Todos os léxicos estão linkados? | Sim |
| Todos os requisitos possuem um ID? | Sim |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | Sim |
| Foi explicitado os participantes da instrospecção? | Sim |

#### 3.6.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.7 Observação
| Item | Inspeção |
| :-------    | :------: | 
| O usuário participante da observação foi identificado? | Sim |
| Há um vídeo da tela do aplicativo da observação feita? | Sim |
| Os requisitos estão bem escritos e claros? | Sim |
| Todos os léxicos estão linkados? | Sim |
| Todos os requisitos possuem um ID? | Sim |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | Sim |

#### 3.7.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.8 Entrevista
| Item | Inspeção |
| :-------    | :------: | 
| O usuário participante da entrevista foi identificado? | Não |
| Há uma gravação da entrevista realizada com o usuário? | Sim |
| Há uma explicação de como a entrevista foi feita e as perguntas antes designadas? | Sim |
| Os requisitos estão bem escritos e claros? | Sim |
| Todos os léxicos estão linkados? | Sim |
| Todos os requisitos possuem um ID? | Sim |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | Sim |

#### 3.8.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Um item do checklist não foi atendido, o que resultou em uma taxa de 85% de satisfação nesse artefato.</p>

<p align="justify">&emsp;&emsp;O problema encontrado foi corrigido, já que o usuário participante da entrevista já foi identificado no documento.</p>

### 3.9 MoSCoW
| Item | Inspeção |
| :-------    | :------: | 
| Todos os requisitos elicitados tiveram sua prioridade selecionada? | Sim|
| Há uma descrição de cada um dos tipos de prioridade? (Must, Should, Could e Would) |Sim|
| O usuário que fez parte da priorização foi identificado? | Não |

#### 3.9.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Um item do checklist não foi atendido, o que resultou em uma taxa de 67% de satisfação nesse artefato.</p>

<p align="justify">&emsp;&emsp;O problema encontrado foi corrigido, já que o usuário participante da priorização já foi identificado no documento.</p>

### 3.10 100 Dólares
| Item | Inspeção |
| :-------    | :------: | 
| Todos os requisitos elicitados tiveram sua prioridade feita? |Sim |
| O usuário que fez parte da priorização foi identificado? | Não |
| A soma de todos os valores atribuídos é de 100? |Sim|

#### 3.10.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Um item do checklist não foi atendido, o que resultou em uma taxa de 67% de satisfação nesse artefato.</p>

<p align="justify">&emsp;&emsp;O problema encontrado foi corrigido, já que o usuário participante da priorização já foi identificado no documento.</p>

### 3.11 Resultado Elicitação
| Item | Inspeção |
| :-------    | :------: | 
| Todos os requisitos possuem uma identificação (ID)? | Sim |
| Cada um dos requisitos tem a técnica de elicitação em que eles foram encontrados? | Sim |
| Os requisitos estão bem escritos e claros? | Sim |
| Todos os léxicos estão linkados? | Sim |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | Sim |

#### 3.11.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.12 Cenários
| Item | Inspeção |
| :-------    | :------: | 
| Todos os cenários possuem títulos? | Sim |
| Todos os cenários possuem todos os elementos? (objetivo, contexto, atores, recursos, episódios e exceções) | Sim |
| O objetivo de todos os cenários é claro? | Sim |
| Os contextos foram bem definidos? (local e pré-condição) | Sim |
| Todos os recursos fazem sentido e são necessários? | Sim |
| A exceção é condizente com a realidade? | Sim |
| Os episódios são bem descritos? | Sim |
| Os cenários fazem sentido com os requisitos? | Sim |
| Todos os léxicos estão linkados? | Sim | 

#### 3.12.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.13 Léxicos
| Item | Inspeção |
| :-------    | :------: | 
| Os léxicos estão divididos entre estado, objeto e verbo? | Sim |
| Os nomes são condizentes? | Sim |
| Todos os léxicos possuem sinônimos corretos? | Sim |
| Todos os léxicos tem impactos relacionados a eles? | Sim |
| As noções de todos os léxicos fazem sentido com eles? | SIm |
| Todos os léxicos estão linkados entre si? | Sim | 

#### 3.13.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.14 Casos de Uso
| Item | Inspeção |
| :-------    | :------: | 
| Há uma legenda sobre cada um dos elementos usados? | Sim |
| Cada caso de uso presente no diagrama é descrito? | Sim |
| O ator principal está do lado esquerdo? | Sim | 
| O ator principal está fora do sistema? | Sim |
| As informações são suscintas? | Sim |
| Os verbos estão no infinitivo? | Sim |
| Os relacionamentos estão corretamente feitos? | Sim |
| Os casos de uso possuem títulos auto-explicativos? | Sim |
| Os casos de uso fazem sentido com os requisitos? | Sim |
| Os fluxos principais são completos? | Sim |
| Todos os léxicos estão linkados? | Sim | 

#### 3.14.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.15 Especificação Suplementar
| Item | Inspeção |
| :-------    | :------: | 
| Segue o FURPS+? | Sim |
| Há uma explicação acerca de cada uma das letras da sigla? | Sim |
| Cada uma das letras possuem pelo menos um requisito relacionado a elas? | Sim |
| Todos os requisitos são mensuráveis e avaliáveis? | Não |

#### 3.15.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Um item do checklist não foi atendido, o que resultou em uma taxa de 75% de satisfação nesse artefato.</p>

<p align="justify">&emsp;&emsp;O problema encontrado foi parcialmente corrigido. Os requisitos não mensuráveis e avaliáveis foram identificados como estimados pela equipe.</p>

### 3.16 NFR Framework
| Item | Inspeção |
| :-------    | :------: | 
| Todos os diagramas estão bem representados? | Sim |
| Os softgoals fazem sentido? | Sim |
| As decomposições são corretas? | Sim |
| Todas as propagações são condizentes com o contexto dos diagramas? | Sim |
| Há uma legenda para cada elemento usado nos diagramas? | Sim |
| Há um diagrama para cada tipo de requisito não-funcional encontrado na especificação suplementar? | Sim |

#### 3.16.1 Correção e Acompanhamento
<p align="justify">&emsp;&emsp;Todos os itens do checklist foram atendidos. Dessa forma, nenhuma correção foi necessária.</p>

### 3.17 Backlog do Produto + Histórias de Usuário
| Item | Inspeção |
| :-------    | :------: | 
| Os épicos fazem sentido? | Sim |
| Todas as features são condizentes com seus épicos? | Sim |
| Todos os itens possuem IDs? | Sim |
| Todas as histórias estão priorizadas? | Sim |
| Todas as histórias possuem critérios de aceitação? | Sim |
| Há gravação para a reunião de priorização? | Sim |
| As histórias seguem um padrão? (quem, o que, para que) | Sim |
| Todos os léxicos estão linkados? | Não | 

## 4. Referências

> - Gerência e Qualidade de Software - Aula 05 - Verificação e Validação, UNIVESP. Acesso em: 14 de agosto de 2022. Disponível em: https://www.youtube.com/watch?v=1Y-1zz6rZxo&t=22s
> - Milene Serrano, Requisitos - Aula 23. Acesso em: 14 de agosto de 2022. Disponível em: Aprender3.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 14/08/2022 | Início do documento com introdução, metodologia, checklists | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a>, <a href="https://github.com/CDGodoy" target="_blank">@CDGodoy</a> |
| 1.1    | 15/08/2022 | Correção do histórico de versão | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> |
| 1.2    | 15/08/2022 | Verificação os itens Rich Picture, Personas e Brainstorm e Caso de Uso | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> |
| 1.3    | 17/08/2022 | Verificação dos itens: Cenários e Léxicos | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> | <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |
| 1.4    | 17/08/2022 | Adição de verificação dos itens: especificação suplementar, nfr e backlog | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a>, <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |
| 1.5    | 17/08/2022 | Término da verificação | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a>, <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |