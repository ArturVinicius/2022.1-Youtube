# Casos de Uso

## 1. Introdução
<p align="justify">&emsp;&emsp;Caso de Uso é uma documentação acerca do comportamento do sistema em desenvolvimento, isto é, o que funcionalmente deve ser fornecido pelo sistema.(Andrey Pimentel, Projeto de Software Usando a UML, página 13).</p>

<p align="justify">&emsp;&emsp;A partir disso, podem ser criados modelos para ilustar/representar os casos de uso de um sistema.</p>

## 2. Composição de um Diagrama de Casos de Uso
<p align="justify">&emsp;&emsp;Um Diagrama de Casos de Uso compõe diversos elementos e relacionamentos. Dito isso, é importante entendê-los antes de criar ou até mesmo ver e analisar um diagrama desse tipo.</p>

### 2.1 Elementos
<p align="justify">&emsp;&emsp;Primeiramente, o diagrama tem 3 elementos gerais que o compõem: atores, casos de uso e sistema.</p>

#### 2.1.1 Atores
<p align="justify">&emsp;&emsp;Atores representam algo ou alguém que deve interagir com o sistema, sem fazer parte dele.</p>

<p align="justify">&emsp;&emsp;São representados por um homem palito, como representado na figura 1.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/stickman.png" width="128" height="128"/>

<figcaption>Figura 1: Homem Palito para representar Ator.</figcaption>

</center>

#### 2.1.2 Casos de Uso
<p align="justify">&emsp;&emsp;Casos de Uso representam a funcionalidade fornecida pelo sistema. Basicamente, é um diálogo entre um ator e o sistema.</p>

<p align="justify">&emsp;&emsp;São representados por uma figura oval, como representado na figura 2.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/usecase.png" width="128" height="128"/>

<figcaption>Figura 2: Figura oval para representar Caso de Uso.</figcaption>

</center>

#### 2.1.3 Sistema
<p align="justify">&emsp;&emsp;O sistema, ou limite de sistema, é a delimitação de atuação da aplicação em si.</p>

<p align="justify">&emsp;&emsp;É representado por uma figura retangular, como representado na figura 3.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/retangulo.png" width="128" height="128"/>

<figcaption>Figura 3: Figura retangular para representar Sistema.</figcaption>

</center>

### 2.2 Relacionamentos
<p align="justify">&emsp;&emsp;Relacionamentos podem ser estabelecidos entre atores e casos de uso e, basicamente, representam as interações que eles podem ter.</p>

#### 2.2.1 Include
<p align="justify">&emsp;&emsp;Relacionamentos include são aqueles que ocorrem sempre que o caso de uso base a que se refere for executado.</p>

<p align="justify">&emsp;&emsp;É representado por uma seta pontilhada direcionada ao caso de uso a ser executado após o base, como representado na figura 4.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/include.jfif" width="256" height="256"/>

<figcaption>Figura 4: Representação de Relacionamento Include.</figcaption>

</center>

#### 2.2.2 Extend
<p align="justify">&emsp;&emsp;Relacionamentos extend são aqueles que podem ocorrer quando o caso de uso base a que se refere for executado, não sendo obrigatoriamente sempre executado.</p>

<p align="justify">&emsp;&emsp;É representado por uma seta pontilhada direcionada para o caso de uso base executado, como representado na figura 5.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/extend.png" width="256" height="256"/>

<figcaption>Figura 5: Representação de Relacionamento Extend.</figcaption>

</center>

## 3. Metodologia
<p align="justify">&emsp;&emsp;A partir da listagem dos diagramas de caso de uso identificados, o grupo modelou-os e fez suas especificações com as seguintes informações:</p>

- **Descrição**: explicação da funcionalidade representada.
- **Ator**: quem performa a ação.
- **Pré-condições**: condições/requisitos necessários para a realização do caso de uso.
- **Fluxo Principal**: maneira que o ator acessará/utilizará a funcionalidade.
- **Pós-condição**: o que será resultado do caso de uso.

