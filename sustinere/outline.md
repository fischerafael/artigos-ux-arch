# Título:Arquitetura e Emoções: Um Modelo para a Avaliação de Experiências Arquitetônicas

## Resumo (200-250 palavras)

### Palavras: 200 palavras

### Frases-guia:

- "A experiência arquitetônica é uma interação sensorial e emocional entre usuários e espaços construídos, fundamental para a percepção e o design de qualidade."​
- "Este trabalho adapta o modelo circumplexo, transpondo-o para uma métrica linear que mede experiências emocionais de forma objetiva."​
- "Utilizando Design Science Research, desenvolvemos e testamos essa métrica, embarcando-a em uma ferramenta chamada UX Arch para permitir avaliações baseadas em imagens."​
- "Os resultados destacam a aplicabilidade da métrica na avaliação comparativa de diferentes espaços e seu potencial para treinar modelos de inteligência artificial."​
- "Apesar das limitações, a ferramenta é um avanço na tradução de percepções subjetivas em métricas quantitativas para uso prático em arquitetura."​

## Introdução (600-700 palavras)

### Palavras: ~600 palavras

### Frases-guia:

O que é experiência arquitetônica:

- "A experiência arquitetônica refere-se à interação emocional e sensorial que os usuários têm com o espaço, incluindo luz, materiais, texturas, sons e formas."​
- "Ela transcende aspectos funcionais e estéticos, englobando emoções e percepções subjetivas que podem impactar comportamentos."​
  Importância da experiência arquitetônica:
- "A experiência arquitetônica tem implicações diretas na saúde, no bem-estar e na produtividade dos usuários."​
  "Projetos que intencionalmente consideram essas experiências criam espaços mais agradáveis, eficientes e memoráveis."​

Foco do artigo:

- "Apesar de sua importância, a avaliação de experiências arquitetônicas ainda carece de métodos objetivos que possam traduzir o subjetivo em mensurável."​
- "Este trabalho adapta o modelo circumplexo, originalmente usado para categorizar emoções humanas, para avaliar experiências arquitetônicas de forma linear e prática."​

Objetivo:

- "Propor, testar e validar uma métrica para mensuração de experiências arquitetônicas, com aplicação em imagens e embarque no UX Arch."​

## Metodologia / Material e Métodos (700-800 palavras)

### Palavras: ~700 palavras

### Frases-guia:

- Uso da Design Science Research - excelente para se propor, criar e avaliar artefatos artificiais inéditos - como uma métrica para mensurar experiências arquitetônicas

Explicação das etapas da DSR:

- Etapas - "A pesquisa seguiu a abordagem Design Science Research, estruturada em etapas iterativas: conscientização, sugestão, desenvolvimento, avaliação e conclusão."​​
- Conscientização - "Durante a etapa de conscientização, foram revisados conceitos como experiência arquitetônica, o modelo circumplexo e métodos de avaliação emocional."​
- Sugestão - "Na sugestão, foi idealizado o artefato como uma adaptação linear do modelo circumplexo para medir experiências arquitetônicas."​
- Desenvolvimento - "A etapa de desenvolvimento envolveu a criação da métrica e sua integração ao UX Arch."​
- Avaliação - "Na avaliação, realizamos um experimento prático para validar o artefato, testando sua capacidade de medir e comparar experiências de diferentes espaços."​

Experimento prático para avaliar a eficácia e eficiência do artefato projetado:

- Realizado com grupo de estudantes da UFPR (com autorização do conselho de ética).
- O artefato foi embutido em um sistema online desenvolvido pelo autor da tese, chamado UX Arch
- Brevemente, o UX Arch é um app baseado em inteligência artificial que permite que um algoritmo de AI seja treinado com variáveis objetivas para se criar um espaço arquitetônico - input - (componentes arquitetônicas) e variáveis subjetivas - output - (experiências geradas pela manipulação dessas componentes)
- Desta forma, a métrica seria fundamental para viabilizar seu desenvolvimento, pois seria responsável por fornecer para o algoritmo valores da experiência arquitetônica de diferentes espaços.
- A ideia é que usuários reais avaliariam a experiência de referências de projetos existentes, os arquitetos poderiam então avaliar as componentes desses projetos, e assim a AI teria dados de treinamento que permitiriam a previsão de experiências inéditas com base na manipulação das componentes arquitetônicas - ainda em etapa de projeto
- Ou seja, é como se o algoritmo de AI passasse a 'pensar' a experiência arquitetônica como os usuários que foram usado para treino, encurtando o feedback loop que naturalmente acontece no processo de projeto - o que poderia facilitar a concepção intencional de experiências arquitetônicas por parte de arquitetos, especialmente os mais inexperientes
- Nesse experimento, estudantes do terceiro ano de arquitetura utilizaram a UI (interface) do Ux Arch junto a usuários de um exercício de projeto para avaliar as experiências de referências de projeto que eles mesmos cadastraram. Esses dados subjetivos (experiência arquitetônica) e os objetivos (componentes arquitetônicas) foram usados para treinar o modelo, e assim poder prever experiência de projetos inéditos.
- Ao final, foi comparado o resultado previsto pela IA e a avaliação da experiência de projetos inéditos por parte dos usuários, para aferir a eficácia do software.
- Nesse contexto, o artefato - métrica de avaliação de experiência arquitetônica - foi avaliado qualitativamente pelos estudantes que utilizaram o software - eles forneceram feedback sobre as impressões que tiveram ao pedir para os usuários utilizarem a escala para avaliar experiências - bem como com base na interação constante com essa métrica, que era a forma com que eles podiam observar a experiência arquitetônica prevista pelo algoritmo.

## Resultados (700-800 palavras)

### Palavras: ~700 palavras

### Frases-guia:

Descrição do artefato:

- "O artefato converte o modelo circumplexo bidimensional em um formato linear, organizando emoções em uma escala de alta intensidade negativa, indo para neutra e, no lado oposto, indo em direção a alta intensidade positiva".
- A métrica foi dividida em 8 categorias (indo do mais intenso negativo para o neutro - ao centro - e para o mais intenso positivo no final):
  -- #tenso #nervoso
  -- #estressado #irritado
  -- #triste #deprimido
  -- #letárgico #fatigado
  -- #calmo #relaxado
  -- #sereno #contente
  -- #feliz #alegre
  -- #excitado #eufório

- "A métrica utilizou emojis para representar os pares de emoções. A ideia era facilitar ao máximo o processo de escolha e avaliação por parte dos usuários, sem perder a granularidade e especifidade das experiências."​

Uso no UX Arch:

- "A métrica foi embarcada no UX Arch, um software desenvolvido para avaliar e projetar experiências arquitetônicas de forma iterativa."​​
- "No UX Arch, a métrica permitiu avaliar via imagem as experiências arquitetônicas de espaços de referência de projeto, que depois serviram para treinamento da IA, conforme descrito no método"
- Também serviu para fornecer aos participantes do experimento o feedback da experiência arquitetônica predita pelo modelo de UI, na meidda em que eles alteravam as componentes arquitetônicas.
- E serviu também, finalmente, para permitir a comparação entre a experiência predita vs experiência de fato percebida pelos usuários, servindo como uma métrica de comparação capaz de demonstrar a eficácia do software.​

Feedback dos usuários:

- "Participantes relataram que a métrica trouxe clareza e praticidade ao processo de avaliação, embora destacassem a dificuldade em representar emoções extremamente subjetivas."​

Capacidade de comparação e aprendizado:

- "A métrica possibilitou comparar experiências de diferentes espaços, gerando dados que podem ser usados para treinar a IA do UX Arch."​

## Discussão / Análise dos Dados (600-700 palavras)

### Palavras: ~600 palavras

### Frases-guia:

Impacto da métrica:

- "A métrica linear transformou a subjetividade das emoções em um formato objetivo, útil para designers e pesquisadores."​

Limitações:

- "Embora prática, a métrica não captura nuances de sensações físicas, como temperatura e som, e é dependente da qualidade das imagens utilizadas."​

Relevância para a arquitetura:

- "O artefato propõe uma ponte entre subjetividade e mensuração objetiva, essencial para criar experiências arquitetônicas intencionais."​

## Conclusões (300-400 palavras)

### Palavras: ~300 palavras

### Frases-guia:

Resumo das contribuições:

- "O trabalho adaptou o modelo circumplexo para uma métrica linear, prática e eficaz para avaliar experiências arquitetônicas."​

Impacto e aplicabilidade:

- "A métrica embarcada no UX Arch pode melhorar o planejamento de projetos e criar um banco de dados para aprendizado de IA."​

Perspectivas futuras:

- "Pesquisas futuras podem explorar sua aplicação em experiências multissensoriais e escalas maiores, como urbanismo e planejamento urbano."​
