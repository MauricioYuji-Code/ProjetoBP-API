"# ProjetoBP-API" 

### Features

[X] Executar métodos GET, POST, PUT, DELETE

[X] Validar JSON schema

### Ferramentas/Tecnologias utilizadas

[Postman](https://www.postman.com/)

[Newman](https://www.npmjs.com/package/newman)

[JavaScript](https://www.javascript.com//)


### Execução através do ID Collections (URL)

Abra o terminal e execute o seguinte comando
C:\ProjetoBP-API> newman run https://api.getpostman.com/collections/17105854-5f93c2ff-1301-4b15-aa37-ed5533223d6d?apikey=PMAK-62dc3815ff2417003d51510b-0f3525c7e8e502396f82b4664573d2d9b7 -e https://api.getpostman.com/environments/17105854-b2870579-bc4a-4d8a-b163-f2901fa01be3?apikey=PMAK-62dc3815ff2417003d51510b-0f3525c7e8e502396f82b4664573d2d9b7
newman

### Execução Local

Abra o terminal e vá até o diretório, em seguifa execute o seguinte comando:

C:\ProjetoBP-API> newman run Collection\API_JsonPlaceHolder.postman_collection -d Data\massa_dados.csv -e Environment\AmbienteJPH.postman_environment.json -r htmlextra