# Validação

## 1. Introdução
<p align="justify">&emsp;&emsp;A validação de um software é o processo de confirmação de que o produto é aquele desejado pelo usuário. Em outras palavras, a validação tem o objetivo de demonstrar que o artefato cumpre a funcionalidade pretendida por ele.</p>

<p align="justify">&emsp;&emsp;Em geral, busca responder as seguintes perguntas: o artefato está correto? É o que o cliente esperava? Dessa forma, fica evidente que o usuário/cliente tem participação esperada nesse momento.</p>

## 2. Metodologia

### 2.1 Prototipação
<p align="justify">&emsp;&emsp;Entre as diversas formas de realizar a validação, a equipe utilizou, primariamente a prototipação.</p>

<p align="justify">&emsp;&emsp;Ao analisarmos todo o material desenvolvido encontramos as seguintes funcionalidades como ainda não implementadas no aplicativo:</p>

- RF09 - O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de excluir um [canal](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#canal).
- RF020 - O [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) deve ser capaz de adicionar [legenda](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#legenda) a um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video).
- RF026 - O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser capaz de enviar um superchat (comentário através de uma doação monetária).
- RF030 - O [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) deve ser capaz de ver as estatísticas de um vídeo postado.
- RF033 - O [criador de conteúdo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#criador-conteudo) deve ser capaz de ver a monetização de seus [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video)s.
- RF035 - O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve poder adicionar um [vídeo](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) à [fila de reprodução](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#fila).

<p align="justify">&emsp;&emsp;A partir destas, desenvolvemos protótipos que correspondem a essas funcionalidades.</p>

### 2.2 Comprovação Informal
<p align="justify">&emsp;&emsp;Outro tipo de validação feita foi a comprovação informal, em que uma mensagem foi enviada a equipe do YouTube, a fim de entender, com os criadores e desenvolvedores dos produtos, se nosso projeto está correto em relação ao aplicativo.</p>

## 3. Prototipação

<div id="excluir-canal"></div>

### 3.1 RF09 - O usuário deve ser capaz de excluir um canal.

<p align="justify">&emsp;&emsp;A figura 1 abaixo mostra a prototipação realizada acerca do requisito funcional com ID RF09: O usuário deve ser capaz de excluir um canal.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/rf09.png"/>

<figcaption>Figura 1: Prototipação da funcionalidade de excluir um canal. Autor: Victor Hugo Oliveira Leão</figcaption>

</center>

<div id="add-legenda"></div>

### 3.2 RF020 - O criador de conteúdo deve ser capaz de adicionar legenda a um vídeo.

<p align="justify">&emsp;&emsp;A figura 2 abaixo mostra a prototipação realizada acerca do requisito funcional com ID RF020: O criador de conteúdo deve ser capaz de adicionar legenda a um vídeo.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/rf020.png"/>

<figcaption>Figura 2: Prototipação da funcionalidade de adicionar legenda a um vídeo. Autor: Victor Hugo Oliveira Leão</figcaption>

</center>

<div id="superchat"></div>

### 3.3 RF026 - O usuário deve ser capaz de enviar um superchat (comentário através de uma doação monetária).

<p align="justify">&emsp;&emsp;A figura 3 abaixo mostra a prototipação realizada acerca do requisito funcional com ID RF026: O usuário deve ser capaz de enviar um superchat (comentário através de uma doação monetária).</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/rf026.png"/>

<figcaption>Figura 3: Prototipação da funcionalidade de enviar um Super Chat. Autor: Paulo Henrique Almeida</figcaption>

</center>

<div id="stats-video"></div>

### 3.4 RF030 - O criador de conteúdo deve ser capaz de ver as estatísticas de um vídeo postado.
<p align="justify">&emsp;&emsp;A figura 4 abaixo mostra a prototipação realizada acerca do requisito funcional com ID RF030: O criador de conteúdo deve ser capaz de ver as estatísticas de um vídeo postado.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/rf030.png"/>

<figcaption>Figura 4: Prototipação da funcionalidade de ver estatísticas de um vídeo postado. Autor: Victor Hugo Oliveira Leão</figcaption>

</center>

<div id="monetizacao"></div>

### 3.5 RF033 - O criador de conteúdo deve ser capaz de ver a monetização de seus vídeos.
<p align="justify">&emsp;&emsp;A figura 5 abaixo mostra a prototipação realizada acerca do requisito funcional com ID RF033: O criador de conteúdo deve ser capaz de ver a monetização de seus vídeos.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/rf033.png"/>

<figcaption>Figura 5: Prototipação da funcionalidade de ver a monetização. Autor: Victor Hugo Oliveira Leão</figcaption>

</center>

<div id="fila"></div>

### 3.6 RF035 - O usuário deve poder adicionar um vídeo à fila de reprodução.
<p align="justify">&emsp;&emsp;A figura 6 abaixo mostra a prototipação realizada acerca do requisito funcional com ID RF035: O usuário deve poder adicionar um vídeo à fila de reprodução.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/rf035.png"/>

<figcaption>Figura 6: Prototipação da funcionalidade de adicionar vídeo à fila de reprodução. Autor: Victor Hugo Oliveira Leão</figcaption>

</center>

## 4. Comprovação Informal 

<p align="justify">&emsp;&emsp;Nesta etapa da validação nossa equipe tentou, de várias formas, contactar o time de desenvolvedores e colaboradores da <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#plataforma" target="_blank">plataforma</a> para que os mesmos nos devolvessem possíveis problemas encontrados na documentação produzida por nós. </p>

### 4.1. Via Ajuda do Youtube
<center>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/validacao_contato_adp.png"/>

<figcaption>Figura 3: Pergunta enviada via Ajuda do Youtube.</figcaption>

Até o dia 16/08/2022 às 19:35, horário de Brasília, ainda não foram obtidas respostas.

<a href='https://support.google.com/youtube/thread/175430770?hl=pt-BR' target="_blank"><button style="border-radius: 8px;font-size: 18px;background-color: #f44336;">Link da pergunta</button></a>
</center>

### 4.2. Via Stack Overflow 
<center>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/validacao_contato_so.png"/>

<figcaption>Figura 4: Pergunta enviada via Stack Overflow.</figcaption>

Até o dia 16/08/2022 às 19:35, horário de Brasília, ainda não foram obtidas respostas.

<a href='https://stackoverflow.com/questions/73380888/youtube-requirements-artifacts' target="_blank"><button style="border-radius: 8px;font-size: 18px;background-color: #f44336;">Link da pergunta</button></a>
</center>

### 4.3. Via Twitter 
<center>
<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/validacao/validacao_contato_tt.jpeg"/>

<figcaption>Figura 5: Pergunta enviada via Twitter.</figcaption>

Até o dia 16/08/2022 às 19:35, horário de Brasília, ainda não foram obtidas respostas.

</center>

## 5. Referências

> - Milene Serrano, Requisitos - Aula 23. Acesso em: 14 de agosto de 2022. Disponível em: Aprender3.
> - Jacinta Pereira e  Rossana Andrade, Processos de Engenharia de
Requisitos. Acesso em: 16 de agosto de 2022. Disponível em: [Processos de Engenharia de
Requisitos](http://disciplinas.lia.ufc.br/engsof081/arquivos/ProcessosEngRequisitos-v2.pdf).

## 5. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0 | 14/08/2022 | Início do documento com introdução e metodologia | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/B3holder2" target="_blank">@B3holder2</a>, <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |
| 1.1    | 15/08/2022 | Correção do histórico de versão | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/Alef012" target="_blank">@Alef012</a> |
| 1.2    | 16/08/2022 | Adição das etapas de comprovação informal via Ajuda do Youtube, Stack Overflow e Twitter | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.3    | 16/08/2022 | Correções no texto de metodologia | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.4    | 17/08/2022 | Adição da prototipação do requisito funcional rf030 | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/B3holder2" target="_blank">@B3holder2</a>, <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |
| 1.5    | 17/08/2022 | Adição da prototipação do requisito funcional rf026 | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.6    | 17/08/2022 | Correção dos números das figuras | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/B3holder2" target="_blank">@B3holder2</a>, <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |
| 1.7    | 01/09/2022 | Adição de protótipos que estavam faltando | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a>  | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |