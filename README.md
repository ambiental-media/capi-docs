<img src="_assets/Horizontal-colorido.png" alt="Logo da Ambiental Media" style="float:right" height="60em">

<p align="center" height="120em"><img src="_assets/LOGO-FINAL-capi.png" alt="Logo da Capí, um rosto de uma capivara sorrindo" style="float:left vertical-align:middle" height="180em"></p>

<h1 align="center">Documentação & Compartilhamento</h1>

## Sobre a Capí

<p align="center"><em>Capí: inteligência artificial contra a desinformação climática</em></p>

A *Capí* é um projeto que utiliza a inteligência artificial para combater a desinformação climática e promover a educação ambiental. Por meio de um chatbot intuitivo e acessível, oferece informações confiáveis e atualizadas sobre os impactos das mudanças climáticas, seus efeitos na sociedade e no meio ambiente, e as ações que podem ser tomadas para mitigar seus efeitos.

Desenvolvida por uma equipe multidisciplinar, formada por engenheiros, jornalistas, educadores e designers, a *Capí* busca democratizar o acesso a informações sobre a ciência do clima, tornando-as acessíveis para um público amplo, especialmente jovens estudantes.

As principais funcionalidades da *Capí* incluem:

* Acesso a informações precisas: a *Capí* é alimentada por uma base de dados robusta, curada por jornalistas especializados em meio ambiente, e por modelos de linguagem de ponta, como o Gemini, que garantem a confiabilidade e a qualidade das informações fornecidas;
* Curadoria jornalística: o conteúdo é atualizado e revisado por uma equipe de jornalistas especialistas em meio ambiente e mudanças climáticas;
Engajamento do público: a *Capí* utiliza uma linguagem simples e direta, tornando as informações sobre as mudanças climáticas e o meio ambiente mais acessíveis;
* Ferramenta educacional: pode ser utilizada como uma ferramenta pedagógica em escolas, proporcionando um aprendizado mais interativo e dinâmico sobre as questões ambientais e as mudanças climáticas.

Com a *Capí*, buscamos subsidiar o público com as informações necessárias para tomar decisões conscientes e incentivar ações contra a desinformação ambiental e climática.

## Sobre Esta Documentação

Neste texto descrevemos o processo de criação do chatbot *Capí*. A ideia é que as experiências e os conhecimentos adquiridos durante o desenvolvimento da *Capí*, possam auxiliar outros veículos de comunicação na criação de soluções similares e a fortalecer o combate à desinformação no Brasil.

### Nota sobre o não compartilhamento do código-fonte

A Ambiental não compartilha o código-fonte da *Capí* porque entende que permitir acesso a ele neste momento do ciclo de vida da ferramenta pode deixar a plataforma vulnerável a ataques maliciosos e dificultar eventuais correções de bugs e implementação de melhorias. No entanto, deixamos alguns detalhes que podem ser úteis para desenvolvedores interessados em realizar projetos similares nesta nota e no restante da documentação disponibilizada neste repositório.

A interface gráfica (*frontend*) do projeto foi construída de forma padrão, utilizando o *framework* de uso livre NextJS. A documentação oficial desse framework passa por atualizações recorrentes e a última versão está sempre [disponível no site oficial](https://nextjs.org/docs).

O ponto de comunicação entre o frontend e o agente de inteligência artificial foi construído com a API do Google Cloud Dialog Flow, um dos componentes do Google Cloud Vertex AI Agent Builder. Esse conjunto de ferramentas disponibilizadas pela Google Cloud pode ser acionada por código-fonte puro ou no modo conhecido como *low-code*, ou seja, via interface gráfica disponibilizada no console da API. Durante o desenvolvimento da *Capí*, decidiu-se utilizar o modo *low-code* para economizar tempo e custos e agilizar os processos de atualização constante pelo qual a ferramenta vem passando.

Boa parte dos componentes desse conjunto de ferramentas, o Google Cloud Vertex AI Agent Builder, ainda está em versão beta e toda a plataforma vem sofrendo ajustes e atualizações com frequência. Portanto, caso desenvolvedores queiram criar projetos semelhantes à *Capí*, sugerimos como melhor prática se apoiar nas [documentações oficiais](https://cloud.google.com/dialogflow/cx/docs?hl=pt-br), que contém informações detalhadas.

O planejamento de longo-prazo do ciclo de vida da *Capí* inclui a migração do agente de inteligência artificial para um repositório de código gestionado pela Ambiental. Esse repositório também receberá as rotinas de DevOps necessárias para a manutenção do ciclo de vida do agente. Esses detalhes serão compartilhados posteriormente, conforme novos ciclos de apoio financeiro e desenvolvimento do projeto se tornem realidade.

Por fim, reiteramos que a Ambiental está comprometida com o compartilhamento do processo de desenvolvimento da *Capí*. Contudo, é importante que nosso time mantenha um nível maior de controle sobre o ciclo de vida da *Capí* neste primeiro momento, sobretudo porque melhorias, correções, manutenções e combate a eventuais abusos por parte de atores maliciosos poderão ser necessários.

Qualquer dúvida, não hesite em contatar o nosso time. Estamos disponíveis no e-mail weare@ambiental.media.

## Conteúdo da Documentação

### [Histórico do Projeto](./historico/README.md)
### [Sistema](./sistema/README.md)
