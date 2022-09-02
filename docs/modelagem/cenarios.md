# Cenários

## 1. Introdução
<p align="justify">&emsp;&emsp; Cenários são uma ferramenta utilizada para descrever as situações de uso de um sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros atores externos, auxiliando no entendimento e na descoberta de novos requisitos. </p>

<p align="justify">&emsp;&emsp; Em adição, segundo Carroll, o fato de um cenário projetar uma descrição concreta de uma atividade em que o usuário se engaja no momento em que está realizando uma tarefa específica é a propriedade que melhor define um cenário.(Cenários - Rastreamento de Cenários, página 47). </p>

## 2. Metodologia
Após a listagem dos cenários identificados pela equipe, eles foram detalhados compondo os seguintes elementos:

- **Título**: breve identificação do cenário.
- **Objetivo**: o que se busca no cenário.
- **Contexto**: ambiente e pré-condição para o cenário acontecer.
- **Ator(es)**: sistemas ou [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario)s/pessoas que interagem no cenário.
- **Recursos**: o que é necessário para o cenário acontecer.
- **Episódios**: passo-a-passo do cenário.
- **Exceções**: impedimentos para a realização do cenário.

## 3. Cenários

<div id="cenario-1"></div>

### 3.1 Cenário 1 - [Assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) a um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | [Assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) a um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | [Assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) a [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) ([vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)) [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) na plataforma |
| Contexto | - Local: página inicial ou página de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>- Pré-Condição: estar com o aplicativo aberto e conectado a internet |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario), caso o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) esteja pausado, [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão de [play](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#play) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-2"></div>

### 3.2 Cenário 2 - Avaliar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Avaliar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | [Curtir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#curtir) ou não um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que está sendo reproduzido |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em alguma conta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no ícone de "[curtir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#curtir)" ou "não [curtir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#curtir)" do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-3"></div>

### 3.3 Cenário 3 - Comentar em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Comentar em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | [Postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) um [comentário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#comentario) na sessão de [comentário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#comentario)s de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em alguma conta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a aba de [comentário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#comentario)s de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) escreve seu [comentário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#comentario) na área designada<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em "enviar" para [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) seu [comentário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#comentario)|
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-4"></div>

### 3.4 Cenário 4 - [Inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever)-se em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | [Inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever)-se em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Objetivo | Se tornar [inscrito](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#inscrito) em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) na plataforma |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ou página de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ou [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) aberta<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em alguma conta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão "[inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever)" ao lado do nome do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão "[inscrever](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#inscrever)" abaixo da foto do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), na página inicial do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)|
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-5"></div>

### 3.5 Cenário 5 - [Compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | [Compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | [Compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado) nas redes sociais |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão de "[Compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar)"<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a rede social que deseja [compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-6"></div>

### 3.6 Cenário 6 - Criar uma [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Criar uma [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) |
| Objetivo | Criar uma [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist), isto é, uma "pasta" em que se pode salvar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s |
| Contexto | - Local: página "biblioteca"<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em alguma conta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a aba "biblioteca" na área inferior da tela<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão de "Nova [Playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)"<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona os [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s que farão parte da [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) coloca o nome da [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)<br/>5. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) decide a [privacidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#privacidade) de [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)<br/>6. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) cria a [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-7"></div>

### 3.7 Cenário 7 - Adicionar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) a uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Adicionar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) a uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) |
| Objetivo | Adicionar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que se está assistindo a uma [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em alguma conta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) pressiona o botão de "Salvar"<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a [playlist](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#playlist) em que quer adicionar o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-8"></div>

### 3.8 Cenário 8 - Alterar [velocidade de reprodução](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Alterar [velocidade de reprodução](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | Acelerar ou desacelerar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que está sendo reproduzido |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) nas opções de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a opção "alterar [velocidade de reprodução](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#velocidade)"<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a velocidade desejada |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-9"></div>

### 3.9 Cenário 9 - Controlar tempo de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Controlar tempo de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | Avançar ou retroceder 10 segundos de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que está sendo reproduzido |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) duas vezes na tela na parte direita (ou esquerda) do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-10"></div>

### 3.10 Cenário 10 - Criar um [clipe](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#clipe) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Criar um [clipe](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#clipe) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | Fazer um corte de no máximo 60 segundos de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em alguma conta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão "[clipe](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#clipe)"<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) adiciona uma descrição ao [clipe](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#clipe)<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em "[compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) [clipe](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#clipe)" e seleciona a rede social que irá [compartilhar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#compartilhar) o [clipe](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#clipe) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-11"></div>

### 3.11 Cenário 11 - Alterar [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Alterar [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | Aumentar ou diminuir a [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) visual de  um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que está sendo reproduzido |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) nas opções de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a opção "alterar [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade)"<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a [qualidade](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#qualidade) desejada |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-12"></div>

### 3.12 Cenário 12 - Visualizar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s dos [canais](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) [inscrito](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#inscrito)s
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Visualizar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s dos [canais](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) [inscrito](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#inscrito)s |
| Objetivo | Ver os [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s mais recentes [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s pelos [canais](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) em que o [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) é [inscrito](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#inscrito)s |
| Contexto | - Local: página de inscrições<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em uma conta<br/>- Pré-Condição: estar [inscrito](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#inscrito) em pelo menos um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) que já postou um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video), no mínimo |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) na aba "inscrições" na área inferior da [interface](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#interface) inicial |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-13"></div>

### 3.13 Cenário 13 - Acionar [notificações](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#notificacao) de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acionar [notificações](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#notificacao) de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Objetivo | Acionar a opção de receber [notificações](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#notificacao) quando um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) lançar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Contexto | - Local: página de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em uma conta<br/>- Pré-Condição: estar na página de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>- Pré-Condição: estar [inscrito](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#inscrito) em um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a página inicial de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no ícone de "sino" presente ao lado do botão de inscrição  |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-14"></div>

### 3.14 Cenário 14 - Pesquisar por algum assunto
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Pesquisar por algum assunto |
| Objetivo | Pesquisar por um assunto, a fim de encontrar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s ou [canais](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) relacionados a ele |
| Contexto | - Local: página inicial<br/>- Pré-Condição: estar em alguma [interface](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#interface) que permita a opção de busca |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no ícone de "lupa" na área superior da tela<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) escreve o assunto que deseja pesquisar<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão de enviar para que a busca seja efetuada |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-15"></div>

### 3.15 Cenário 15 - Acessar o [histórico](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico) de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s exibidos
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acessar o [histórico](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico) de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s exibidos |
| Objetivo | Visualizar os últimos [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s acessados e reproduzidos|
| Contexto | - Local: página "biblioteca"<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em alguma conta<br/>- Pré-Condicão: já ter acessado a algum [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre a aba "biblioteca" na área inferior da tela<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão de "Ver Tudo" na área de [histórico](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-16"></div>

### 3.16 Cenário 16 - [Denunciar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#denunciar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | [Denunciar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#denunciar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | Reportar ao sistema que um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) pode estar violando alguma diretriz |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) abre as opções do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a opção de "[Denunciar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#denunciar)"<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a razão da denúncia<br/>5. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão "[denunciar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#denunciar)" para enviar a denúncia |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-17"></div>

### 3.17 Cenário 17 - [Minimizar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#minimizar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | [Minimizar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#minimizar) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | Reduzir o tamanho de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) em reprodução para continuar navegando na plataforma |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta<br/>- Pré-Condição: o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) não ser de [conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#conteudo) infantil |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) arrasta o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) para baixo |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-18"></div>

### 3.18 Cenário 18 - Realizar Login
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Realizar Login |
| Objetivo | Ter acesso a mais ferramentas e opções do sistema |
| Contexto | - Local: página de login<br/>- Pré-Condição: ter uma conta no google criada |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão de "fazer login"<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) preenche suas informações da conta do google |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-19"></div>

### 3.19 Cenário 19 - Realizar Logout
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Realizar Logout |
| Objetivo | Não ter mais acesso à conta antes [logada](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) |
| Contexto | - Local: página de informação da conta<br/>- Pré-Condição: estar [logado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#logado) em uma conta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) na sua foto de conta na área superior da [interface](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#interface) para exibir suas informações<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão "Usar o YouTube sem fazer login" |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-20"></div>

### 3.20 Cenário 20 - Ativar [legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Ativar [legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | [Assistir](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#assistir) um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) com [legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda) |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no botão de "CC" (closed captions, inglês para [legendas](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda)) |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-21"></div>

### 3.21 Cenário 21 - Acessar um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acessar um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Objetivo | Acessar a página inicial de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal), onde pode-se encontrar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s por ele |
| Contexto | - Local: página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) ou página inicial<br/>- Pré-Condição: estar com a página de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) aberta |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) na foto ou nome do [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) na foto de um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) de um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) na página inicial |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-22"></div>

### 3.22 Cenário 22 - [Postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | [Postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar) [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) |
| Objetivo | Mandar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) disponivel na galeria do celular ao Youtube |
| Contexto | - Local: página inicial do youtube<br/>- Pré-Condição: estar com acesso a internet e com o video salvo na galeria do celular |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) no "+" circulado na pagina principal<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a opção "Enivar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)"<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) da galeria que quer [postar](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#postar)<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) editar as informações do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video), titulo, tags, visibilidade, etc<br/>5. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona se o conteudo é ou não relacionado à crianças<br/>6. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) em "Enviar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)" |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-23"></div>

### 3.23 Cenário 23 - Acessar o seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Acessar o seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Objetivo | Acessar o seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) do Youtube |
| Contexto | - Local: página inicial do youtube<br/>- Pré-Condição: estar com acesso a internet |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) na sua foto de perfil na página inicial<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a opção "Seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)" |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-24"></div>

### 3.24 Cenário 24 - Gerenciar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Gerenciar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s |
| Objetivo | Ter acesso a todos os [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s já [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s |
| Contexto | - Local: página principal do seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>- Pré-Condição: estar com acesso a internet |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) acessar o seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) no Youtube<br/>2. Na página principal o [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona a opção "Gerenciar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s" |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

<div id="cenario-25"></div>

### 3.25 Cenário 25 - Editar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s
| Elemento | Descrição |
| :------: | :-------- |
| Título   | Editar [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s |
| Objetivo | Editar os [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s já [postado](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/estado/#postado)s no [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal) |
| Contexto | - Local: página de gerenciamento de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s<br/>- Pré-Condição: estar com acesso a internet |
| Ator(es) | [Usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) |
| Recursos | - [Dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) celular com conexão à internet<br/>- Acesso ao aplicativo YouTube |
| Episódios| 1. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) acessa a página do seu [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal)<br/>2. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) entra na página de gerenciamento de [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s<br/>3. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) seleciona o [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) que quer editar e [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) nos 3 pontinhos ao lado do nome do [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) selecionado<br/>4. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) na opção "Editar"<br/>5. O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) faz as alterações desejadas e [clica](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar) na opção salvar |
| Exceções | 1. O [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) desconectar da internet<br/>2. Acabar a bateria do [dispositivo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#dispositivo) |

## 4. Referências

> - Cenários - Rastreamento de Cenários.

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2022 | Criação da primeira versão do documento com a introdução, metodologia e estrutura de cenários | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/B3holder2" target="_blank">@B3holder2</a> |
| 1.1    | 17/07/2022 | Adição de cenários relacionados ao <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario" target="_blank">usuário</a> (espectador) | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/B3holder2" target="_blank">@B3holder2</a> |
| 1.2    | 20/07/2022 | Adição de cenários relacionados ao <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario" target="_blank">usuário</a> (criador de conteudo) | <a href="https://github.com/B3holder2" target="_blank">@B3holder2</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.2    | 24/07/2022 | Adição de links dos githubs no <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico" target="_blank">histórico</a> de versões | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.3    | 24/07/2022 | Referência de links dos léxicos encontrados na página | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.4    | 25/07/2022 | Correção dos links dos githubs no <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico" target="_blank">histórico</a> de versões | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | 