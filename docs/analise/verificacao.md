# Verificação

## 1. Introdução
<p align="justify">&emsp;&emsp;A verificação é uma etapa do processo que busca garantir que os produtos de trabalho selecionados cumpram os seus requisitos especificados. Durante o desenvolvimento de um software, basicamente qualquer documento ou artefato pode ser verificado.</p>

<p align="justify">&emsp;&emsp;Normalmente, busca-se responder as seguintes perguntas: tem algo errado no nosso modelo em termos de notação, processo e/ou procedimentos? O modelo está de acordo com o que se espera dele? Sendo assim, normalmente, a verificação é um processo que só interessa aos engenheiros de software, sem a necessidade de envolver o cliente.</p>

## 2. Metodologia
<p align="justify">&emsp;&emsp;Há diversas formas de se realizar uma verificação, porém, o grupo seguiu a de Inspeção.</p>

<p align="justify">&emsp;&emsp;Basicamente, na Inspeção, são feitos checklists que buscam encontrar defeitos nos documentos desenvolvidos. Os itens de cada um dos checklists estão de acordo com o que esperaria do artefato e sua notação em si.</p>

<p align="justify">&emsp;&emsp;Seguindo os seis passos de Fagan para um método de inspeção, a equipe planejou os artefatos que seriam inspecionados, fez-se uma visão geral, juntamente com a preparação, de entendimento de cada um do que seria necessário colocar no checklist para cada parte do projeto. A partir disso, foi feita a inspeção (análise e anotação dos itens do checklist) e correção dos que estivesse errado. Com isso, pode-se fazer o acompanhamento do projeto.</p>

## 3. Inspeção

### 3.1 Legenda
<p align="justify">&emsp;&emsp;Para cada item de cada um dos checklists, foram escritos "Sim" caso o item se encontrasse presente no artefato e "Não" caso contrário.</p>

### 3.2 Rich Picture
| Item        | Inspeção |
| :-------    | :------: | 
| Há legenda? | |
| O ator principal está do lado direito? | |
| Todos os elementos estão presentes? (atores, delimitação de sistema, operações, setas, bancos de dados) | |
| O(s) ator(es) está fora da fronteira do sistema? | |
| Os fluxos fazem sentido? | |
| Há título? | Sim |

### 3.3 Personas
| Item | Inspeção |
| :-------    | :------: | 
| Há a descrição se a persona é primária, secundária ou anti-persona para todas as personas? | Não |
| As personas possuem identidade? (Foto e Nome) | |
| Foi feita uma descrição (objetivos, tarefas, ambiente, expectativas) acerca de cada uma das personas? | |
| Todas as personas são condizentes com pessoas? | |
| As imagens encontradas são de pessoas não existentes? | |

### 3.4 Perfil de Usuário
| Item | Inspeção |
| :-------    | :------: | 
| Os perfis de usuários estão separados entre espectador e criador de conteúdo? | Sim |
| Os perfis de usuários possuem experiência, nível de alfabetização e faixa etária? | |

### 3.5 Brainstorm
| Item | Inspeção |
| :-------    | :------: | 
| Há uma lista de todos os participantes da reunião? | |
| Os requisitos estão bem escritos e claros? | |
| Todos os léxicos estão linkados? | Sim |
| Há um registro de horário e dia da reunião? | |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | |
| Há a gravação da reunião? | Não |
| Todos os requisitos possuem um ID? | |

### 3.6 Introspecção
| Item | Inspeção |
| :-------    | :------: | 
| Os requisitos estão bem escritos e claros? | |
| Todos os léxicos estão linkados? | Sim |
| Todos os requisitos possuem um ID? | |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | |
| Foi explicitado os participantes da instrospecção? | |

### 3.7 Observação
| Item | Inspeção |
| :-------    | :------: | 
| O usuário participante da observação foi identificado? | |
| Há um vídeo da tela do aplicativo da observação feita? | Sim |
| Os requisitos estão bem escritos e claros? | |
| Todos os léxicos estão linkados? | |
| Todos os requisitos possuem um ID? | |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | Sim |

### 3.8 Entrevista
| Item | Inspeção |
| :-------    | :------: | 
| O usuário participante da entrevista foi identificado? | |
| Há uma gravação da entrevista realizada com o usuário? | Sim |
| Há uma explicação de como a entrevista foi feita e as perguntas antes designadas? | |
| Os requisitos estão bem escritos e claros? | |
| Todos os léxicos estão linkados? | Sim |
| Todos os requisitos possuem um ID? | |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | |

### 3.9 MoSCoW
| Item | Inspeção |
| :-------    | :------: | 
| Todos os requisitos elicitados tiveram sua prioridade selecionada? | |
| Há uma descrição de cada um dos tipos de prioridade? (Must, Should, Could e Would) | |
| O usuário que fez parte da priorização foi identificado? | Não |

### 3.10 100 Dólares
| Item | Inspeção |
| :-------    | :------: | 
| Todos os requisitos elicitados tiveram sua prioridade feita? | |
| O usuário que fez parte da priorização foi identificado? | Não |
| A soma de todos os valores atribuídos é de 100? | |

### 3.11 Resultado Elicitação
| Item | Inspeção |
| :-------    | :------: | 
| Todos os requisitos possuem uma identificação (ID)? | Sim |
| Cada um dos requisitos tem a técnica de elicitação em que eles foram encontrados? | |
| Os requisitos estão bem escritos e claros? | |
| Todos os léxicos estão linkados? | Sim |
| Há uma divisão entre os requisitos funcionais e os não-funcionais? | |

### 3.12 Cenários
| Item | Inspeção |
| :-------    | :------: | 
| Todos os cenários possuem títulos? | |
| Todos os cenários possuem todos os elementos? (objetivo, contexto, atores, recursos, episódios e exceções) | |
| O objetivo de todos os cenários é claro? | |
| Os contextos foram bem definidos? (local e pré-condição) | |
| Todos os recursos fazem sentido e são necessários? | |
| A exceção é condizente com a realidade? | |
| Os episódios são bem descritos? | |
| Os cenários fazem sentido com os requisitos? | |
| Todos os léxicos estão linkados? | Sim | 

### 3.13 Léxicos
| Item | Inspeção |
| :-------    | :------: | 
| Os léxicos estão divididos entre estado, objeto e verbo? | |
| Os nomes são condizentes? | |
| Todos os léxicos possuem sinônimos corretos? | |
| Todos os léxicos tem impactos relacionados a eles? | |
| As noções de todos os léxicos fazem sentido com eles? | |
| Todos os léxicos estão linkados entre si? | Sim | 

### 3.14 Casos de Uso
| Item | Inspeção |
| :-------    | :------: | 
| Há uma legenda sobre cada um dos elementos usados? | |
| Cada caso de uso presente no diagrama é descrito? | |
| O ator principal está do lado esquerdo? | Sim | 
| O ator principal está fora do sistema? | |
| As informações são suscintas? | |
| Os verbos estão no infinitivo? | |
| Os relacionamentos estão corretamente feitos? | |
| Os casos de uso possuem títulos auto-explicativos? | |
| Os casos de uso fazem sentido com os requisitos? | |
| Os fluxos principais são completos? | |
| Todos os léxicos estão linkados? | Sim | 

### 3.15 Especificação Suplementar
| Item | Inspeção |
| :-------    | :------: | 
| Segue o FURPS+? | |
| Há uma explicação acerca de cada uma das letras da sigla? | Sim |
| Cada uma das letras possuem pelo menos um requisito relacionado a elas? | |
| Todos os requisitos são mesuráveis e avaliáveis? | |

### 3.16 NFR Framework
| Item | Inspeção |
| :-------    | :------: | 
| Todos os diagramas estão bem representados? | |
| Os softgoals fazem sentido? | |
| As decomposições são corretas? | |
| Todas as propagações são condizentes com o contexto dos diagramas? | |
| Há uma legenda para cada elemento usado nos diagramas? | |
| Há um diagrama para cada tipo de requisito não-funcional encontrado na especificação suplementar? | Sim |

### 3.17 Backlog do Produto + Histórias de Usuário
| Item | Inspeção |
| :-------    | :------: | 
| Os épicos fazem sentido? | |
| Todas as features são condizentes com seus épicos? | |
| Todos os itens possuem IDs? | |
| Todas as histórias estão priorizadas? | |
| Todas as histórias possuem critérios de aceitação? | |
| Há gravação para a reunião de priorização? | Sim |
| As histórias seguem um padrão? (quem, o que, para que) | |
| Todos os léxicos estão linkados? | Não | 

## 4. Referências

> - Gerência e Qualidade de Software - Aula 05 - Verificação e Validação, UNIVESP. Acesso em: 14 de agosto de 2022. Disponível em: https://www.youtube.com/watch?v=1Y-1zz6rZxo&t=22s
> - Milene Serrano, Requisitos - Aula 23. Acesso em: 14 de agosto de 2022. Disponível em: Aprender3.

## 5. Histórico de Versão
| 1.0    | 14/08/2022 | Início do documento com introdução, metodologia, checklists | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a>, <a href="https://github.com/CDGodoy" target="_blank">@CDGodoy</a> |