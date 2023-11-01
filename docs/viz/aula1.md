# 1. Por que aprender a construir visualizações de dados é importante?

<iframe width="560" height="315" src="https://www.youtube.com/embed/QGhDlGTLcSU?si=sCPrqzXidLYD1iJz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Sobre esta aula

Nesta aula de introdução ao curso **Mãos à obra: Visualização de Dados com Python**, você irá entender a importância de aprender a construir uma visualização de dados, aprender o que é uma visualização de dados e analisar dois exemplos muito interessantes e bastante distintos de visualizações de dados.

- 0:00 Metodologia do Curso
- 0:38 O que é uma Visualização de Dados?
- 1:45 Exemplo 1: Better Life Index
- 3:41 Exemplo 2: Wind Map 

!!! info Apoie este material

    O curso completo está disponível para os membros do canal Programação Dinâmica no nível Superfã ou Capuccino. Se você gosta do nosso trabalho e acha relevante a existência de materiais como este, considere nos [apoiar se tornando membro do canal(https://www.youtube.com/programacaodinamica/join)].


----
### Conteúdo da aula
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Olá, aqui começa nossa jornada – eu, você e a visualização de dados – e estou bastante feliz por isso. Espero que você também esteja animado(a) para essa experiência.</span>
</p>
<blockquote><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Nosso ponto de partida é uma reflexão: <em data-redactor-tag="em">"Por que e para que vamos aprender a construir uma visualização de dados?"</em></span>
</blockquote>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Em primeiro lugar, se você chegou até esse curso, posso supor que você compreende em alguma medida a importância de lidar com dados. Fato é que, no momento que estou escrevendo esse curso, se fala muito mais sobre dados do que quando eu ainda estava na faculdade. Já ouvi repetidas vezes a frase "Os dados são o novo petróleo" que é atribuída a Clive Humby ("<em data-redactor-tag="em">Data is the new oil</em>") e supostamente foi dita pela primeira vez em 2006. Os anos se passaram e essa expressão ganha cada vez mais força.</span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Se ignorarmos o tom sensacionalista da frase e percebermos que os dados são o insumo para algoritmos que influenciam a tomada de decisão e comportamento das pessoas ao redor de todo o mundo, é possível chegarmos à conclusão de que, independentemente de dados serem ou não um "novo petróleo", eles são relevantes nos mais variados contextos sociais e, certamente, representam um ativo com valor socioeconômico em nossa sociedade atual.<br/></span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">E se os dados, por si, são um ativo, as informações que podem ser extraídas desses dados, são ainda mais valiosas. Atualmente, qualquer profissional que desenvolva a habilidade de extrair informações de grandes volumes de dados se diferencia no mercado de trabalho em todos os nichos de atuação. No entanto, não basta extrair informações de dados e não saber interpretar e comunicar essas informações obtidas; nesse sentido, aprender a construir uma visualização de dados é imprescíndivel.</span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);"><span style="background-color:rgb(255, 255, 0)" rel="background-color: rgb(255, 255, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="background-color: rgb(255, 255, 0);"><strong data-redactor-tag="strong">Mas, afinal de contas o que precisamente é uma visualização de dados?</strong></span></span>
</p>
<blockquote><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Segundo Andy Kirk, uma visualização de dados é <em data-redactor-tag="em">a <strong data-redactor-tag="strong">representação visual e a apresentação de dados para facilitar o entendimento.</strong><br/></em></span>
</blockquote>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Nesse curso, iremos aprender e discutir a representação visual e apresentação de dados aplicadas a um problema prático e concreto. Nossa intenção é compreender o referencial teórico e dominar ferramentas práticas que permitam que alcancemos um objetivo.</span>
</p>
<blockquote><em data-redactor-tag="em"><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">O maior valor de uma imagem se dá quando ela nos força a perceber algo que nunca esperaríamos ver. (Tukey, J W)</span></em>
</blockquote>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Quando nos propomos a construir uma visualização de dados procuramos por novas possibilidades de ver os dados, observamos padrões e exceções e investigamos histórias que podem estar escondidas atrás dos dados brutos. Um exemplo clássico que ilustra o impacto de uma visualização de dados é o <a href="https://pt.wikipedia.org/wiki/Quarteto_de_Anscombe">"Quarteto de Anscombe"</a> criado pelo estatístico Francis Anscombe em 1970. Ele desenvolveu um experimento utilizando quatro conjuntos de dados que possuíam aproximadamente as mesmas medidas estatísticas descritivas: média, variância e correlação.</span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);"><br/></span><img src="https://assets.memberkit.com.br/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBOGFQQXc9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--55f06962cfdccb049639e1377a682de828a23976/Captura%20de%20Tela%202020-06-27%20a%CC%80s%2021.02.34.png" alt data-verified="redactor"/><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);"><br/></span>
</p>
<p><img src="https://assets.memberkit.com.br/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBOENQQXc9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--bb24d626b253c81af7aaeea3e1731c02f5660366/Captura%20de%20Tela%202020-06-27%20a%CC%80s%2020.50.21.png" alt="Fonte: wikipedia" data-verified="redactor"/><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);"> </span><img src="https://assets.memberkit.com.br/rails/active_storage/blobs/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBOEdQQXc9PSIsImV4cCI6bnVsbCwicHVyIjoiYmxvYl9pZCJ9fQ==--083cd603929d555e354b43c84cb39207703af970/Captura%20de%20Tela%202020-06-27%20a%CC%80s%2020.50.14.png" alt="Fonte: wikipedia" data-verified="redactor"/><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Fonte: Wikipedia</span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">A tabela mostra as medidas descritivas praticamente idênticas, no entanto quando observamos os gráficos fica nítido que existem diferenças nos padrões dos dados.</span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">E o que aprenderemos nesse curso?</span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);">Aplicaremos a metodologia proposta por Andy Kirk com um direcionamento para a construção de uma visualização de dados. Juntos, exploraremos cada etapa, a fim de construir o conhecimento almejado. Eu elaborei um mapa mental (recurso que gosto muito e recomendo) para nos guiar nesse processo, confira abaixo.<br/></span>
</p>
<p><span style="color:rgb(0, 0, 0)" rel="color: rgb(0, 0, 0);" data-verified="redactor" data-redactor-tag="span" data-redactor-style="color: rgb(0, 0, 0);"></span>
</p>

