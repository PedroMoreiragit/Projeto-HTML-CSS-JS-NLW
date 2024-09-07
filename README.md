# Aplicação de Gerenciamento de Atividades

Esta aplicação foi desenvolvida como parte do evento **NLW Journey**, promovido pela **Rocketseat**, com o objetivo de criar uma plataforma simples para cadastro e gerenciamento de atividades diárias. O projeto utiliza tecnologias web modernas e oferece uma interface intuitiva e estilosa para o usuário. A seguir, explicamos as tecnologias utilizadas e como elas foram aplicadas no projeto.

## Tecnologias Utilizadas

### 1. **HTML5**
A estrutura da página foi construída utilizando HTML5, garantindo semântica adequada e compatibilidade com os padrões modernos de desenvolvimento web. Cada elemento foi cuidadosamente escolhido para criar uma interface acessível e de fácil navegação.

### 2. **CSS3**
O estilo visual da aplicação foi construído utilizando **CSS3**. Através de propriedades como **flexbox**, **grid**, e **media queries**, foi possível criar uma interface responsiva que se adapta a diferentes tamanhos de tela, tanto em dispositivos móveis quanto em desktops. A tipografia foi feita com a fonte **Inter**, importada do Google Fonts, proporcionando uma leitura agradável e moderna.

#### Destaques no CSS:
- Estilização de botões com transições suaves e efeitos de hover.
- Uso de cores escuras para criar uma aparência moderna e minimalista.
- Estilização responsiva, adaptando o layout em telas maiores através de *media queries*.

### 3. **JavaScript**
O comportamento dinâmico da aplicação foi desenvolvido utilizando **JavaScript**. As funções principais envolvem a manipulação do DOM, permitindo a criação de atividades dinâmicas, exibição de horários formatados e controle de estados (atividades concluídas ou não).

#### Principais Funções:
- `CriarItemDeAtividade`: Cria o HTML dinamicamente para cada atividade cadastrada.
- `AtualizarListaDeAtividades`: Atualiza a lista de atividades na tela com base no array de atividades.
- `SalvarAtividade`: Salva uma nova atividade no array e atualiza a exibição.
- `CriarDiaSelecao` e `CriarHorasSelecao`: Preenchem automaticamente os campos de data e hora disponíveis para seleção.

### 4. **Day.js**
Para manipulação de datas e horários, foi utilizada a biblioteca **Day.js**. Ela permite a formatação e exibição de datas em diferentes formatos, simplificando o processo de apresentação de informações relacionadas ao tempo, como dias da semana e horas.

### 5. **Rocketseat e NLW Journey**
Esta aplicação foi desenvolvida durante o evento **NLW Journey** da **Rocketseat**, uma plataforma brasileira focada no ensino de tecnologias modernas de desenvolvimento de software. A Rocketseat é conhecida por fornecer uma experiência de aprendizado imersiva, com desafios práticos e projetos que simulam demandas reais do mercado de trabalho. Seus eventos, como o **NLW (Next Level Week)**, são intensivos e têm como objetivo guiar os desenvolvedores por uma jornada de aprendizado acelerado.

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nlw-journey-atividades.git
