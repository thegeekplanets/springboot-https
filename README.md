<h1 align="center" id="title">HTTPS Enabled Spring boot Application</h1>

<p id="description">The purpose of this application is to enable the https protocol for a spring boot application and generate a self-signed SSL certificate.</p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   Create Self Signed SSL Certificate
*   Enable HTTPS

<h2>🛠️ Installation Steps:</h2>

<p>1. Maven Build</p>

```
mvn clean install -Dmaven.test.skip=true
```

<p>2. Create a SSL certificate</p>

```
keytool -genkey -alias thegeekspace -storetype PKCS12 -keyalg RSA -keysize 2048 -keystore keystore.p12  -validity 3650
```

<p>3. Run Application</p>

```
 mvn spring-boot:run
```

<p>4. Access HTTPS enable endpoint</p>

```
https://localhost:443/api
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Java
*   Spring Boot
*   Restful API
*   Swagger API
*   HTTPS
