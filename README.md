# Cinema

## Instruções para criação do projeto

1. Crie um projeto chamado **cinema**.

2. Crie um arquivo **index.html**.

   2.1 O título do arquivo e o título de nível 1 devem conter o nome do projeto.

3. Crie um diretório dentro do projeto com o nome **estados**.

4. Dentro do diretório **estados**, crie dois arquivos: **rj.html** e **sp.html**.

   4.1 Adicione um link em cada arquivo que leve para o início do site (página inicial).

   4.2 Adicione um título de nível 1 com o nome do estado (Rio de Janeiro ou São Paulo).

   4.3 Adicione os seguintes parágrafos (cada filme é um parágrafo):
   
   - **(Rio de Janeiro):**
     - *Lisbela e o Prisioneiro* - 20:00 Hoje
     - *Meu Nome Não é Johnny* - 21:00 Hoje
     - *O Cheiro do Ralo* - 15:00 Amanhã
     
   - **(São Paulo):**
     - *Lisbela e o Prisioneiro* - 20:00 Hoje
     - *Meu Nome Não é Johnny* - 21:00 Amanhã
     - *O Cheiro do Ralo* - 15:00 Amanhã

5. Na página inicial, crie um link para cada cidade (RJ e SP).

   5.1 O link deve estar dentro de um título de nível 2.

6. Crie um arquivo de estilo CSS dentro de um diretório chamado **css**.

   6.1 Faça o link do arquivo CSS em todas as páginas do site.

   6.2 Altere a cor dos filmes que estreiam **hoje** para `darkred`.

   6.3 Altere a cor dos filmes que estreiam **amanhã** para `darkblue`.

   6.4 Remova o sublinhado de todos os links do site.

   6.5 Mude a cor dos links que estão dentro de títulos de nível 2 para `seagreen`.

   6.6 Aumente o tamanho da fonte dos parágrafos para `20px`.

   6.7 Altere a família da fonte de todo o site para **Arial**.

---

# Introdução CSS
**• Modelo de caixa (box model).**  

**• Content (Conteúdo)** 

**• Padding (Preenchimento)** 

**• Border (Borda)**

**• Margin (Margem)**
---
# Box Model

O **Box Model** é um conceito central no CSS que define como os elementos de uma página web são estruturados e exibidos. Cada elemento HTML é representado como uma caixa retangular composta por quatro partes principais:

1. **Content** (Conteúdo): A área onde o conteúdo real do elemento (como texto ou imagem) é exibido.
2. **Padding** (Preenchimento): Espaço entre o conteúdo e a borda do elemento. Ele é transparente e aumenta o tamanho da caixa.
3. **Border** (Borda): Uma linha que circunda o padding e o conteúdo. Pode ter espessura, estilo e cor diferentes.
4. **Margin** (Margem): Espaço externo entre a borda do elemento e outros elementos da página. A margem pode ser usada para afastar ou alinhar elementos.

## Funcionalidades

- **Controlar espaçamento**: Através de `padding` e `margin`, o Box Model permite ajustar o espaçamento interno e externo dos elementos.
- **Personalização visual**: Com `border`, é possível estilizar a aparência da caixa, dando efeitos visuais como contornos ou divisões.
- **Layout responsivo**: Manipulando o Box Model, você pode ajustar como os elementos se comportam em diferentes tamanhos de tela.

Essas funcionalidades são fundamentais para criar layouts flexíveis e bem-organizados em páginas web.


---
## Content (Conteúdo)

O **Conteúdo** é a parte central do Box Model e representa a área onde o texto, imagens e outros elementos são exibidos. Esta é a parte mais importante da caixa, pois é onde reside a informação que o usuário vê e interage.

### Características do Conteúdo

- **Tamanho**: O tamanho do conteúdo pode ser definido utilizando as propriedades de largura (`width`) e altura (`height`). O tamanho pode ser ajustado em pixels, porcentagens ou unidades relativas, como `em` e `rem`.

- **Texto e Imagens**: O conteúdo pode incluir qualquer tipo de dado, como texto, imagens, vídeos, links, listas e muito mais. Cada tipo de conteúdo pode ter suas próprias propriedades CSS que influenciam sua aparência.

- **Estilo**: As propriedades CSS como `font-size`, `color`, `text-align` e `line-height` podem ser aplicadas para estilizar o texto dentro do conteúdo, enquanto outras propriedades, como `background-color`, podem ser usadas para mudar a aparência do fundo do conteúdo.

### Importância do Conteúdo

- **Experiência do Usuário**: O conteúdo é crucial para a experiência do usuário, pois fornece a informação necessária de forma clara e organizada.

- **Interatividade**: O conteúdo pode incluir elementos interativos, como botões e links, que incentivam a interação do usuário com a página.

- **SEO (Otimização para Motores de Busca)**: O conteúdo relevante e bem estruturado também é fundamental para o SEO, ajudando a aumentar a visibilidade da página nos resultados de busca.

