# Aplicação de Gerenciamento de Atividades

## Descrição
Esta aplicação permite aos usuários cadastrar, gerenciar e concluir atividades diárias, oferecendo uma interface simples e intuitiva para organização de tarefas. O design é responsivo, adaptando-se a diferentes tamanhos de tela, com foco na usabilidade e acessibilidade.

## Tecnologias Utilizadas

### 1. **HTML**
   - **Estrutura**: O HTML é usado para estruturar os elementos da interface de usuário, como formulários, seções e botões.
   - **Formulário de Cadastro**: Um formulário permite que os usuários adicionem novas atividades com data e hora específicas.
   - **SVGs**: Ícones SVG são utilizados para melhorar a aparência visual.

### 2. **CSS**
   - **Reset de Estilo**: Todos os elementos básicos têm margens e preenchimentos zerados para garantir um layout consistente entre diferentes navegadores.
   - **Responsividade**: A aplicação usa media queries para se adaptar a dispositivos maiores (largura > 1024px), ajustando o layout.
   - **Animação**: O efeito de transição `@keyframes` é utilizado para a animação de fade-in das atividades ao serem exibidas.
   - **Foco Interativo**: Os campos de entrada de texto têm um estilo de borda personalizada quando estão em foco, destacando a interação do usuário.
   - **Botões com Feedback Visual**: Botões têm efeito de sombra ao passar o mouse, melhorando a interação e oferecendo feedback visual.

### 3. **JavaScript**
   - **Manipulação de DOM**: O JavaScript é utilizado para manipular elementos da página, atualizando a lista de atividades dinamicamente.
   - **Formatação de Data**: A biblioteca `dayjs` é usada para formatação de datas e horários, garantindo consistência nos formatos exibidos.
   - **Validação de Atividades**: O código verifica se há conflitos de datas e horários ao adicionar novas atividades.
   - **Conclusão de Atividades**: O estado das atividades (finalizada ou não) pode ser alterado por meio de uma checkbox associada a cada uma delas.

### 4. **Bibliotecas Externas**
   - **Google Fonts**: A aplicação utiliza a fonte 'Inter', que é carregada via Google Fonts.
   - **Day.js**: A biblioteca `dayjs` é usada para formatação e manipulação de datas, sendo crucial para exibir as atividades em diferentes formatos (por exemplo, dia da semana, dia do mês e hora).
   - **CDN**: Tanto a biblioteca `dayjs` quanto o suporte a localização em português brasileiro são carregados diretamente de um CDN (Content Delivery Network).

## Funcionalidades

### 1. **Cadastro de Atividades**
   - Os usuários podem cadastrar uma atividade, definindo um nome, data e hora. O sistema previne conflitos
