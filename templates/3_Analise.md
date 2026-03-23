# Requerimientos do sistema

- [Requerimientos do sistema](#requerimientos-do-sistema)
  - [1- Descrición Xeral](#1--descrición-xeral)
  - [2- Funcionalidades](#2--funcionalidades)
  - [3- Tipos de usuarios](#3--tipos-de-usuarios)
  - [4- Contorno operacional](#4--contorno-operacional)
  - [5- Normativa](#5--normativa)
  - [6- Melloras futuras](#6--melloras-futuras)

## 1- Descrición Xeral

O proxecto consiste no desenvolvemento dunha plataforma web orientada ao **powerlifting e ao adestramento de forza**, que permitirá conectar adestradores e usuarios nun mesmo entorno dixital.

A aplicación funcionará como un sistema centralizado no que os adestradores poderán ofrecer os seus servizos mediante distintos tipos de subscricións, mentres que os usuarios poderán acceder a contidos, rexistrar os seus adestramentos e facer seguimento do seu progreso.

A plataforma incluirá funcionalidades relacionadas coa xestión de rutinas, rexistro de datos deportivos, comunicación entre usuarios e adestradores, así como unha tenda de produtos deportivos.

## 2- Funcionalidades

A continuación descríbense as principais funcionalidades do sistema:

| Acción                    | Descrición                                                             |
| ------------------------- | ---------------------------------------------------------------------- |
| Rexistro de usuario       | Permite crear unha conta como cliente ou adestrador                    |
| Inicio de sesión          | Acceso á plataforma mediante credenciais                               |
| Xestión de perfil         | Modificación de datos persoais e preferencias                          |
| Creación de contidos      | Os adestradores poden publicar rutinas, programas e cursos             |
| Sistema de subscricións   | Os adestradores crean plans con diferentes prezos e servizos           |
| Compra de subscrición     | Os usuarios contratan un plan dun adestrador                           |
| Rexistro de adestramentos | Os usuarios gardan datos dos seus exercicios (peso, repeticións, etc.) |
| Calculadora de RM         | Permite calcular o peso máximo nunha repetición                        |
| Seguimento do progreso    | Visualización da evolución do usuario                                  |
| Sistema de mensaxería     | Comunicación directa entre usuario e adestrador                        |
| Tenda de merchandising    | Compra de produtos deportivos                                          |
| Xestión de pedidos        | Control de compras realizadas                                          |
| Panel de administración   | Xestión global da plataforma                                           |

Cada funcionalidade implica:

- **Entrada:** datos introducidos polo usuario
- **Proceso:** validación e tratamento dos datos
- **Saída:** resposta do sistema (visualización, confirmación...)

## 3- Tipos de usuarios

O sistema contará con distintos tipos de usuarios segundo o seu rol:

### Usuario non rexistrado

- Pode navegar pola plataforma
- Pode ver contido público

### Usuario cliente

- Pode contratar subscricións
- Pode rexistrar adestramentos
- Pode acceder a contidos de adestradores
- Pode comunicarse cos adestradores
- Pode comprar produtos

### Usuario adestrador

- Pode crear e xestionar contidos
- Pode definir subscricións
- Pode xestionar clientes
- Pode vender produtos
- Pode comunicarse cos usuarios

### Administrador

- Xestionar usuarios
- Controlar contidos
- Supervisar a actividade da plataforma
- Resolver incidencias

## 4- Contorno operacional

Para utilizar a aplicación, o usuario necesitará:

- Un dispositivo con acceso a internet (ordenador, móbil ou tablet)
- Un navegador web actualizado (Chrome, Firefox, Edge...)

Non será necesario instalar e usar software adicional, xa que a aplicación funcionará integramente vía web.

## 5- Normativa

O proxecto deberá cumprir coa normativa vixente en materia de protección de datos e servizos dixitais.

En particular:

- **Lei Orgánica 3/2018 (LOPDGDD)** en España
- **Regulamento Xeral de Protección de Datos (GDPR)** a nivel europeo

Estas normativas afectan directamente ao deseño e desenvolvemento da aplicación, xa que obriga a implementar medidas técnicas e organizativas desde as primeiras fases do proxecto.

### Protección de datos desde o deseño

A aplicación deberá seguir o principio de “privacidade desde o deseño”, o que implica:

- recoller só os datos estritamente necesarios (nome, email, datos de uso)
- evitar almacenar información innecesaria
- definir claramente a finalidade do tratamento dos datos

### Sistema de autenticación e seguridade

Será necesario implementar:

- contrasinais cifrados (hash)
- uso de conexión segura mediante HTTPS (SSL)
- control de sesións de usuario
- protección fronte a accesos non autorizados

### Xestión de consentimento

A aplicación deberá:

- olicitar consentimento explícito ao rexistrarse
- permitir aceptar ou rexeitar cookies
- informar ao usuario sobre o uso dos seus datos

### Dereitos dos usuarios

O sistema debe permitir que os usuarios poidan:

- acceder aos seus datos
- modificar a súa información
- eliminar a súa conta

### Almacenamento e tratamento de datos

- os datos deben almacenarse de forma segura na base de datos
- evitar exposición de datos sensibles
- limitar o acceso só a usuarios autorizados

### Documentación legal obrigatoria

A web deberá incluír:

- aviso legal
- política de privacidade
- política de cookies

### Impacto no desenvolvemento

Estas obrigas implican que:

- será necesario implementar medidas de seguridade desde o inicio
- aumentará lixeiramente a complexidade do desenvolvemento
- haberá que dedicar tempo á configuración legal e técnica

Non obstante, estas medidas son estándar en aplicacións web actuais e non supoñen unha limitación significativa para o proxecto.

## 6- Melloras futuras

O proxecto poderá ampliarse no futuro mediante novas funcionalidades:

- Sistema de estatísticas avanzadas
- Plans automatizados mediante intelixencia artificial
- Sistema de valoración de adestradores
- Marketplace ampliado con posibles colaboracións
- Sistema de competicións e rankings

Estas melloras permitirán evolucionar a plataforma e adaptala ás necesidades do mercado.

[**<-Anterior**](../../README.md)
