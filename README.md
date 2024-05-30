<div align="center">

![Convert-me_cover](https://user-images.githubusercontent.com/87483916/224345890-7077b778-878c-42cb-9292-2590de454519.png)



<img src= "./frontend/assets/currency_theme_white-trim.png" width="850" height="300" alt=" face of an American president on a coin">

</div>

## :8ball: Description

Currency pair converter that queries a LAYER API returns the exchange rate in real time and converts the respective pairs.

<div align="center">

 <img src= "https://user-images.githubusercontent.com/87483916/232828544-c7af4a6d-8670-4616-a5bc-7ea078acdab2.png " width="1000" alt= "application design scheme"/>

</div>

## :smile: Project Status

![→_-in-development-green](https://user-images.githubusercontent.com/87483916/224333868-804e4712-ecb7-492b-8c47-6c6bff8e3b7a.svg)


## 🚀 Getting Started

These instructions will allow you to get a copy of the project running on your local machine for development and testing purposes.

See **[Deployment](#-implanta%C3%A7%C3%A3o)** to learn how to deploy the project.

### 📋 Prerequisites

 ##### <a href="https://www.oracle.com/br/java/technologies/downloads"> * Maven </a>
 ##### <a href="https://www.oracle.com/br/java/technologies/downloads"> * Eclipse or other IDE </a>
 ##### <a href="https://www.oracle.com/br/java/technologies/downloads"> * JDK 11 or higher </a>
 ##### <a href="https://www.oracle.com/br/java/technologies/downloads"> * MySQL Workbench </a>


### 🔧 Installation


#### :anger: By Git Bash:
<hr>

1. Open Git Bash.
2. Change the current working directory to the location where you want to have the directory cloned.
3. Type git clone and paste the already copied URL.

```
$ git clone https://github.com/rc-ventura/CurrencyConverter-App
```
4. Press **ENTER** to create your local clone.
```
$ git clone https://github.com/rc-ventura/CurrencyConverter-App
> Cloning into `Spoon-Knife`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```
5. Open your Eclipse
6. Select -> File -> Open Projects From File System -> Select the folder path where you downloaded.
7. Press **RUN** in Eclipe to run the application or **Ctrl + F11**


#### :anger: By Downloading the .zip file:
<hr>

1. On GitHub.com, navigate to the repository's main page.
2. Above the file list, click **Code** or **Code**.
3. Select the **Download .zip** option
5. Save to a local machine.
5. Open your Eclipse
6. Select -> File -> Open Projects From File System -> Select the folder path where you downloaded.
7. Press **RUN** in Eclipe to run the application or **Ctrl + F11**


#### :anger: Running with Maven:
<hr>

1. Clone or download the application.
2. Open Command Prompt or Terminal.
3. Select the folder path where you downloaded.
5. Run the following command:
 ```
 mvn spring-boot:run
 ```


## :scroll: Features

<br>

* Exchange rate converter between a currency pair.

https://user-images.githubusercontent.com/87483916/224521177-28dfcd7d-a7f8-4b07-8165-008f50befc2d.mp4

<br>
<br>

* Saving conversion transactions to the database.

https://user-images.githubusercontent.com/87483916/224570140-59ec3d15-2057-4b94-b85e-2c733daf2f98.mp4



## :airplane: Roadmap

 - [x] Main Feature: Method for converting currency pairs.
 - [x] Feature: User interface in Html/Css.
 - [x] Feature: Link between backend and frontend with JQuery.
 - [x] Feature: Exceptions Controller
 - [x] Unit tests with Junit and Mockito from Main Feature.
 - [x] API integration test with the restAssured library.
 - [x] Tests with 80% coverage.
 - [x] UI adjustments.
 - [x] Feature: Method to save every conversion transaction in the database.
 - [x] Test for method to save every transaction in the database.
 - [x] Integration testing of all features.
 - [ ] Load testing on database transactions.
 - [ ] UI testing with Selenium.
 - [x] API documentation with Swagger/OpenApi.
 - [x] Documentation with Tests with Allure Framework.
 - [x] Deploy the application in a test environment with K3d from Ranch.
 - [x] Automation with startup script with Terraform for the remote server at Digital Ocean.
 - [x] Deploy the application in a development environment on a remote server on Digital Ocean with Kubernetes.
 - [x] CI/CD pipeline with Jenkins in development environment.
 - [ ] CI/CD pipeline with Jenkins at Digital Ocean in production.
 - [x] SRE: Application Observability: Metrics with Micrometer
 - [x] SRE: Application Observability: Monitoring with Prometheus
 - [x] SRE: Application Observability: Dashboards with Grafana.




## :book: Documentação

##### <a href="https://swagger.io/specification/)" target="_blank"> Swagger/OpenAPI </a>

<img src="https://user-images.githubusercontent.com/87483916/230924283-b1cf026a-ca3d-4ad0-a721-d762791bc960.png" alt="documentacão Api swagger"/>


<div align="center">

https://user-images.githubusercontent.com/87483916/230924780-c11f1a06-e2d6-4cf1-a6d8-3e75b8c24f01.mp4

</div>

## ⚙️ Executando os testes
<Br>

* Overview dos testes feitos em Junit, Mockito, Rest Assured
<Br>

<div  style="display: inline-block" >

<img src="https://user-images.githubusercontent.com/87483916/230927490-7ff73c1c-cc32-4e4f-bf0c-e899d38d96d9.png" alt="Imagem modificada" width="800"/>

<img src="https://user-images.githubusercontent.com/87483916/230928492-249e0adf-1f74-48d4-9b40-b95a67b7846b.png" alt="Imagem modificada" width="800"/>
<Br>
<Br>

### :fast_forward: Testes de Integração
<Hr>

#### :o: shouldConvertCurrencyAndSaveTransaction
* Simula uma consulta na API externa.
* Retorna com a taxa de conversão.
* Processa a conversão.
* Salva no banco de dados a transação.
<Br>
<img src= "https://user-images.githubusercontent.com/87483916/230958891-d9ff3b4b-1f7f-43ef-96a4-fb72c2a47303.png" alt= "Imagem modificada" width="800"/>


#### :o: Transaction Controller Feature
* Simula todos os endpoints da aplicação ao manipular uma transação
* Controller->Service->Repository
* GET, UPDATE, GET/ID, DELETE/ID, SAVE
<Br>


<img src="https://user-images.githubusercontent.com/87483916/230958940-8f6d3e33-36f8-4244-a334-59429143a0a1.png" alt=" Imagem modificada" width="800"/>

<Br>

### :fast_forward: Testes Unitários
<Hr>

#### :o: CurrencyExceptionHandler
* Simula o controle de exceções
<Br>

![Sem título - Brave 10_04_2023 11_56_51](https://user-images.githubusercontent.com/87483916/230982651-7dbe2ae6-b3f4-4808-8c83-38cb4f8733d3.png)


#### :o: Currency Conversion
* Simula uma conversão.
* Chama a API Externa
* Faz uma conversão do par USD para BRL.
<Br>

![Sem título - Brave 10_04_2023 11_54_53](https://user-images.githubusercontent.com/87483916/230982897-a2460374-df92-43b4-8a68-ae14140fe758.png)


<Br>

#### :o: Transaction Service
* Simula todas as manipulações de transações na camada de Serviços
* Service->Repository

<Br>

![Sem título - Brave 10_04_2023 11_55_35](https://user-images.githubusercontent.com/87483916/230983762-5092a75c-d24e-4d28-8d41-6b3ee1b71449.png)


</div>


<!-- Explicar como executar os testes automatizados para este sistema.

### 🔩 Analise os testes de ponta a ponta

Explique que eles verificam esses testes e porquê.

```
Dar exemplos
```

### ⌨️ E testes de estilo de codificação

Explique que eles verificam esses testes e porquê.

```
Dar exemplos
```
-->

## 📦 Implantação

<Br>

<div align="center">

![Deploy-Currency-Converter drawio](https://github.com/rc-ventura/CurrencyConverter_CI-CD-K3D/assets/87483916/8ce8a791-f8fc-4e4d-8d05-8cc90a121330)


</div>

<Br>

#### :crystal_ball: DEVOPS

* Utilizando o Terraform provisiona uma infra-estrutura básica na  Digital Ocean.
* Criação de um cluster kubernetes com três serviços: backend, frontend e bancode dados
* Criação de 3 réplicas do backend e do frontend para escalonamento
* Criação de um load balancer aberto para internet que balanceia a carga para o frontend na porta 80 (http)
* Provisionamento de um máquina virtual (Droplet) para configurar a orquestração com o Jenkins.
* Criação do pipeline com o Jenkins CI utilizando o Docker e o DockerHub.
* Configuração d eum webhook no github para automatização do início do pipeline CI após um gitpush no repositório.

#### :mag: SRE

* Criação de observabilidade utlizando o Helm para configurar o cluster Kubernetes.
* Criação um load balancer aberto para requisições http na porta 80 e redirecionamento para a porta 9090 (prometheus)
* Criação um load balancer aberto para requisições http na porta 80 e redirecionamento para 3000 (grafana).
* Criação dos dashboards das métricas funcionais e não funcionais da aplicação.

#### :computer: DEV

* Promove alterações no código e ativa o trigger do pipeline.
* Manutenção e implementação dos testes unitários
* Promove a cobertura do código nos testes.

<Br>



## 🛠️ Tecnologias

<div  style="display: inline-block" >

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="80"  />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="80"  />
<img src= "https://user-images.githubusercontent.com/87483916/224313415-17511f48-87e4-4d9d-98ed-01daba701270.png" width="80"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"width="80" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-plain-wordmark.svg"width="80" />
<img src="https://cdn.js





