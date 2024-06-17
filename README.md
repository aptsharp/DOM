# DOM (Manipulação e armazenamento)

### o que é DOM
O DOM (Document Object Model) é uma interface de programação para documentos HTML e XML. Ele representa a estrutura do documento como uma árvore de objetos, onde cada objeto corresponde a uma parte do documento. O DOM permite que scripts (como JavaScript) leiam e modifiquem o conteúdo, a estrutura e o estilo do documento de forma dinâmica.

###  Para que serve?
O DOM serve para permitir que scripts interajam com o conteúdo de um documento de forma programática. Com o DOM, você pode:

* Modificar a estrutura do documento (adicionar, remover ou reordenar elementos).
* Alterar o conteúdo dos elementos (texto, HTML interno, atributos).
* Atualizar o estilo dos elementos (CSS).
* Manipular eventos (responder a cliques, movimentos do mouse, teclado, etc.).

### Onde é aplicado o DOM
O DOM é aplicado em qualquer contexto onde documentos HTML ou XML precisam ser manipulados dinamicamente. Isso inclui:

Páginas web interativas.
* Aplicações web complexas (Single Page Applications).
* Extensões de navegador.
* Ferramentas de scraping e análise de dados de documentos XML/HTML.
* Aplicações móveis híbridas que utilizam tecnologias web (como Ionic e React Native).

### Em que contexto o DOM é usado e como é usado
O DOM é usado principalmente no desenvolvimento front-end de aplicações web. Ele é utilizado para criar interfaces de usuário dinâmicas e interativas. Exemplos de uso incluem:

* Manipulação de conteúdo: Atualizar texto e HTML dentro de elementos.
* Criação de novos elementos: Adicionar novos nós ao documento.
* Manipulação de atributos: Alterar atributos de elementos existentes.
* Estilo dinâmico: Modificar estilos CSS de elementos em resposta a eventos do usuário.
* Eventos: Lidar com interações do usuário, como cliques e movimentos do mouse.

### Vantagens de usar o DOM no desenvolvimento front-end e back-end

No front-end:

* Interatividade: Permite criar interfaces de usuário dinâmicas e responsivas.
* Flexibilidade: Facilita a manipulação de documentos HTML de forma programática.
* Reatividade: Permite responder a eventos do usuário em tempo real.
* Atualizações dinâmicas: Facilita a atualização de conteúdo sem recarregar a página.

No back-end:

* Manipulação de documentos XML/HTML: Útil para parsing e manipulação de documentos em aplicações de servidor.
* Automação de tarefas: Facilita a automação de tarefas como web scraping e geração de relatórios.

### Como funciona o DOM nos navegadores de web

O DOM é implementado de forma consistente nos principais navegadores (Edge, Chrome, Firefox, Opera, Safari), o que permite que desenvolvedores criem scripts que funcionam de forma semelhante em diferentes ambientes. Cada navegador tem um motor de renderização que interpreta o HTML e constrói a árvore DOM correspondente. O motor JavaScript do navegador (como V8 no Chrome) permite que scripts interajam com essa árvore.

### Como manipular DOM em sistemas legados como IE (Internet Explorer)

Manipular o DOM em sistemas legados como o Internet Explorer pode ser desafiador devido às inconsistências e limitações de suporte. No entanto, aqui estão algumas práticas comuns:

* Compatibilidade: Usar bibliotecas como jQuery, que abstraem as diferenças entre navegadores e fornecem uma API consistente para manipulação do DOM.
* Polyfills: Utilizar polyfills para adicionar suporte a funcionalidades modernas em navegadores antigos.
* Evitar métodos modernos: Alguns métodos modernos, como querySelector e addEventListener, podem não ser totalmente suportados em versões mais antigas do IE. Utilize alternativas mais antigas, como getElementById, attachEvent, etc.
* Testes: Realizar testes extensivos em diferentes versões do IE para garantir compatibilidade.

#### 🕵🏻‍♂️Todas essas praticas ajudam com que o DOM seja manipulado de maneira mais assertiva, a manipulação do DOM tambem depende de contextos de ambientes como o uso do Edge e do IE ( legado ), tambem em sistemas legados podem ser usados o jQuery para manipulação do DOM.

#### 🧙🏻Nesse repositorio foi somente uma contetualização de como o DOM funcina e as suas peculiaridades, o assunto é bem mais extenso do que apenas os codigos que esse repositorio tem. 


-enjoy!
🫰🏻


![image](https://github.com/aptsharp/DOM/assets/6175226/0fbd3b8b-1a2d-49f5-afcc-824546e4a78d)