Entender como gerenciar e estilizar o conteúdo no Box Model é essencial para criar páginas web eficazes e atraentes.
---
## Padding (Preenchimento)

O **Padding** é a área entre o conteúdo da caixa e sua borda. Ele serve para criar espaço interno ao redor do conteúdo, ajudando a melhorar a legibilidade e a estética do layout.

### Características do Padding

- **Espaçamento Interno**: O padding adiciona espaço dentro da caixa, entre o conteúdo e a borda. Isso impede que o conteúdo fique muito próximo das bordas, tornando a visualização mais agradável.

- **Propriedades**: O padding pode ser definido usando as propriedades `padding-top`, `padding-right`, `padding-bottom` e `padding-left`, ou uma única propriedade `padding` para aplicar o mesmo valor a todos os lados. Os valores podem ser especificados em pixels, porcentagens ou unidades relativas.

- **Impacto no Tamanho da Caixa**: O padding aumenta o tamanho total da caixa, já que é adicionado à largura e altura do elemento. Isso deve ser considerado ao definir o layout da página.

### Importância do Padding

- **Legibilidade**: Um padding adequado melhora a legibilidade do conteúdo, separando visualmente o texto e outros elementos das bordas da caixa.

- **Estética**: Um bom uso do padding pode contribuir para uma apresentação mais harmoniosa e equilibrada da página, tornando-a visualmente mais atraente.

- **Interatividade**: Em elementos interativos, como botões, o padding pode aumentar a área clicável, facilitando a interação do usuário.

Compreender como usar o padding corretamente é fundamental para o design de páginas web eficazes e agradáveis.
---
## Border (Borda)

A **Border** é a linha que envolve a caixa de um elemento, delimitando sua área visualmente. Ela pode ser utilizada para destacar elementos na página, separar conteúdos e melhorar a estrutura visual do layout.

### Características da Border

- **Estilos de Borda**: As bordas podem ser personalizadas em termos de estilo (`solid`, `dashed`, `dotted`, `double`, etc.), largura (em pixels ou unidades relativas) e cor. Essas propriedades permitem uma ampla gama de personalizações visuais.

- **Propriedades**: As bordas podem ser definidas usando as propriedades `border`, `border-width`, `border-style`, e `border-color`. Também é possível aplicar bordas diferentes para cada lado da caixa usando `border-top`, `border-right`, `border-bottom`, e `border-left`.

- **Raio da Borda**: O `border-radius` é uma propriedade que permite arredondar os cantos da borda, criando uma aparência mais suave e moderna.

### Importância da Border

- **Destaque**: Bordas podem ser usadas para chamar a atenção para elementos específicos, como botões, caixas de texto ou seções importantes da página.

- **Separação de Conteúdo**: Bordas ajudam a separar diferentes áreas de conteúdo, facilitando a leitura e a navegação pelo site.

- **Estética**: A escolha correta de bordas pode contribuir para a identidade visual de um site, alinhando-se com a marca e o estilo desejado.

Compreender o uso de bordas é essencial para criar layouts organizados e visualmente atraentes em páginas web.
---
## Margin (Margem)

A **Margin** é a área em branco que envolve a caixa de um elemento, separando-o de outros elementos na página. As margens são fundamentais para controlar o espaçamento entre os elementos, ajudando a criar um layout organizado e visualmente agradável.

### Características da Margin

- **Espaçamento Externo**: As margens criam espaço fora da borda de um elemento, permitindo que os elementos fiquem afastados uns dos outros. Isso é útil para evitar que o conteúdo fique muito próximo, melhorando a legibilidade.

- **Propriedades**: As margens podem ser definidas usando a propriedade `margin`, que pode aceitar valores para todos os lados (`margin: 10px;`), ou valores individuais para cada lado (`margin-top`, `margin-right`, `margin-bottom`, `margin-left`). Também é possível usar valores automáticos para centralizar elementos (`margin: auto;`).

- **Colapso de Margens**: Em alguns casos, as margens de elementos adjacentes podem se "colapsar", resultando em um espaço menor do que o esperado. Compreender esse comportamento é importante para evitar surpresas no layout.

### Importância da Margin

- **Layout**: As margens ajudam a estruturar o layout de uma página, permitindo que elementos sejam posicionados de forma equilibrada e harmoniosa.

- **Espaçamento Consistente**: O uso adequado de margens garante que o espaçamento entre elementos seja consistente em toda a página, melhorando a estética geral.

- **Acessibilidade**: Um layout bem espaçado é mais acessível, pois facilita a navegação e a interação com os elementos da página.

Compreender o uso de margens é essencial para criar layouts claros e organizados, melhorando a experiência do usuário em páginas web.

---
## Favicons
Usei o site para os icones das páginas 
https://www.favicon.cc/

---
### Alguns comandos que aprendi :

O comando `text-decoration: none;` em CSS é usado para remover qualquer decoração aplicada ao texto, como sublinhados, sobrelinhados ou linhas de corte.