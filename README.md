Projeto de Linguagem de Marcação

Alanis Venerruche de Carvalho

Este documento de Especificação de Requisitos de Software e Planejamento descreve o planejamento e a estrutura base para o desenvolvimento de um site de notícias “O Informativo”, tal nome foi decidido e aprovado para a representação do site. Ele define de forma detalhada as funcionalidades esperadas. Além disso, abrange requisitos funcionais e não funcionais, restrições de design e critérios de desempenho, com o objetivo de garantir que o sistema atenda às necessidades dos usuários e seja seguro, eficiente e escalável. A SRS serve como base para o desenvolvimento e alinhamento de expectativas entre todas as partes envolvidas no projeto. 

1.1	Finalidade:
A finalidade é fornecer uma descrição detalhada e clara do comportamento do site desenvolvido e suas principais expectativas, abordando todas as funcionalidades e interações esperadas pelos usuários, como o acesso à página inicial, conteúdo de cada notícia, formulário para contato, menu de navegação, entre outros. Este documento visa definir, de forma precisa, tanto os requisitos funcionais quanto os não funcionais, garantindo que o site atenda às necessidades dos usuários. O objetivo é oferecer uma visão abrangente dos requisitos, assegurando que todos os aspectos técnicos e operacionais do software sejam atendidos, proporcionando uma solução eficiente, segura e escalável.

1.2	Escopo:
O site do portal de notícias possuí diversas expectativas iniciais, dentre elas, o desenvolvimento de uma página inicial, contendo um grid de notícias principais, com imagens, título e breve resumo do conteúdo, menu de pesquisas, para que os usuários possam pesquisa notícias por palavras chaves. Além disso, cada notícia deve poder ser acessada, onde cada uma terá seu próprio conteúdo abordado.

2 Descrição Geral:
O portal de notícias a ser desenvolvido tem como função principal apresentar notícias para a população, garantindo credibilidade e confiabilidade para seus usuários.
• Perspectiva do Produto: 

O website serve como o principal front-end digital da empresa. Seu propósito fundamental é atuar como uma plataforma de notícias, reforçando a credibilidade da marca e servindo como um ponto eficiente de entrega de notícias.

O site se concentra em passar confiança para seus usuários, garantindo a eles notícias seguras e de qualidade, além de garantir sua acessibilidade para todos.
• Funções do Produto: 
1.	Assegurar que os usuários possam se mover facilmente entre as seções principais e acessar informações legais (Política de Privacidade, Termos de Uso) através de menus consistentes.
2.	Apresentar a identidade e a missão do site O Informativo de forma visualmente atraente, utilizando uma logo que passe confiabilidade para seus usuários.
3.	Apresentar um grid de notícias principais, que deveram ser corretamente acessadas.
4.	Oferecer aos usuários acesso a artigos informativos, organizados em cartões visuais, e fornecer um mecanismo de busca para filtrar o conteúdo por interesses.
5.	Fornecer um canal direto para que os visitantes entrem em contato com o site, por meio de um formulário e pela exibição de sua localização física via mapa.
• Restrições: 
O desenvolvimento do aplicativo estará sujeito a restrições como a necessidade de conformidade com regulamentos legais, incluindo as leis de proteção de dados (como a LGPD), requisitos de segurança. Além disso, o sistema deve ser escalável para permitir o crescimento da empresa e ser acessível por dispositivos móveis e desktop. 
3.	Requisitos Específicos 
São aqueles que descrevem as funcionalidades específicas que o sistema deve oferecer para que ele cumpra seu objetivo e atenda às necessidades dos usuários.  Esses requisitos estão diretamente relacionados à operação do sistema e definem o comportamento esperado do software sob diversas condições e situações de uso. Eles especificam o que o sistema deve fazer, descrevendo as interações entre os usuários e o sistema, bem como os processos que o sistema deve executar para alcançar os resultados desejados. Cada requisito funcional deve ser claro, preciso e mensurável, de modo que possa ser verificado através de testes ou análises para garantir que o sistema os atenda de forma adequada. Esses requisitos servem para garantir que o produto seja capaz de realizar todas as operações necessárias para resolver o problema ou atender à demanda dos usuários, mantendo a eficiência e a usabilidade no processo. 

3.1	Requisitos Funcionais
São aqueles que descrevem as funcionalidades específicas que o sistema deve oferecer para que ele cumpra seu objetivo e atenda às necessidades dos usuários.  Esses requisitos estão diretamente relacionados à operação do sistema e definem o comportamento esperado do software sob diversas condições e situações de uso. Eles especificam o que o sistema deve fazer, descrevendo as interações entre os usuários e o sistema, bem como os processos que o sistema deve executar para alcançar os resultados desejados. Cada requisito funcional deve ser claro, preciso e mensurável, de modo que possa ser verificado através de testes ou análises para garantir que o sistema os atenda de forma adequada. Esses requisitos servem para garantir que o produto seja capaz de realizar todas as operações necessárias para resolver o problema ou atender à demanda dos usuários, mantendo a eficiência e a usabilidade no processo. 

3.1.1	Listagem de Requisitos

•	RF01 - Apresentação do Conteúdo (Grid): O sistema deve exibir na Página Inicial um grid (layout em grade) com prévias das notícias (título, imagem e resumo curto).

•	RF02 - Visualização da Notícia IndividualO sistema deve permitir que o usuário clique em uma prévia do grid e seja direcionado para a Página de Notícia Individual.

•	RF03 - Exibição do Conteúdo Completo: A Página de Notícia Individual deve exibir o conteúdo completo da notícia, incluindo título, corpo do texto, imagem principal e, se houver, galeria de mídia.

•	RF04 - Acesso por Assunto/Categoria: O sistema deve garantir que cada notícia seja acessada corretamente e contenha a informação de seu respectivo assunto/categoria.

•	RF05 - Galeria de Mídia (Imagens/Vídeos): O sistema deve ser capaz de exibir uma Galeria de Imagens e/ou Vídeos associada ao conteúdo na Página de Notícia Individual.

•	RF06 - Funcionalidade da Newsletter: O sistema deve exibir um Formulário de Newsletter que permita ao usuário cadastrar seu email para receber atualizações.

•	RF07 - Funcionalidade de Contato: O sistema deve exibir um Formulário de Contato que permita ao usuário enviar uma mensagem ou feedback para a equipe do portal.

•	RF08- Barra de Pesquisa (Visual): O sistema deve exibir uma Barra de Pesquisa na Página Inicial, mas não precisa ser funcional nesta etapa inicial.

•	RF09 (Rodapé): O rodapé deve incluir links para "Política de Privacidade" e "Termos de Uso".


3.2	Requisitos Não Funcionais:

•	RNF01 (Responsividade): O site deve ser totalmente responsivo (abordagem Mobile First), garantindo que o layout se adapte perfeitamente a qualquer tamanho de tela (celulares, tablets e desktops).

•	RNF02 (Desempenho): As páginas devem ser otimizadas para um carregamento rápido, com um tempo alvo de LCP (Largest Contentful Paint) abaixo de 3 segundos em redes móveis.

•	RNF03 (Segurança): O formulário de contato deve ser protegido contra injeção de código e deve-se utilizar o protocolo HTTPS para comunicação segura.

•	RNF04 (Padrões): O código deve seguir estritamente as melhores práticas e padrões do HTML5 e CSS, utilizando a semântica correta.

•	RNF05 (Localização): Todo o conteúdo deve ser apresentado em português do Brasil.

•	RNF06 (Manutenibilidade): O CSS deve ser gerenciado em arquivos externos separados (style.css, blog-style.css, etc.) para garantir a modularidade e facilitar a manutenção.

•	RNF07 (Adesão de Marca - Paleta de Cores): O design visual deve seguir rigorosamente a paleta de cores institucional definida pela EcoLife, garantindo a consistência da marca em todos os elementos.

•	RNF08 - Design Profissional Usabilidade/Design :O layout do portal deve ser limpo, moderno e profissional, transmitindo credibilidade, conforme o padrão de um site de notícias.

•	RNF09 - Usabilidade da Navegação: O Menu de Navegação deve ser intuitivo, fácil de usar e consistente em todas as páginas do site.

•	RNF10 - Tempo de Carregamento: As páginas do portal (Página Inicial e Notícia Individual) devem ter um tempo de carregamento rápido (idealmente abaixo de 3 segundos) para garantir uma boa experiência ao usuário.
