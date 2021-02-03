# <h1 align="center"> Padrões de Projeto </h1>
<hr/>

## <h2 align="center">DESCUBRA E APLIQUE PADRÕES </h2>

<div align="justify">
  
 ## <h2 align="center">Envio de Mensagens</h2>
 
 <p>Atualmente, aplicações de diversas plataformas como web e mobile possuem recursos de envio de mensagens por diferentes meios como: email, sms, WhatsApp, notificações push, etc. </p>
 <p>Considere que você precisará:</p>
 
     1. Trocar a forma de envio de mensagens por outra ou
     2. alternar entre diferentes formas

<p>No entanto, você não quer ficar escrevendo ifs em todos os locais onde precisa definir qual classe será instanciada para enviar mensagens e quer que o 
processo de decisão de qual classe instanciar (que define a forma de envio de mensagens) seja encapsulado.</p>

   

Responda:

1.Qual padrão de projeto pode ser utilizado para resolver este problema? Implemente a solução (não precisa enviar mensagens de fato, apenas simular com prints). 

   <p>Ao meu ver, podemos aplicar o padrão Strategy, porque em sua definição, diz: </p>

      <p> Com o padrão Strategy teremos vários algoritmos implementados e poderemos  trocar um algoritmo pelo outro  para alterar o comportamento de uma classe,
      até mesmo em tempo de execução. Tais algoritmos sendo encapsulados, quer dizer que quem for utilizá-los não precisa conhecer os detalhes específicos.</p>

   
</div>
