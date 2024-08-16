<h1>API - Controle de vagas de carro em condomínio</h1>
<p>A aplicação tem o objetivo de gerenciar vagas de garagem em um condomínio, onde cada apartamento tem direito a 1 vaga na garagem</p>

<h2>Endpoints</h2>
<p>GET - localhost:8080/parking-spot?page=0&size=5&sort=registrationDate,DESC</p>
<p>GET - localhost:8080/parking-spot/{id}</p>
<p>POST - localhost:8080/parking-spot</p>
<p>PUT - localhost:8080/parking-spot/{id}</p>
<p>DELETE - localhost:8080/parking-spot/{id}</p>

<h3>JSON exemplo - post</h3>
<p>
{ <br>
  "parkingSpotNumber": "2085", <br>
  "licensePlateCar": "RRS8552", <br>
  "brandCar": "hyundai", <br>
  "modelCar": "4x4", <br>
  "colorCar": "cinza", <br>
  "responsibleName": "Sarah Pereira", <br>
  "apartment": "107", <br>
  "block": "c" <br>
}
</p>

<h2>Bibliotecas usadas</h2>
<ul>
    <li>Spring Boot</li>
    <li>Spring MVC</li>
    <li>Spring Data JPA</li>
    <li>Spring Validation</li>
    <li>Spring MySQL Driver</li>    
</ul>

<h2>Banco de dados</h2>
<p>MySql</p>
<p>Database nome: park_control_db </p>
<p>*Alteraçoes necessárias no:  src/resources/aplication.properties</p>
