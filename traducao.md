# Processo de tradução da WebIWG

_Nota: ver o tópico [#6](https://github.com/webiwg/webiwg-issues/issues/6)_.

Índice

- [Etapa 1 - Definição de pertinência](#etapa-1---definição-de-pertinência)
- [Etapa 2 - Autorização para tradução](#etapa-2---autorização-para-tradução)
- [Etapa 3 - Preparação do documento para tradução](#etapa-3---preparação-do-documento-para-tradução)
- [Etapa 4 - Tradução](#etapa-4---tradução)
- [Etapa 5 - Revisão geral e publicação](#etapa-4---revisão-gera-e-publicação)

## O que ter em mente ao fazer traduções para o WebIWG

Parte do nosso grupo de trabalho é formado por pessoas que traduzem documentos
e podem ou não ser especialistas em tecnologias da web. As traduções não
precisam ser feitas às pressas. Um bom prazo para documentos que não fogem do
comum em termos de complexidade estaria entre **7 a 10 dias** após você e seu
revisor confirmarem que estão trabalhando no documento.

## Sobre sua colaboração

- **Assim como os demais membros do grupo, seu trabalho é voluntário**, ou seja,
neste momento as traduções não são remuneradas; nós existimos justamente para
viabilizar esse tipo de trabalho.
- **Seu trabalho como tradutor pode ser adicionado ao seu currículo Lattes**,
na seção de _produção bibliográfica_.
- **Todos os artigos traduzidos por você terão um link de sua escolha** que
pode ser uma bibliografia sua em nosso site ou uma URL a sua escolha. Este
link, diferentemente do que ocorre em sites como a Wikipedia, não terá
`rel="nofollow"`. Caso haja múltiplos tradutores e/ou revisores, os dois
principais envolvidos deterão direito a link.
- **Suas traduções são inovadoras e de grande importância histórica**, não
existentes ainda em português. Isso pode ser decisivo para você mais tarde
ajudar a definir padrões a níveis nacionais ou internacionais, e causam grande
simpatia no meio acadêmico ou mesmo entre empresas mais inovadoras.
- **Você receberá ajuda nossa para projetos relacionados**.

<!--
  @fititnt: adicionais mais motivos no futuro
-->

## Etapa 1 - Definição de pertinência

As traduções feitas por nosso grupo de trabalho se encontram nos repositórios
[webiwg/historia-web-pt](https://github.com/webiwg/historia-web-pt) e
[webiwg/acessibilidade-web-pt](https://github.com/webiwg/acessibilidade-web-pt);
todas as **sugestões de traduções devem ter alguma relação com o propósito
destes repositórios**. Para sugerir uma tradução, abra um issue com:

- título idêntico ao do documento proposto;
- descrição contendo:
  1. link do original;
  2. descrição curta do documento;
  3. e traduções já existentes em língua portuguesa;
- e marcador `traducao`.

Além disso, mesmo que seja pertinente e tenha relação com o conteúdo, a sugestão
poderá, a critério da complexidade da tradução e da disponibilidade de equipe
livre, ser marcada como não pertinente em carater temporário.

## Etapa 2 - Autorização para tradução

É uma boa prática pedir autorização prévia a autores e mantenedores para nossa
equipe traduzir. Por este grupo não ter fins lucrativos e destinar-se a levar
textos de alta qualidade para a língua portuguesa que possuam caráter histórico
e/ou educacional, os autores costumam ser simpáticos a traduções voluntárias, o
que, contudo, não implica autorização automática da reprodução do seu trabalho
criativo. Ao pedirmos autorização, permite-se ao autor original:

- Referenciar a nossa tradução por link no artigo original;
- Fazer observações sobre o texto (e.g. indicar desatualização/erro no original
  que deve corrigido antes da tradução);
- Informar sobre futuras atualizações do documento.

Quando um autor ou detentor dos direitos de cópia autoriza, nós adicionamos
um marcador específico à issue indicando que há alguma comprovação de que
estamos explicitamente autorizados para tradução do documento, de uma série de
documentos ou de um blog/site.

<!--
  @tassoevan: referenciar o marcador da etapa de autorização e dos estados da
              etapa
-->

Há casos em que não é viável, necessário ou possível pedir autorização para uma
pessoa, como em documentos de domínio público, com licença específica informada
ou com autorização liberada apenas _após_ a tradução, recebendo marcador
específico da autorização implícita.

<!--
  @tassoevan: referenciar o marcador da autorização implícita
-->

## Etapa 3 - Preparação do documento para tradução

Para textos autorizados, é necessário preparar a inclusão deles nos
repositórios. **Os tradutores e revisores não precisam saber HTML** ou deter
conhecimento relacionado a URLs ou armazenamento de hipermídia anexa. Isso
flexibiliza a adição de conteúdo via _pull requests_ e elimina requisitos que
poderiam afastar voluntários engajados apenas no processo de tradução.

### Como preparar documentos

Documentos HTML podem ser convertidos para Markdown com ajuda de ferramentas.
Uma delas é a https://domchristie.github.io/to-markdown/, disponível para uso
online. Depois de fazer a conversão e formatação, **deixe pronto o original e
o documento a ser traduzido exatamente com o mesmo conteúdo**. Se for necessário
fazer novas formatações visuais na edição traduzida, edite também o original.

#### Da origem dos dados

Na maioria das vezes, a origem dos dados é uma página única, porém isso não
ocorrerá sempre. Um exemplo é a tradução de uma troca de e-mails que tem
valor histórico, que requer que sejam acessadas várias páginas ou mesmo que
haja conversão de algum formato de imagem que é tão antigo que não há suporte
nos navegadores atuais. Se este é um caso, a pessoa responsável pela preparação
do documento deverá usar de seu bom senso e deixar o mais fácil possível para a
equipe tradutora. Isso poderá significar, por exemplo, que você deverá mesclar
várias páginas em um só documento.

**Lembre-se: em documentos grandes, esta preparação poderá selecionar apenas as
partes que são relevantes para tradução.**

#### Da referência a links externos e biografia do autor

Caso o documento a ser preparado tenha links a referências externas que têm
grande importância, ou a tradução desta referência deve ser conjunta, ou deve-se
abrir um novo tópico para tradução. Tenha isto em mente e deixe claro para os
tradutores.

Sempre que pertinente, se o autor original, ou a instituição que ele representa,
ainda não estão adicionados na
[historia-web-pt](https://github.com/webiwg/historia-web-pt), então isto deve
ser feito assim que possível. Caso a biografia seja simples, a pessoa
responsável pela preparação do conteúdo é convidada a já preparar isto também.
Para algo mais complexo como, por exemplo, a biografia de
[Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/), vale a pena abrir um
tópico exclusivo para traduzir a biografia.

#### Da decisão de URL do documento

É almejável que **a URL do documento a ser traduzido não se altere com passar
dos anos** por dois motivos:

- Links para nosso site param de funcionar (e ninguém gosta disso, ainda mais se
  pretendemos ser referência não só para a web, como também para impressos);
- É complicado acompanhar histórico de edições de arquivos renomeados através do
  git.

A julgar por esses dois problemas, sempre que possível escolha um bom nome que
não precisará ser alterado no futuro. Se estiver em dúvida, discuta essa escolha
com os demais membros do grupo.

#### Da cópia de arquivo original como backup

Idealmente, devemos ter pelo menos duas cópias no repositório e, opcionalmente,
uma terceira:

1. **Copia a ser traduzida**, e.g. `/nvda/mudando-do-jaws-para-o-nvda/index.md`;
2. **Copia formatada do original**, e.g.
   `/nvda/mudando-do-jaws-para-o-nvda/_original.md`;
3. **Cópia bruta do original (opcional)**, aplicável somente a documentos que
podem ser alterados e cujo origem não possui um controle de versão.

Os itens 1 e 2 sempre devem existir e os itens 2 e 3 devem ter algum tipo de
controle para não serem acessados (ou pelo menos indexados por mecanismos de
busca) no site final gerado nos repositórios, pois é comum que autores permitam
a tradução sem uma cópia idêntica do original em site de terceiros.

#### Da formatação do documento

**Muito importante**: a formatação do documento, além de resolver conversão de
outros formatos para Markdown, **tem como objetivo facilitar o trabalho da
equipe de tradução em detrimento de formatação de texto, limite de colunas,
e afins**. Como o tamanho das palavras sempre serão diferentes de um idioma
para o outro, é melhor usar o bom senso do que forçar um limite de, por exemplo,
80 caracteres.

##### Da escolha de quebra de linhas

A equipe de tradução será orientada a fazer tradução linha por linha, e não
serão convidados sequer a saber quantidade de caracteres por linha. É
responsabilidade de quem formata o documento usar bom senso e arcar com o fato
de que a escolha tomada perdurará por anos. Não que isso seja algo grave, mas
facilita se levar em consideração alguns pontos a seguir.

**Procure fazer quebras de linhas somente a cada ponto final** ou, se as frases
forem _muito_ grandes, como um parágrafo inteiro, **quebre após alguma
virgula**. A meta é que a equipe de tradução tenda a manter a tradução exata
anterior na mesma alteração de linha. Isto facilita na hora de investigar o
passado.

Não agrega valor quebrar linhas em itens que fazem mais sentido juntos. Por
exemplo, um título (h1, h2, h3...) no original, mesmo que seja grande, ficará
melhor descrito numa única linha. Uma legenda de imagem que não for muito grande
também pode fazer mais sentido quando mantida na mesma linha.

#### Da inclusão de imagens

Caso seja necessário adicionar imagens do original, elas precisam estar
otimizadas para serem exibidas na web, a não ser que a razão de existir das
imagens seja permitir impressão. É recomendável que você use sites como
https://tinypng.com/ ou https://tinyjpg.com/ antes de adicionar a imagem.

<!--
  @tassoevan: pedir esclarecimento sobre a frase "a não ser que a razão de
              existir das imagens seja permitir impressão"
-->

Outro conselho é que imagens e arquivos relacionados a uma tradução devem ficar
no mesmo diretório da tradução, exceto em casos muito especiais em que a imagem
é reutilizada muitas vezes; mas, por padrão, adicione mais uma vez cada imagem.

## Etapa 4 - Tradução

Quando o documento já tiver sido preparado, a equipe de tradução estará
liberada para iniciar os trabalhos. Em geral, o ideal para documento que não
são muito grandes, o responsável principal pela tradução inicie e termine
ela, e só então um ou mais revisores são convidados a iniciar sua etapa.

### O que é Markdown?
Você provavelmente fará a edição pela interface do Github, onde também tem
opção para ver resultado visual em "Preview changes". Caso queira saber
mais sobre markdown, leia https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet.

Em geral, o documento a ser traduzido já vai ter sido preparado, então
você poderá se focar mais em traduzir do que na formatação.

### Faça tradução linha por linha
O sistema de controle de versão git tende a ajudar investigar passado
melhor se você mantiver próximo do que recebeu originalmente, e isso faz
muita diferença se mantiver as linhas.

Independente do tamanho de cada linha, **procure fazer as traduções linha por
linha sem quebrar o resultado traduzido em mais linhas, nem mesclar linhas
em relação ao original**.

### Não tenho certeza da tradução de uma palavra
Se não tem certeza da tradução de uma palavra, provisoriamente deixa a
palavra ou o termo inteiro na lingua original, e a mantenha em itálico.
`_underline no inicio e fim_` gera em italigo "_underline no inicio e fim_".

Adicionalmente, você pode adicionar comentários, que não serão visíveis
na página final. Isso pode ser feito iniciando o bloco com `<!--` e
encerrando com `-->`. Por exemplo

```markdown
# Titulo do artigo a ser traduzido

<!--
  Notas de tradução:
    @fititnt: este bloco de conteudo usa tags de comentário de HTML e somente é visivel ao
              se olhar o código fonte. É um bom local para deixar comentários para revisores
              e outros tradutores, como por exemplo uma lista de palafras que ficou em dúvida
              ou mesmo um comentário de "não terminei o ultimo parafrafo"
    @dkmister: aqui outra pessoa deixando outro comentário. No caso seria o Vilmar
-->

Texto do artigo traduzido (...)

```

A discussão mais completa sobre isso pode ser lida em [Estratégias para
mitigar dúvidas em termos que devem (ou não) serem traduzidos](https://github.com/webiwg/webiwg-issues/issues/8).

## Etapa 5 - Revisão geral e publicação
Esta é a ultima etapa do processo. Tão logo a equipe de tradução diga que
concluíu o processo, poderá haver uma nova revisão, principalmente
relacionada a aparência visual do documento.
