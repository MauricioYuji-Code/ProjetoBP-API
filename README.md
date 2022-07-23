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
```bash
C:\ProjetoBP-API> newman run https://api.getpostman.com/collections/17105854-5f93c2ff-1301-4b15-aa37-ed5533223d6d?apikey=<API-Key> -e https://api.getpostman.com/environments/17105854-b2870579-bc4a-4d8a-b163-f2901fa01be3?apikey=<API-Key>
newman
```
### Execução Local
Abra o terminal e vá até o diretório, em seguifa execute o seguinte comando:
```bash
C:\ProjetoBP-API> newman run Collection\API_JsonPlaceHolder.postman_collection -d Data\massa_dados.csv -e Environment\AmbienteJPH.postman_environment.json -r htmlextra
```

Observação: Solicitar API Key para a execução remota