### Leituras Recomendadas

1. [Quarteto de Anscombe - Wikipedia](https://pt.wikipedia.org/wiki/Quarteto_de_Anscombe)
2. <a href="https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/data-visualization-for-human-perception#:~:text=Data%20visualization%20is%20effective%20because,is%20extremely%20fast%20and%20efficient.">Data Visualization for Human Perception</a>
3. Capítulo 1 - O momento Sputnik da China. [Inteligência Artificial. Kai-Fu Lee](https://amzn.to/3MpAMZP).

4. Chapter 2 - The Design Visualization Process. A Handbook for Data Driven Design. Andy Kirk.

<iframe sandbox="allow-popups allow-scripts allow-modals allow-forms allow-same-origin" style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=BR&source=ss&ref=as_ss_li_til&ad_type=product_link&tracking_id=hallpaz-20&language=pt_BR&marketplace=amazon&region=BR&placement=1473912148&asins=1473912148&linkId=deb37b81497c145c3e8e86c388c25679&show_border=true&link_opens_in_new_window=true"></iframe>

### Confira abaixo o mapa mental do curso e descubra o que iremos aprender:

<iframe src="https://www.mindmeister.com/maps/public_map_shell/1548595849/metodologia-de-visualiza-o-de-dados-por-andy-kirk?width=1200&amp;height=800&amp;z=auto" style="color:rgb(18, 38, 63);font-family:&quot;Cerebri Sans&quot;, sans-serif;font-size:15px" width="1200" height="400">
</iframe>
