# Processo de tradução da WebIWG

_Nota: este documento NÃO foi revisado, e deve conter erros de português e de
lógica do processo**. Veja também o tópico [#6](https://github.com/webiwg/webiwg-issues/issues/6)_.

Índice

- [Etapa 1 - Definição de pertinência](#etapa-1---definição-de-pertinência)
- [Etapa 2 - Autorização para tradução](#etapa-2---autorização-para-tradução)
- [Etapa 3 - Preparação do documento para tradução](#etapa-3---preparação-do-documento-para-tradução)
- [Etapa 4 - Tradução](#etapa-4---tradução)
- [Etapa 5 - Revisão geral e publicação](#etapa-4---revisão-gera-e-publicação)

## O que ter em mente ao fazer traduções para o WebIWG
Parte do nosso grupo de trabalho é especificamente de pessoas que traduzem
documentos e podem ou não já serem especialistas em tegnologias da web. As
traduções não precisam ser feitas as pressas. **Um bom prazo** para documentos
que não fogem do comum em complexidade **é de 7 a 10 dias** após você e seu
revisor confirmarem que estão trabalhando no documento.

Sobre sua colaboração
- **Assim como os demais do grupo, seu trabalho é voluntário**, ou seja, neste
momento as traduções não são pagas; nos existimos justamente para viabilizar
esse tipo de trabalho
- **Seu trabalho como tradutor pode ser adicionado no seu Currículo Lattes**,
na parte de _Produção bibliográfica_.
- **Todos os artigos traduzidos por você terá um link de sua escolha** que
pode ser uma bibliografia sua em nosso site ou uma URL a sua escolha; estas
urls, diferentes do que ocorre na Wikipedia, não tem `rel="nofollow"`; caso
haja multiplos tradutores e/ou revisores, as duas pessoas principais terão
link
- **Suas traduções são inovadoras ou de grande importância histórica**, não
existententes ainda em português; isso pode ser decisivo para você mais tarde
ajudar a definir padrões a níveis nacionais ou internacionais, e causam grande
simpatia no meio acadêmico ou mesmo empresas mais inovadoras
- **Você recebera ajuda nossa para projetos relacionados**.

<!--
  fititnt: adicionais mais motivos no futuro
-->

## Etapa 1 - Definição de pertinência
Etiquetas relacionadas:
- **traducao-bloqueado:1-pertinencia**: usado quando pertiência ainda não está
definida; se a proposta, no momento da decisão, deve seguir adiante ou se
bloqueada

As traduções feitas por nosso grupo de trabalho ficam em [webiwg/historia-web-pt](https://github.com/webiwg/historia-web-pt)
e [webiwg/acessibilidade-web-pt](https://github.com/webiwg/acessibilidade-web-pt)
e todas as **sugestões de traduções devem ter alguma relação com o propósito
destes repositórios**. Além disso, mesmo que elas sejam pertinentes e tenham
relação com o conteúdo, tal sugestão de tradução poderá, a critério da
complexidade da tradução e da disponibilidade de equipe livre, ser marcada
como não pertinente em carater temporário.

## Etapa 2 - Autorização para tradução
Etiquetas relacionadas:
- **traducao-bloqueado:2-autorizacao**: usada quando deve-se pedir autorização para fonte original
- **traducao-andamento:2-autorizacao**: uma ou mais pessoas já estão em contato para pedir autorização; veja o tópico para detalhes adicionais
- **traducao-autorizada**: a tradução especifica deste item está autorizada; este marcador pode ser adicionado também em casos que o autor costuma liberar de antemão todas as traduções
- **traducao-autorizada-implicitamente**: este item não foi autorizado para tradução explicitamente, mas assume-se que é possível ser traduzido sem pedir explicitamente

É uma boa prática pedir autorização prévia para nossa equipe traduzir. É comum
que o fato de nosso grupo não ter fins lucrativos, e ser focado em ter como
objetivo trazer para o português textos de alta qualidade quanto a carater
educacional ou na história da web, que nos autorizem e até nos agradeçam. Ao
pedirmos autorização, isto também típicamente permite ao autor original:
- No artigo original, por link para nossa tradução
- Fazer observações sobre o texto. Por exemplo, dizer que está desatualizado
e pretende fazer a correção antes de traduzirmos
- Informar no futuro de atualizações do documento

Quando um autor, ou detentor dos direitos de cópia autoriza, nos adicionamos
o marcador **traducao-autorizada**. Isto quer dizer que há alguma comprovação
de que estamos autorizados explicitamente para o texto a ser traduzido, ou
então houve autorização para traduzir todos os textos daquele autor ou do
seu site.

Casos em que não é viável pedir autorização para uma pessoa, ou que a fonte
do artigo tipicamente não requer autorização prévia, ou mesmo que exige que
a autorização só seja data APÓS a tradução, nos poderemos adicionar o
marcador **traducao-autorizada-implicitamente**.

## Etapa 3 - Preparação do documento para tradução
Etiquetas relacionadas:
- **traducao-bloqueado:3-preparacao**: o documento está pronto, ou provavelmente está em breve, e deve ser obtido da fonte original, convertido para markdown e preparado para tradutores
- **traducao-liberado:3-preparacao**: o documento já foi convertido para markdown, e está pronto para tradutores iniciarem o processo

Para textos pertinentes e autorizados, é necessário preparar a inclusão deles
nos repositórios. **O ideal é que a equipe de pessoas tradutoras e
revisoras não precise saber de HTML**, nem tenha que definir melhor forma de
escolha de URLs, como armazenar imagens e afins. Isto também permite adição
de conteúdo via _Pull Requests_, sem frustrar a pessoa tradutora com coisas
irrelevantes a tradução.

### Como preparar documento

TL;DR: documentos HTML podem ser convertidos para markdown com ajuda de
ferramentas. Uma online é a https://domchristie.github.io/to-markdown/.
Depois de fazer a conversão e formatação, deixe pronto o original e
o documento a ser traduzido exatamente com o mesmo conteúdo. Se for
necessário fazer novas formatações visuais na edição traduzida,
pode ser interessante editar também o original.

#### Da origem dos dados
Na maioria das vezes, a origem dos dados é uma página única, porém isso não
ocorrerá sempre. Um exemplo é a tradução de uma troca de e-mails que tem
valor histórico, e requer que sejam acessadas várias páginas, ou mesmo que
haja conversão de algum formato de imagem que é tão antigo que não há suporte
dos navegadores atuais.

Se este é um caso, a pessoa responsavel pela preparação do documento deverá
usar de seu bom senso e deixar o mais fácil possível para a equipe tradutora.
Isso poderá significar, por exemplo, que você deverá mesclar várias páginas
em um só documento.

**Lembre-se: em documentos grandes, esta preparação poderá selecionar apenas
partes que são relevantes para tradução.**

#### Da referência a links externos e biografia do autor
Caso o documento a ser preparado tenha links a referências externas que tenham
grande importância, ou a tradução desta referência deve ser junta, ou deve-se
abrir um novo tópico para tradução. Tenha isto em mente, e deixe claro
para os tradutores.

Sempre que pertinente se o autor original, ou a instituição que ele representa
ainda não estão adicionados na [historia-web-pt](https://github.com/webiwg/historia-web-pt)
idealmente isto deve ser feito, ou no mínimo agendado para ser feito no futuro.

Caso a biografia seja simples, a pessoa responsável pela preparação do conteúdo
é convidada a já preparar isto também. Porém, se for algo mais complexo, por
exemplo, como o [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/),
vale a pena abrir um tópico exclusivo para traduzir a biografia dele.

#### Da decisão de URL do documento
No ideal é que **a URL do documento a ser traduzido não se altere com passar
dos anos** por dois motivos:
- Links para nosso site param de funcionar (e ninguém gosta disso, ainda mais se
pretendemos ser referência não só para site, mas para impressos)
- É complicado acompanhar histórico de edições pelo git de arquivos renomeados

Tendo em mente esses dois problemas, se for possível escolher um bom nome que
não precisará ser alterado no futuro, melhor. Se estiver em dúvida, discuta
essa escolha com os demais

#### Da cópia de arquivo original como backup
Idealmente, devemos ter pelo menos duas cópias no repositório, e opcionalmente
uma terceira

1. **Copia a ser traduzida**, exemplo `/nvda/mudando-do-jaws-para-o-nvda/index.md`
2. **Copia do original, formatada**, exemplo `/nvda/mudando-do-jaws-para-o-nvda/_original.md`
3. **Cópia bruta do original**, (opcional!) e aplicável somente a documentos que
podem ser alterados e não há um controle de versão na origem

Os itens 1 e 2 sempre devem existir, e os itens 2 e 3 devem ter algum tipo de
controle para não serem acessados, ou pelo menos indexados por mecanismos
de busca, no site final gerado nos repositórios, pois é comum que autores
permitam a tradução, mas não uma cópia idêntica do original em site de
terceiros.

#### Da formatação do documento

**Muito importante**: a formatação do documento, além de resolver conversão de
outros formatos para markdown, **tem como objetivo facilitar o trabalho da
equipe de tradução em detrimento de formatação de texto, limite de colunas,
e afins**. Como o tamanho das palavras sempre serão diferentes de um idioma
para o outro, é melhor usar o bom senso do que forçar um limite de, por
exemplo, 80 caracteres.

##### Da escolha de quebra de linhas
A equipe de tradução será orientada a fazer tradução linha por linha, e
não serão convidados sequer a saber quantidade de caracteres por linha. É
responsabilidade de quem formata o documento usar bom senso e que, a
escolha que você tomar, vai ficar assim por anos. Não que isso seja algo
grave, mas facilita se levar em consideração alguns pontos a seguir.

**Procure fazer quebras de linhas somente a cada ponto final** ou, se as
frases forem MUITO grandes, como um parágrafo inteiro, **quebre após 
alguma virgula**. A meta é que a equipe de tradução tenda a manter
a tradução exata anterior na mesma alteração de linha. Isto facilita
na hora de investigar o passado.

Tende a não valer a pena quebrar linhas em itens que fazem mais sentido
juntos. Por exemplo, um título (h1, h2, h3...) no original, mesmo que
seja grande, pode valer a pena deixar junto. Uma legenda de imagem
que não for muito grande também pode fazer mais sentido manter na mesma
linha.

#### Da inclusão de imagens
Caso seja necessário adicionar imagens do original, o ideal é que elas
já estejam otimizadas para serem exibidas via web, a não ser que a
razão de existir das imagens seja permitir impressão. É recomendável
que vocễ use sites como https://tinypng.com/ ou https://tinyjpg.com/
antes de adicionar a imagem.

Outro ponto é que idealmente imagens e arquivos relacionados a
uma tradução, fiquem na mesma pasta da tradução, exceto em casos
muito especiais em que a imagem é reutilizada muitas vezes, mas
por padrão, adicione mais uma vez cada imagem.

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
    fititnt: este bloco de conteudo usa tags de comentário de HTML e somente é visivel ao
             se olhar o código fonte. É um bom local para deixar comentários para revisores
             e outros tradutores, como por exemplo uma lista de palafras que ficou em dúvida
             ou mesmo um comentário de "não terminei o ultimo parafrafo" 
    dkmister: aqui outra pessoa deixando outro comentário. No caso seria o Vilmar
-->

Texto do artigo traduzido (...)

```

A discussão mais completa sobre isso pode ser lida em [Estratégias para
mitigar dúvidas em termos que devem (ou não) serem traduzidos](https://github.com/webiwg/webiwg-issues/issues/8).

## Etapa 5 - Revisão geral e publicação
Esta é a ultima etapa do processo. Tão logo a equipe de tradução diga que
concluíu o processo, poderá haver uma nova revisão, principalmente
relacionada a aparência visual do documento.
