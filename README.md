<img src="https://camo.githubusercontent.com/0a35fb0a0add717a1556200218530580cca84bfd7a0e8c3f5c28fc72e02cd3fb/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732d6e65772e706e67" styles="text-align: center; margin-bottom: 32px;" />

<h1 class="title" styles="border: none; text-align: center; margin-bottom: 32px; font-weight: bold;">
  Desafio 09: Relacionamentos com banco de dados no Node.js
</h1>

<div styles="text-align: justify;">
<h1 styles="font-weight: 500;">Sobre o desafio</h1>

<p>O foco desse desafio é treinar nossas habilidades com banco de dados, principalmente os relacionamentos.</p>

<p>Nesse desafio, você vai estar criando uma nova aplicação para aprender novas coisas e treinar o que você aprendeu até agora no Node.js junto ao TypeScript, incluindo o uso de banco de dados com o TypeORM, e relacionamentos ManyToMany!</p>

<p>Essa será uma aplicação que deve permitir a criação de clientes, produtos e pedidos, onde o cliente pode gerar novos pedidos de compra de certos produtos, como um pequeno e-commerce.</p>

<h1 styles="font-weight: 500;">Rotas da aplicação</h1>
<ul>
  <li>
    <strong>POST /customers :</strong> Rota para criar um novo cliente, a rota deve receber no corpo da requisição o
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">name</span> e
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">email</span>
  </li>

  <li>
    <strong>POST /products :</strong> Rota para criar um novo produto, a rota deve receber no corpo da requisição o
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">name</span>,
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">price</span> e
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">quantity</span>
  </li>

  <li>
    <strong>POST /orders :</strong> Rota para criar um novo pedido, a rota deve receber no corpo da requisição o
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">customer_id</span> e um array de products, contendo o
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">id</span> e a
    <span styles="padding: 4px 8px; border-radius: 8px; background-color: rgba(0, 0, 0, .3);" class="label">quantity</span>
  </li>

  <li>
    <strong>GET /orders/:id :</strong> Essa rota deve retornar as informações de um pedido específico.
  </li>
</ul>
<footer styles="border-top: 4px solid rgba(255,255,255, .2); margin-top: 20px; padding-top: 20px;">
  <h3> Feito com 💜 by Matheus Lucas 👋🏾 </h3>
</footer>
</div>
