#Tarefa 02 - Teste de Unidade

Gabriel Lima - Lima404 - gabriel.lima.112@ufrn.edu.br

* [Backend](https://github.com/leonardobezrr/sig-estoque-back-end)
* [Frontend](https://github.com/leonardobezrr/sig-estoque-front-end)

9.
- a) Testes de software são processos essenciais no desenvolvimento de programas, assegurando que o produto final cumpra os requisitos especificados e funcione corretamente. Dentre os vários tipos de testes, os testes de unidade se destacam pela verificação de componentes individuais do código, como funções ou métodos, de forma isolada. Esses testes automatizados detectam erros e bugs precocemente no ciclo de desenvolvimento, facilitando correções rápidas. Além disso, os testes de unidade auxiliam na manutenção do código, garantindo que modificações futuras não introduzam novos problemas, e servem como documentação viva do comportamento esperado do software. Realizar testes de software eficazes é fundamental para a qualidade, confiabilidade e sucesso de qualquer aplicação.

- b) As linguagens de programação que usamos no projeto foram...

### Para Back-end

Node.js é uma plataforma que permite a execução de código JavaScript no servidor, fora do navegador, utilizando o motor V8 do Google Chrome. É conhecida por sua capacidade de lidar com operações de entrada/saída de forma não bloqueante, tornando-a ideal para aplicações que requerem alta escalabilidade e desempenho, como servidores web.

Fastify é uma biblioteca de framework web para Node.js que se destaca por sua performance e simplicidade. Projetada para ser rápida, possui uma estrutura leve que facilita o desenvolvimento de aplicações web e APIs RESTful. O funcionamento do Fastify é baseado em uma arquitetura assíncrona e event-driven, similar ao próprio Node.js, permitindo o processamento eficiente de múltiplas requisições simultâneas.

## Para front-end

Next.js é um framework de desenvolvimento web baseado em React, que permite a criação de aplicações web modernas e otimizadas, com suporte para renderização do lado do servidor (SSR) e geração de sites estáticos (SSG). Este framework, desenvolvido pela Vercel, oferece uma série de recursos que facilitam a construção de aplicações React escaláveis e de alto desempenho, como roteamento automático, suporte a APIs, e otimização de performance.

Integrar Next.js com TypeScript é uma prática comum, pois TypeScript adiciona tipagem estática ao JavaScript, ajudando a detectar erros em tempo de desenvolvimento e melhorando a manutenção do código. O Next.js possui suporte nativo para TypeScript, tornando a configuração inicial simples e direta.


- c) 

Vitest é uma ferramenta moderna de teste de software para JavaScript e TypeScript, desenvolvida com foco em simplicidade, desempenho e integração com frameworks modernos como Vite. É uma alternativa rápida e leve a outros frameworks de teste, como Jest, oferecendo uma experiência otimizada para desenvolvedores que utilizam o ecossistema Vite.

Características Principais do Vitest
Integração com Vite: Vitest é projetado para funcionar perfeitamente com Vite, um bundler e servidor de desenvolvimento rápido. Isso permite uma configuração de ambiente de teste sem complicações e um desempenho superior em comparação com outras ferramentas de teste tradicionais.

Desempenho: O Vitest é extremamente rápido, aproveitando a construção incremental e a capacidade de cache do Vite. Isso resulta em execuções de teste mais rápidas, especialmente em projetos grandes.

Suporte a JavaScript e TypeScript: Vitest suporta testes tanto para código JavaScript quanto TypeScript, oferecendo uma experiência de desenvolvimento fluida e integrada. 

Entre outros...

- d)

Vscode:

Editor Leve e Rápido: VSCode é conhecido por ser um editor leve e rápido, capaz de lidar com projetos de qualquer tamanho, desde pequenos scripts até grandes aplicações empresariais.

Suporte a Diversas Linguagens de Programação: Oferece suporte nativo a várias linguagens de programação, incluindo JavaScript, TypeScript, Python, C++, Java, entre outras. Além disso, sua extensibilidade permite adicionar suporte a praticamente qualquer linguagem através de extensões.

Extensões e Personalização: O marketplace de extensões do VSCode oferece milhares de extensões que ampliam suas funcionalidades, desde temas de interface até ferramentas de integração contínua, depuração e controle de versão. Os desenvolvedores podem personalizar o editor conforme suas necessidades específicas.

Integração com Git: VSCode possui integração nativa com Git, permitindo que os desenvolvedores realizem operações de controle de versão diretamente do editor, como commit, push, pull, e merge. Também é compatível com outras ferramentas de controle de versão através de extensões.

- e) Link de CRUD com Node + Fastify

* [Rest API com Node e Fastify](https://www.youtube.com/watch?v=E6mZSJFozvM)

- f) Mock Objects em Testes de Unidade

Mock Objects são objetos simulados que imitam o comportamento de objetos reais de forma controlada. Eles são amplamente utilizados em testes de unidade para substituir componentes externos ou dependências que são difíceis de configurar ou que tornariam os testes lentos e não determinísticos. Mocks permitem isolar a unidade de código que está sendo testada, garantindo que os testes sejam focados e confiáveis.