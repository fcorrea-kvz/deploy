# Deploy con Now.sh #

## 1. Introducción al Cursos de Deploy con Now.sh ##
### 1.1 Componentes de una aplicación  ###

Una aplicación web moderna se divide en varias partes, algunas aplicaciones tienen más que otras, en este curso vamos a ver alguna:

* **Archivos estáticos o Frontend**. Estos archivos son enviados al usuario a través de un CDN.
* **Backend for Frontend**. Este es el servidor que pide datos al API y responde HTML al usuario.
* **Backend API**. Puede estar hecho en cualquier tecnología e incluso puede estar dividido en múltiples aplicaciones pequeñas encargadas de distintas responsabilidades cada una.
* **Bases de Datos**. Puede estar hecha en lo tecnología de BD que sea y pueden existir diferentes bases de datos creadas en distintas tecnologías.
	* PostgreSQL: informacion general
	* Redis: cache y seciones
	* MOndoDB: datos que cambian muy rapidos
	
![Componentes](https://joaquinaraujo.github.io/deploy-now/)

#### Definiciones importantes ####

* **CDN**: Content Delivering Network. Muchos servidores distribuidos por todo el mundo proveer de estos archivos comunes y que no están generados dinámicamente a nuestros usuarios y que puedan acceder rápidamente a ellos.
* **API**: Aplication Programming Interface. Representa la capacidad de comunicación entre componentes de software.

```
┌----------------- Frontend -----------┐
Usuario ---- backend for Frontend ---- backend API ---- Base de Datos
```

### 1.2 Opciones para hacer Deploy ###

Estas son algunas de las opciones para llevar una aplicación a producción:
* **Amazon Web Services** (Control en la infraestructura) <-- Netflix esta aca
* **Microsoft Azure** (Control en la infraestructura) <-- Integrado con Visual Studio.
* **Google Cloud Platform** (Control en la infraestructura) <-- Acceso API de Google.
* **Digital Ocean** (Control en la infraestructura) <-- util si se tiene varios clientes y cada uno paso su servicio.
* **Heroku** (Sin control en la infraestructura) <-- deploy sin pensar en infraestructura
* **Zeit Now** (Sin control en la infraestructura) <-- Deploy aplicacion web.
* **GitHub Pages** (Para sitios estáticos) <-- deploy de archivos estaticos gratuita. (open source)
* **Surge.sh** (Para sitios estáticos) <-- deploy estaticos.

#### ¿Por que elegir Now.sh por encima de otros? ####

Zeit Now funciona con Nodejs, puede contener archivos estáticos y soporta Docker. 

##### Tipos de Deploys #####

* Aplicacion de Node.js
* Sitios estaticos
* Contenedores de Docker

##### Algunas de sus características son #####

* Es fácil (sólo un comando basta).
* Escala automáticamente.
* Deploy inmutable.
* Deploy sin caída.
* Deploy ilimitados.
* HTTP2 automáticamente.
* Certificado SSL gratis.
* Logs por deploy.
* DNS (zeit.world).
* Permite comprar dominios por CLI.

### 1.3 Aplicaciones monolíticas vs microservicios ###
### 1.4 Instalación de Now.sh ###

## 2. Aplicaciones Estáticas ##
### 2.1 Deploy con GitHub Pages ###
### 2.2 Deploy con Surge.sh ###
### 2.3 Deploy con Now.sh ###

## 3. Tipos de Deploy ##
### 3.1 Estructura del proyecto ###
### 3.2 Deploy de aplicaciones Node.js ###
### 3.3 Deploy de contenedores de Docker ###

## 4. Configuraciones ##
### 4.1 Configuración de secrets y variables de entorno ###
### 4.2 Ver el código fuente de tu aplicación ###
### 4.3 Definir aliases para tus deploy ###
### 4.4 Usar un dominio personalizado ###
### 4.5 Componer microservicios ###

## 5. Conclusiones ##
### 5.1 Conclusión del proyecto ###
### 5.2 Conclusiones del curso ###

## 6. Contenido Bonus ##
### 6.1 Deploy en Now.sh desde GitHub ###

## 7. Retos y Desafíos ##
### 7.1 Combinar muchos servicios ###
### 7.2 Usar un servicio diferente ###
