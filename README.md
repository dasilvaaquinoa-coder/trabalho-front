             
»««««««««««««»»»»»»»»»»»»  Desafio Card ««««««««««««««««««««««««««


             Criar um card de resumo de pedido contendo resposividade e focado no disgn no css.

»»»»»»»»»»»»»             descrição do que foi feito a montagem do card       «««««««


»»»»»»»»»»»»»»»»»»»»»       Html ««««««««««««««««««««««««««««««««««««««

Para começar a construção do card comecei com html  colocando o ! DOCTYPE html declarando o tipo de documento no inicio , depois colocando a "tag lang" para colocar o idioma que vai ser exibido no card, antes de começar o corpo linkar o arquivo do css para aparecer as modificaçoes no card usando a 
"tag link" dentro do " head".
Depois coloca a "tag tittler" para colocar um o titulo no card , e colocado a " tag body " que e o corpo do html coloquei um "main class " declarando a classe que ia ser colocada no corpo do card , em seguida foi posto o " div class" que declara a classe da iamgem que vai ficar no top do box , usando a o "img" para linkar a imagem e a pasta onde esta localizada.
Em seguida foi posto o "div class card-content" para estruturar o texto que vai ser posto no card , dentro desta tag foi colocado  o " H1" para se montado o cabeçalho do conteudo defindo a hierarquia semantica sendo o titulo principal do texto, em baixo foi posto a tag"p"  para motar o paragrafo onde vai ser descrito todo o conteudo do texto , depois foi aberto outra classe de css para ser estilizado a parte do preço , dentro desta classe foi colocado o a "h2" e " p" , e um segundo titulo que utilizado na parte principal do conteudo do texto  contedo a imagem ilustrativa de incone de musica onde se localiza a parte do plano anual e o reço do produto.
Terminado a parte do conteudo , foi para montagem do botões de acesso como o change , e os principais do card onde foi utilizado a tag "button" para motar a estrutura do botão que vai ser motado e estilizado no css. 


»»»»»»»»»»»»»»»»»»»»»»»»»»»»     CSS «««««««««««««««««««««««««

O css e utilizado para fazer toda a estilizaçao da estrutura do site deixando mais bonito e funcinal para o usuario , no css foi utilizado no começo as tags" margin , padding , box-sizing" para tratar as magens do card garantindo que todo o conteudo não passe dos lados fique certinho dentro do card.

Em seguida foi para estilização do corpo do card, abrindo  a tag "body" dentro desta tag foi colocado o "display" para fazer o alinhamento dos elementos filhos , o "justify-content " que usado no css para centralizar os elementos filho no card assim como "align-items", o height foi colocado para definir a altura minima do corpo do conteudo, ja o background foi utilizado para dar uma cor para o fundo atraz da estrutura do card, e o font- family e para motificar a letra que vai ser usada no texto o tipo de fonte para deixar mais bonita .

Nesta parte do css foi colocada essa tag para fazer a estilzação de toda a parte do conteudo em questao o "texto" dentro da caixa do card, onde doi utilizado tags para fazer o alinhamento do texto, para dar uma cor para o texto , o tamanho da fonte foi utilizado uma tamanho menor que o normal, e um tipo de fonte para deixar em negrito mais "grosso", foi usado na " plan- details " para modificar o H2 e o seu paragrafo. (text-align , color , font-size , font- weight , margin-top , font- family).

E foi para parte das informaçoes que são colocada  layout no corpo do texto , mechendo no alinhamento  usando "align-items", o display "flex" para colocar o plano anual e o preço e o icone de musica  um do lado do outro  para ficar mais uniforme dentro do card e tambem foi criado um espaço entre cada item filho dentro do card usando o gap, ja na  cor  foi usado para destacar essa parte no card foi utilizado color "hsl" no titulo  e um fonte padrão de texto. Na parte " plan-box" , usei a tag background-color para colocar uma leve cor azulada com um pouco de transparencia no fundo , o justify-content , para empurrar as informações para o lado ,  usando tag para fazer o espaçamento interno do texto , e tambem foi utilizado o border-radius para fazer o arredondamento dos cantos da caixa do card e o width  para que o conteudo ocupe todo o espaço disponivel do conteiner pai e um margin- bottom para afastar o conteudo do meio do card do botão principal. 

ja na estrutura e no conteudo do  card foi utilizado na estilização no "card-body"  a tags (color, font-size, line- heitght, margin-bottom), para fazer as modificação na cor do texto para dar destaque tambem foi criado um espaçamento entre as linhas do texto e tamanho da fonte e o espaçamento entre o texto e o botão, ja no " card- content" e " card-contant h1" foi mechido no espaçamento e alinahmento do texto centralizando na caixa do card  foi usado o display "flex" para modificar mais facil o conteudo , e para deixar o conteudo empilhilhado um embaixo do outro usei a tag "flex-direction". 

Na tag "card" foi utilizado tag para o empilhamento dos filhos verticalmete , e para fazer o ajuste da largura e altura do card como "width e height" , colocar cor "branca" no fundo caixa e usei o "border-radius" para fazer o arredondamento das bordas deixando com o aspecto mais arredondado e bonito , para fazer tipo um sobreamento embaixo do card utilizei o "box-shadow" no css , para que o card tenha um tipo de animação utilizei a "transition" uma leve mudança e o "overflow" para o conteudo que passe dos limites estabelecido no card não fique amostra .

Nas imagem que foi utilizada na parte de cima do card fazendo que ela não utrapassace o limite do card não estorace , para fazer o ajuste tanto na altura como na largura da imagem e fazendo com que a imagem ocupace 100% da altura e largura da caixa pai , e tambem fazendo o arredondamento das borda da imagem para igualar com a bordas estabelecida da caixa do card , e fazendo com que preencha sem fazer a distorção da imagem cortando o excesso.(width , height , object- fit , boder-top-left-radius , border-top-right-radius).

Nesta parte foi feio para deixar o conteiner  flutuante na parte inferir  do card e alterações na parte dos botões para fixar no rodapé do cartão pai alinhando os cantos no limite da caixa, mechendo na largura e na cor também , como a cor do fundo azul- escuro no botão usando a sintaxe de gradiente , uniformisando as cores usadas, e usei a tag "padding" na parte do espaçamento interno em todas as direções paea expandir a área clique no formato ao botão.(.card.read-more, .card.card-content).

E para finalizar foi estilizados os botões "Proceed to Paymen" e "Cancel Order" montado a estrutura e responsividade , primeiro comecei montando a estrutura usando  a tag button no css estilzando o espaçamento , fazendo o arredondamento dos cantos deixando com aspecto mais bonito e tambem colocando o efeito da mãozinha ao passar por cima do botão quando o usuario mecher o mause com "cursor:pointer"