## 4. Diagramas de Caso de Uso

### 4.1 Diagrama 1 - Casos de Uso para o [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo)
A figura 1 apresenta o diagrama de casos de uso para um [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo)

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/casouso-criador.png"/>

<figcaption>Figura 1: Diagrama de Casos de Uso - Criador de Conteúdo. Autor: Paulo Henrique Almeida.</figcaption>

</center>

<div id="cu-11"></div>

#### 4.1.1 1UC01 - Caso de Uso 1 - Criar [Canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar [Canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Descrição      | O [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) cria um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), onde [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar)á e armazenará seus [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s/conteúdos |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- Clica na sua foto de perfil<br/>- Entra em "meu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)"<br/>- Preenche foto e nome do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)|
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) tem um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) criado|

<div id="cu-12"></div>

#### 4.1.2 1UC02 - Caso de Uso 2 - Autenticar [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Autenticar [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) autentica suas credenciais de [login](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#login) para poder ter acesso a mais ferramentas |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Pré-condições  | Ter uma conta Google |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em "Fazer [Login](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#login)"<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) se autentica com sua conta Google|
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) está no estado [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) e pode acessar ferramentas antes restritas|

<div id="cu-13"></div>

#### 4.1.3 1UC03 - Caso de Uso 3 - [Postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | [Postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |
| Descrição      | A funcionalidade de [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo), como, por exemplo, um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado<br/>- Ter um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) armazenado no computador para [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica no ícone "+" na área inferior<br/>- Seleciona o envio de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Coloca as informações do [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) (título, descrição e visibilidade)<br/>- Clica em "[postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar)" |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá um conteúdo [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) em seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |

<div id="cu-14"></div>

#### 4.1.4 1UC04 - Caso de Uso 4 - Criar [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)s
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)s |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) executa a ação de criar uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a tela de biblioteca<br/>- Seleciona a opção de "nova [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)"<br/>- Adiciona [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s à [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)<br/>- Informa o nome e [privacidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#privacidade) da [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)<br/>- Clica em "criar [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)" |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) associada a sua conta criada |

<div id="cu-15"></div>

#### 4.1.5 1UC05 - Caso de Uso 5 - Excluir [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Excluir [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) exclui um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado<br/>- Ter um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a aba de gerenciamento de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s<br/>- Abre o menu de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) representado por um ícone de "3 pontos verticais"<br/>- Seleciona o botão de excluir<br/>- Confirma a remoção do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá seu conteúdo antes [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado), agora deletado |

<div id="cu-16"></div>

#### 4.1.6 1UC06 - Caso de Uso 6 - Ver estatísticas do [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Ver estatísticas do [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) tem a funcionalidade de ver as estatísticas e dados de um conteúdo postsado |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado<br/>- Ter um conteúdo [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a tela de seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a aba de estatísticas |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá acesso às estatísticas de seus conteúdos [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s |

<div id="cu-17"></div>

#### 4.1.7 1UC07 - Caso de Uso 7 - Editar informações do [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Editar informações do [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) executa a funcionalidade de alterar informações de um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) já [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado<br/>- Ter um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a aba de gerenciamento de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s<br/>- Abre o menu de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) representado por um ícone de "3 pontos verticais"<br/>- Seleciona o botão de editar<br/>- Faz as edições desejadas no [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)<br/>- Clica em "salvar" |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá as informações de um conteúdo já [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) alteradas |

<div id="cu-18"></div>

#### 4.1.8 1UC08 - Caso de Uso 8 - Adicionar [Thumbnail](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#thumbnail)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Adicionar [Thumbnail](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#thumbnail) |
| Descrição      | Um conteúdo pode ter uma [thumbnail](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#thumbnail) (imagem de apresentação do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)) adicionada a ele |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado<br/>- Ter um conteúdo [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a aba de gerenciamento de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s<br/>- Abre o menu de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) representado por um ícone de "3 pontos verticais"<br/>- Seleciona o botão de editar<br/>- Clica no ícone de adicionar imagem ao [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Clica em "salvar" |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá uma imagem inicial (thumbnail) relacionada a ele |

<div id="cu-19"></div>

#### 4.1.9 1UC09 - Caso de Uso 9 - Fazer transmissão ao vivo
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Fazer transmissão ao vivo |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) pode fazer uma transmissão ao vivo na plataforma |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica no ícone "+" na área inferior<br/>- Seleciona a opção de "transmissão ao vivo"<br/>- Coloca as informações da transmissão<br/>- Clica em "iniciar transmissão" |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) estará realizando uma transmissão ao vivo no seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)|

<div id="cu-110"></div>

#### 4.1.10 1UC10 - Caso de Uso 10 - [Postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [Shorts](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#shorts)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | [Postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [Shorts](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#shorts) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) pode [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) um tipo de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) de até 60 segundos e de forma vertical |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [Criador de Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica no ícone "+" na área inferior<br/>- Seleciona a opção de "criar um short"<br/>- Seleciona um clipe<br/>- Clica em "concluído"<br/>- Adiciona as informações do [shorts](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#shorts)<br/>- Clica em "[postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar)" |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) um [Shorts](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#shorts) [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) no seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |

### 4.2 Diagrama 2 - Casos de Uso para o [espectador](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#espectador)
A figura 2 apresenta o diagrama de casos de uso para um [espectador](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#espectador) ([usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) regular do sistema)

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Grupo-03/main/docs/media/casos-uso/casouso-espectador.png"/>

<figcaption>Figura 2: Diagrama de Casos de Uso - Espectador. Autor: Paulo Henrique Almeida.</figcaption>

</center>

<div id="cu-21"></div>

#### 4.2.1 2UC01 - Caso de Uso 1 - Criar [Canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar [Canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Descrição      | O [espectador](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#espectador) cria um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), onde poderá [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) e armazenar seus [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s/conteúdos |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- Clica na sua foto de perfil<br/>- Entra em "meu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)"<br/>- Preenche foto e nome do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) tem um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) criado |

<div id="cu-22"></div>

#### 4.2.2 2UC02 - Caso de Uso 2 - [Inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever) em [Canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | [Inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever) em [Canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Descrição      | O [espectador](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#espectador) se [inscreve](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever) em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), por onde poderá acompanhar/consumir os conteúdo que estão sendo [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- Clica no ícone/nome do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) que deseja se [inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever) <br/>- Clica em "[inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever)-se"<br/>|
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) está inscrito no [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |

<div id="cu-23"></div>

#### 4.2.3 1UC03 - Caso de Uso 3 - Autenticar [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Autenticar [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) autentica suas credenciais de [login](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#login) para poder ter acesso a mais ferramentas |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Pré-condições  | Ter uma conta Google |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em "Fazer [Login](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#login)"<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) se autentica com sua conta Google |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) está no estado [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) e pode acessar ferramentas antes restritas |

<div id="cu-24"></div>

#### 4.2.4 2UC04 - Caso de Uso 4 - Consumir [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Consumir [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) consome/assiste os [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s que estão [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s no sistema |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | Abrir o aplicativo |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em um card de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) consome o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) consimiu/assistiu um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |

<div id="cu-25"></div>

#### 4.2.5 2UC05 - Caso de Uso 5 - Pesquisar [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Pesquisar [Conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) pesquisa por um [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que foi [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s no sistema |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | Abrir o aplicativo |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica na ferramenta de pesquisa<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) digita título de [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que deseja consumir<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em buscar |
| Pós-condição   | O sistema disponibilzia ao [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) o [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) desejado/relacionado na pesquisa |

<div id="cu-26"></div>

#### 4.2.6 2UC06 - Caso de Uso 6 - Criar [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)s
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Criar [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)s |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) cria uma lista de [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s que deseja consumir |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a tela de biblioteca<br/>- Seleciona a opção de "nova [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)"<br/>- Adiciona [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s à [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)<br/>- Informa o nome e [privacidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#privacidade) da [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)<br/>- Clica em "criar [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)" |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) associada a sua conta criada |

<div id="cu-27"></div>

#### 4.2.7 2UC07 - Caso de Uso 7 - Avaliar
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Avaliar |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) avalia (positivamente ou negativamente) [conteúdos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo)/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s consumidos |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica no joinha para avaliar positivamente ou no joinha invertido para avaliar negativamente <br/> |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá avaliado um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |

<div id="cu-28"></div>

#### 4.2.8 2UC08 - Caso de Uso 8 - Comentar
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Comentar |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) comenta conteúdos/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s consumidos |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | - Estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado)/autenticado |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em comentários<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em "Adicione um comentário..."</br>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) digita um comentário e clica na seta à direita para [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) comentário |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá comentado um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |

<div id="cu-29"></div>

#### 4.2.9 2UC09 - Caso de Uso 9 - [Compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | [Compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) compartilha conteúdos/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s consumidos |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | - Estar com um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberto |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em [compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a forma que deseja [compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)</br>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) possuirá o link do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ou terá compartilhado o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) em alguma rede social |
| Pós-condição   | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) terá compartilhado um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |

<div id="cu-210"></div>

#### 4.2.10 2UC10 - Caso de Uso 10 - Alterar [velocidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) e [Qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Alterar [velocidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) e [Qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) poderá alterar a [velocidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video), deixando-o mais lento ou mais rápido, e também poderá alterar a [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) deixando-o com menor ou maior resolução |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | - Estar com um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberto |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica nos três pontinhos no canto superior direito do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em "[Velocidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) de reprodução" ou "[Qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade)"</br>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a [velocidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) de reprodução ou [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) desejada |
| Pós-condição   | O [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberto estará na [Velocidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) de reprodução ou [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) desejada |

<div id="cu-211"></div>

#### 4.2.11 2UC11 - Caso de Uso 11 - Ver [legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda)
| Informação     | Descrição |
| :--------:     | :-------  |
| Nome           | Ver [legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda) |
| Descrição      | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) poderá consumir o conteúdo/[vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) com [legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda) |
| Ator           | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) Espectador |
| Pré-condições  | - Estar com um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberto |
| Fluxo Principal| - [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre o aplicativo<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica nos três pontinhos no canto superior direito do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) clica em "[Legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda)"</br>- [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona o idioma de [legenda](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda) desejado |
| Pós-condição   | O [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberto estará legendado no idioma escolhido |

## 5. Referências

> - Andrey Pimentel, Projeto de Software Usando a UML. Julho de 2007.

## 6. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2022 | Criação da primeira versão do documento com a introdução e composição de um diagrama de caso de uso. | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.1    | 19/07/2022 | Adição do diagrama e das descrições dos casos de uso para um <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario" target="_blank">usuário</a> <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario" target="_blank">criador de conteúdo</a>. | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a>, <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/B3holder2" target="_blank">@B3holder2</a> |
| 1.2    | 19/07/2022 | Adição do diagrama e das descrições dos casos de uso para um <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario" target="_blank">usuário</a> <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#espectador" target="_blank">espectador</a>. | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a>, <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> |
| 1.3    | 24/07/2022 | Adição de links dos githubs no <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico" target="_blank">histórico</a> de versões | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | 
| 1.4    | 24/07/2022 | Referência de links dos léxicos encontrados na página | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.5    | 25/07/2022 | Correção dos links dos githubs no <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico" target="_blank">histórico</a> de versões | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | 
| 1.6    | 08/03/2022 | Imagens das legendas em português | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.7    | 12/09/2022 | Adição dos ids de caso de uso | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | 
