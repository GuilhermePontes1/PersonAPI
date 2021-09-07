<h2> Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot</h2>

### Tecnologias: 
![image](https://user-images.githubusercontent.com/65747791/132414724-937a6541-5798-425b-88ba-e98e1b41f0ed.png) 
![image](https://user-images.githubusercontent.com/65747791/132414836-53e06b2c-f2e6-4e3b-8014-8470b7f892f0.png)
![image](https://user-images.githubusercontent.com/65747791/132417042-576ca233-3556-44aa-b542-0101f37f0773.png)
![image](https://user-images.githubusercontent.com/65747791/132417078-fc54aa77-ef7b-4877-87a2-c2efee701706.png)
![image](https://user-images.githubusercontent.com/65747791/132417108-7243ab05-6e3e-49ee-abdb-09f4e97e4bf7.png)





Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people 

```
#### Exemplo de Post no Heroku ou local (dados fictícios ). 
#### Pode se fazer Get por ID, ou Geral além de PUT e Delete

```
https://person-api1.herokuapp.com/api/v1/people
```

```
{
"firstName": "Rodrigo",
"lastName": "Jaime",
"cpf" : "747.055.100-03",
"phones" : [
    {
        "type" : "MOBILE",
        "number": "(45)515070714"
    }
]
}
```


