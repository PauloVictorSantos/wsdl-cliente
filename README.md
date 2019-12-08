# Cliente WebService SOAP
Cliente web utilizando SOAP com Java e Spring Boot.  
Esse cliente consome os dados disponibilizados pelo servidor implementado em https://github.com/m4rciosouza/webservice-soap-spring-servidorhttps://github.com/PauloVictorSantos/webservice-soap-spring-servidor.git
Certifique-se de possuir o Git instalado.
```
git clone https://github.com/PauloVictorSantos/wsdl-cliente.git
cd webservice-soap-spring-cliente
./mvnw clean install -DskipTests
./mvnw spring-boot:run
```
Será impresso no console dois exemplos de chamadas ao servidor mencionado acima.
