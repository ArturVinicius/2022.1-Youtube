# Especificação Suplementar

## 1. Introdução
<p align="justify">&emsp;&emsp;A Especificação Suplementar é um documento em linguagem natural, no qual são descritos os requisitos não-funcionais. (Milene Serrano, Requisitos - Aula 10, página 28).</p>

<p align="justify">&emsp;&emsp;Além disso, alguns outros requisitos podem ser obtidos a partir desse documento, como, por exemplo:</p>

- Requisitos legais e reguladores, incluindo padrões de aplicativo;
- Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade;
- Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design.

(Samily Gois, Projeto de Software Floricultura Beija-Flor Especificação Suplementar, página 4).

<p align="justify">&emsp;&emsp;Esse documento orienta-se pelo FURPS+.</p>

## 2. FURPS+
<p align="justify">&emsp;&emsp;O FURPS+ é um modelo em que cada letra entende-se por uma categoria de requisitos.</p>

<div id="func"></div>

### 2.1 F - Funcionality - Funcionalidade
<p align="justify">&emsp;&emsp;São requisitos relacionados à especificação das funcionalidades do sistema. Eles já foram <a href="https://requisitos-de-software.github.io/2022.1-Youtube/elicitacao/resultado/" target="_blank">elicitados</a> e também podem ser encontrados como <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/casouso/" target="_blank">casos de uso</a> e <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/cenarios//" target="_blank">cenários</a>.</p>

<div id="usab"></div>

### 2.2 U - Usability - Usabilidade
<p align="justify">&emsp;&emsp;São requisitos relacionados a interface com o usuário. Exemplos:</p>

- Prevenção de erros.
- Ajudas.
- Consistência.
- Padrões.
- Documentação.

<div id="conf"></div>

### 2.3 R - Reliability - Confiabilidade
<p align="justify">&emsp;&emsp;São requisitos relacionados à integridade e interoperabilidade (comunicação com outros sistemas) do software. Exemplos:</p>

- Frequência de falhas.
- Possibilidade de recuperação.
- Duração da falha.
- Estabilidade.

<div id="perf"></div>

### 2.4 P - Performance - Performance
<p align="justify">&emsp;&emsp;São requisitos relacionados ao desempenho do software. Exemplos:</p>

- Tempo de resposta.
- Consumo de recursos.
- Escalabilidade.
- Disponibilidade.

<div id="supo"></div>

### 2.5 S - Suportability - Suportabilidade
<p align="justify">&emsp;&emsp;São requisitos relacionados a capacidade de suporte do software, tanto para consigo mesmo, quanto para o usuário. Exemplos:</p>

- Testabilidade.
- Adaptabilidade.
- Manutenibilidade.
- Compatibilidade.
- Instalabilidade.
- Portabilidade.

<div id="mais"></div>

### 2.6 +
<p align="justify">&emsp;&emsp;Com a evolução do FURPS, foram encontradas algumas outras categorias para requisitos de software, tais como:</p>

- **Design**: restringem o design de um sistema. Exemplos: padrões de design, processo de desenvolvimento de software, uso de ferramentas de desenvolvimento etc.
- **Implementação**: restringem a construção/código do software. Exemplos: linguagens de programação, políticas de integridade do banco de dados, ambientes operacionais etc.

## 3. Especificação Suplementar
<p align="justify">&emsp;&emsp;Após o entendimento do modelo FURPS+, a Especificação Suplementar do sistema foi desenvolvida.</p>

<p align="justify">&emsp;&emsp;Alguns requisitos foram estimados, isto é, não foi possível encontrar uma confirmação oficial ou testá-los. Eles foram identificados por "Requisito Estimado" em itálico.</p>

