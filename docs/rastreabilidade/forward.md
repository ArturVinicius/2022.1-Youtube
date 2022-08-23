# Forward-From

## 1. Introdução
<p align="justify">&emsp;&emsp; O rastreamento de requisitos é um método de fornecer ligação e relacionamentos entre requisitos elicitados e entender suas dependências e origens. É considerado um fator de garantia de qualidade no processo de desenvolvimento de projetos.</p>

<p align="justify">&emsp;&emsp; A estratégia Forward-From (para frente), em específico, conecta os requisitos traçados às suas fontes.</p>

## 2. Metodologia
<p align="justify">&emsp;&emsp; A partir dos <a href="https://requisitos-de-software.github.io/2022.1-Youtube/elicitacao/resultado/" target="_blank">requisitos já obtidos e elicitados</a> disponíveis na página de resultados da elicitação relacionamos, à partir do documento de <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/agil/backlog/" target="_blank">Backlog e Histórias de Usuário</a> relacionamos cada um dos requisitos encontrados aos épicos, features e histórias de usuário. Relacionaremos também aos <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/cenarios/" target="_blank">cenários</a> e aos <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/casouso/" target="_blank">casos de uso</a></p>

<p align="justify">&emsp;&emsp; O aplicativo escolhido pela equipe não é um Open-Source Software, logo não tivemos acesso ao código fonte, então só foi possível relacionar os requisitos às funcionalidades já implementadas.</p>

## 2.1 Legendas 

>- RFXX: Requisito Funcional
>- RNFXX: Requisito Não Funcional
>- EPCXX: Épico
>- FTRXX: Feature
>- USXX: Histórias de Usuário
>- CNXX: Cenário
>- XUCXX: Número do diagrama seguido do Caso de Uso

## 3. Requisitos Funcionais
| ID | Requisito | Épico | Feature | Histórias de Usuário | Cenário | Casos de Uso |
| -- | --------- | ----- | ------- | -------------------- |---------|--------------|
| RF01 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video). | EPC02 | FTR04 | US10 | CN22 | 1UC03 |
| RF02 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder [assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video). | EPC03 | FTR05 | US15 | CN01 | 2UC04 |
| RF03 | O [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) deve poder editar o título do próprio [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video). | - | - | - | CN25 | 1UC07 |
| RF04 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de comentar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video). | EPC03 | FTR05 | US16 | CN03 | 2UC08 |
| RF05 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de avaliar ([curtir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#curtir) ou não) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video). | EPC03 | FTR05 | US17 | CN02 | 2UC07 |
| RF06 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de [compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video). | EPC03 | FTR05 | US18 | CN05 | 2UC08 |
| RF07 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder criar um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal). | EPC02 | FTR03 | US06 | CN06 | 1UC04 |
| RF08 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder criar uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist). | EPC03 | FTR07 | US25 | - | 1UC01 |
| RF09 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de excluir um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal). | EPC02 | FTR03 | US08 | - | - |
| RF10 | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder excluir uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist). | EPC03 | FTR07 | US26 | - | - |

## 4. Requisitos Não-Funcionais
| ID | Requisito | Épico | Feature | Histórias de Usuário | Cenário | Casos de Uso |
| -- | --------- | ----- | ------- | -------------------- |---------|--------------|
|  |  |  |  |  |  |  |

## 5. Referências
>- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. Acesso em: 20 de ago. de 2022. Disponível em: Aprender3. 
>- SAYÃO, Mirian; LEITE, J. C. S. P. . Acesso em: 17 de jul. de 2022. Acesso em: 20 de ago. de 2022. Disponível em : Aprender3.
>- Jama Software, What is Traceability? Why Does It Matter for Product Teams?. Disponível em: https://www.jamasoftware.com/requirements-management-guide/requirements-traceability/what-is-traceability-and-why-does-it-matter-for-product-teams#:~:text=Forward%20from%20requirements%20traces%20relationships,satisfied%20but%20verified%20and%20validated. Acesso em: 23 de ago. de 2022.
## 6. Histórico de Versão 
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
1.0 | 23/08/2022 | Criação da primeira versão com introdução, metodologia e referências da técnica forward-from dos requisitos elicitados | <a href="https://github.com/victorleaoo" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |