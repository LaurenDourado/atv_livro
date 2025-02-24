# 📚 *Atividade Literária*

Esta atividade acadêmica foi uma jornada criativa pelo universo dos livros! Nosso desafio consistiu em escolher um livro, trabalhar em dupla e desenvolver uma página web responsiva para promovê-lo. 🚀📖

### 🔥 Nossa Experiência

Nós realizamos todas as etapas do desenvolvimento, desde o levantamento de requisitos até a criação da página web. O objetivo foi destacar o livro escolhido pelo parceiro, apresentando seus prós e contras, tema, sinopse e informações sobre o autor, de forma criativa e atrativa! 💡✨

### 📌 Entregas Realizadas

- Levantamento de Requisitos: Criamos um documento físico (folha de sulfite) contendo uma entrevista para coletar informações relevantes.

- Wireframe de Baixa Fidelidade: Elaboramos um esboço feito à mão em folha de sulfite, representando a estrutura inicial da página web.

- Wireframe de Alta Fidelidade: Desenvolvemos o wireframe no Figma, garantindo mais detalhes sobre o layout e a usabilidade.

- Página Web Responsiva: Implementamos a página web final, garantindo a melhor experiência para o usuário em diferentes dispositivos.

### 🚀 Conclusão

Foi uma experiência enriquecedora, onde pudemos aprimorar nossas habilidades em design e desenvolvimento web. Trabalhamos em equipe para criar uma "propaganda literária" envolvente e funcional.

##  🖼️ Como vizualizar o figma

Você pode visualizar o protótpo diretamente pelo link abaixo:

https://www.figma.com/design/vd5WUqoFWG4mgz64cOeVdm/mobile?node-id=1-3&p=f&t=Xur23z7TNBKoUrfx-0

# Complementação da atividade
#### Página Web Interativa com Feedbacks Literários

Este projeto consiste em uma página web interativa que apresenta feedbacks sobre um livro, permitindo que o usuário navegue entre as avaliações através de uma animação de virada de página. O design é responsivo, adaptando-se a diferentes tamanhos de tela, e a experiência de navegação foi projetada para ser atraente e dinâmica.

## 📖 Descrição do Código

Este código HTML, CSS e JavaScript cria uma página web que simula a virada de páginas de um livro. A página exibe avaliações de um livro, com animações de transição entre as seções de feedback, permitindo que o usuário navegue de forma interativa entre os feedbacks.

### 🧩 Componentes do Código

1. **Estrutura HTML (HTML)**

   A estrutura HTML contém o conteúdo principal da página, incluindo:
   - **Título:** Nome do livro na parte superior.
   - **Feedbacks:** Três seções de feedback de leitores sobre o livro, cada uma com o nome do autor, a avaliação e uma imagem de estrela.
   - **Botões de Navegação:** Botões para navegar entre os feedbacks, representados por setas para frente e para trás.
   - **Rodapé:** Uma seção no final da página com um aviso de direitos autorais.

2. **Estilos CSS (CSS)**

   O estilo CSS é responsável pela aparência da página e inclui:
   - **Layout da Página:** A página é projetada para ter uma aparência de "livro aberto", com uma imagem de fundo que simula o visual de páginas de um livro.
   - **Animação de Virada de Página:** Uma animação 3D é aplicada para simular a virada de página, utilizando a propriedade `rotateY` para girar as seções de feedback de um lado para o outro.
   - **Responsividade:** A página é responsiva, o que significa que ela se ajusta automaticamente para se adequar a diferentes tamanhos de tela, como dispositivos móveis, tablets e desktops.
   - **Estilos dos Botões:** Os botões de navegação possuem um design simples, com uma aparência arredondada e são posicionados de forma que fiquem ao lado da página.

3. **Interatividade com JavaScript (JS)**

   O JavaScript é utilizado para permitir a navegação entre os feedbacks:
   - **Navegação entre Feedbacks:** Os botões "Anterior" e "Próximo" permitem que o usuário mude entre os feedbacks, removendo a classe `ativo` do feedback atual e aplicando-a ao próximo ou anterior. A animação de virada de página é acionada a cada mudança.
   - **Controle de Feedbacks Visíveis:** Cada feedback é oculto por padrão, e apenas o feedback ativo é exibido no momento. Isso é controlado pela adição e remoção da classe `ativo` nos elementos.

### 🎨 Estilo Visual

- **Imagem de Fundo:** A página tem uma imagem de fundo com o tema de um livro aberto. A imagem é posicionada no centro e ajustada para cobrir toda a tela.
- **Animação de Virada de Página:** Quando o usuário navega entre os feedbacks, o efeito de virada de página é aplicado, dando uma sensação de 3D. O feedback atual gira para a esquerda (com a animação `rotateY`), e o próximo feedback é exibido com a mesma animação, criando uma transição suave.
- **Texto e Estilo dos Feedbacks:** Cada seção de feedback é estilizada com uma cor de fundo personalizada (via variável CSS `--background`), texto em branco e fontes modernas. O design é limpo e claro, com boa legibilidade.
- **Responsividade:** A página ajusta seu layout dependendo do tamanho da tela, para garantir uma boa experiência de navegação em qualquer dispositivo, seja um smartphone, tablet ou desktop.

### 🖥️ Funcionalidade

- **Botões de Navegação:**
  - **Botão "Próximo":** Ao clicar, o feedback atual desaparece com uma animação de virada de página, e o próximo feedback é exibido.
  - **Botão "Anterior":** Ao clicar, o feedback atual desaparece com a mesma animação, e o feedback anterior é exibido.
  
- **Feedbacks:** Cada feedback contém o título, o texto de avaliação e o nome do autor, junto com a imagem de uma estrela.

### 📱 Responsividade

O código inclui **media queries** para garantir que a página funcione bem em diferentes dispositivos:
- **Para telas pequenas (celulares):** O layout se ajusta para garantir que o conteúdo fique legível e acessível, com os elementos ajustando seu tamanho e posição conforme necessário.
- **Para telas médias (tablets):** O design adapta-se para manter a legibilidade sem perder a funcionalidade, ajustando a largura e a disposição dos elementos.