| Categoria           | Requisitos |
| :-----------------: | :--------- |
| **U**sabilidade     | Idade mínima de 13 anos para usar o aplicativo.</br> |
| **U**sabilidade     | Operar segundo as leis de Delaware, onde se encontra a sede da empresa. </br> |
| **U**sabilidade     | O sistema deve ter um site direcionado para ajudas, em que diversas possíveis falhas e suas resoluções são explicadas. </br>|
| **U**sabilidade     | O aplicativo deve ter um site com informações dos seus Termos de Uso e Serviço. </br> |
| **U**sabilidade     | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) executa ações essenciais em, no máximo, 5 [cliques](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/verbo/#clicar). </br> |
| **U**sabilidade     | Quando possível, ícones devem ser usados juntamente com textos para trazer uma melhor visibilidade da funcionalidade para o [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario). </br> |
| **U**sabilidade     | A tela inicial e de busca devem apresentar um padrão direcionado à exibição de [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) recomendados/encontrados. </br>  |
| **C**onfiabilidade  | Não é esperada nenhuma frequência de falhas constante e/ou periódica no aplicativo.</br>|
| **C**onfiabilidade  | Em 99% dos casos, deve-se haver a possibilidade de recuperação. </br>*Requisito Estimado*|
| **C**onfiabilidade  | As falhas devem ter prioridade máxima de recuperação quando encontradas, durando não mais que 24h para que sejam extinguidas. </br>*Requisito Estimado*|
| **C**onfiabilidade  | O [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser avisado caso o sistema esteja passando por alguma falha. </br>|
| **P**erformance     | Se espera que 90% do tempo quando se assiste youtube, os [vídeos](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#video) tenham uma qualidade padrão de pelo menos 360p. </br>Presente em: Relatório de qualidade de vídeo do Google - Ajuda do YouTube|
| **P**erformance     | O aplicativo deve funcionar durante 168h semanais, sem a expectativa de instabilidade. </br>*Requisito Estimado*|
| **S**uportabilidade | O aplicativo deve ser disponível para os principais sistemas operacionais de dispositivos Mobile, como iOS e Android </br>| 
| **S**uportabilidade | Quando um teste ou manutenção for ocorrer no aplicativo, o [usuário](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#usuario) deve ser previamente avisado.</br>| 
| **S**uportabilidade  | Conexão de Internet com 500Kbps ou mais.</br>Presente em: Requisitos do sistema - Ajuda do YouTube |
| **S**uportabilidade  | 274,2 Mb de memória disponível no celular.</br>Presente em: Requisitos do sistema - Ajuda do YouTube |
| **S**uportabilidade  | Caso o acesso seja feito fora do App, é necessário utilizar algum navegador como Google Chrome, Firefox, MS Edge, Safari ou Opera</br> *Requisito Estimado*|
| **S**uportabilidade  | O sistema deve ter um site para explicar suas Políticas e Segurança: Política, segurança e direitos autorais - Ajuda do YouTube.</br> |
| **+**               | O sistema deve disponibilizar a opção de alterar o idioma das [notificações](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#notificacao) e o do sistema.</br>|

## 4. Contato com o YouTube
<p align="justify">&emsp;&emsp;O grupo enviou uma mensagem para a comunidade do YouTube a fim de buscar por informações oficiais acerca da Especificação Suplementar, mais especificamente requisitos do modelo FURPS+. Segue na figura 1 um print da mensagem enviada.</p>

<center>

<img src="https://user-images.githubusercontent.com/33530818/179577308-cec8ab76-2d9d-4ef6-8916-189383661021.png"/>

<figcaption>Figura 1: Mensagem de Contato com o YouTube.</figcaption>

<p align="justify">&emsp;&emsp;Até o dia 03/09/2022 às 23:30, horário de Brasília, recebemos apenas uma recomendação para postarmos a mensagem no StackOverflow, onde desenvolvedores poderiam ajudar com melhor eficácia.</p>

<a href='https://support.google.com/youtube/thread/171629913?hl=pt-BR' target="_blank"><button style="border-radius: 8px;font-size: 18px;background-color: #f44336;">Thread da Mensagem</button></a>

</center>

## 4.1 Contato com o youtube via Stack Overflow
<p align="justify">&emsp;&emsp;O grupo fez uma pergunta na plataforma Stack Overflow a fim de intensificar a busca por informações oficiais acerca da Especificação Suplementar, mais especificamente requisitos do modelo FURPS+. Segue a figura 2, um print da pergunta na plataforma.</p>

<center>

<img src="https://raw.githubusercontent.com/Requisitos-de-Software/2022.1-Youtube/main/docs/media/pergunta-stackoverflow.png"/>

<figcaption>Figura 2: Pergunta enviada ao Stack Overflow.</figcaption>

<p align="justify">&emsp;&emsp;A pergunta foi excluída por motivos de moderação, logo não recebemos retorno satisfatório.</p>

</center>

## 5. Referências

> - Milene Serrano, Requisitos - Aula 10. Acesso em: 17 de jul. de 2022. Disponível em: Aprender3.
> - Samily Gois, Projeto de Software Floricultura Beija-Flor Especificação Suplementar. Acesso em: 17 de jul. de 2022.
> - Youtube. Acesso em: 29 de jun. de 2022. Disponível em: https://about.youtube/
> - Requisitos do sistema - YouTube. Acesso em 03 de set. de 2022. Disponível em: https://support.google.com/youtube/answer/78358?hl=pt-BR
> - Relatório de qualidade de vídeo do Google. Acesso em 03 de set. de 2022. Disponível em: https://support.google.com/youtube/answer/6013340?hl=pt-BR
> - Wikipedia - FURPS. Acesso em: 17 de jul. de 2022. Disponível em: https://pt.wikipedia.org/wiki/FURPS

## 6. Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 17/07/2022 | Criação da primeira versão do documento com a introdução, explicação de FURPS e estrutura da especificação suplementar | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |
| 1.1    | 18/07/2022 | Adição da mensagem de contato com o YouTube | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |
| 1.2    | 20/07/2022 | Adição da Especicificação suplementar | <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a>  |  <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.3    | 24/07/2022 | Adição da pergunta enviada ao stackoverflow | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a>  |  <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.4    | 24/07/2022 | Adição dos links de perfil do github no histório de versão da página de Especificação Suplementar | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a>  |  <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> |
| 1.5    | 24/07/2022 | Melhorias de links dos githubs no <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico" target="_blank">histórico</a> de versões | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.6    | 24/07/2022 | Referência de links dos léxicos encontrados na página | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.7    | 25/07/2022 | Correção dos links dos githubs no <a href="https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/lexicos/objeto/#historico" target="_blank">histórico</a> de versões | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | 
| 1.8    | 03/08/2022 | Correção dos requisitos de Funcionalidade e atualização das mensagens no youtube e stackoverflow | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/owhenrique" target="_blank">@owhenrique</a> |
| 1.9    | 03/09/2022 | Remoção do link para o stackoverflow, já que a pergunta foi excluída. Além da adição de requisito estimado para os requisitos não encontrados ou testados | <a href="https://github.com/victorleaoo" target="_blank">@victorleaoo</a> | <a href="https://github.com/lramon2001" target="_blank">@lramon2001</a> |