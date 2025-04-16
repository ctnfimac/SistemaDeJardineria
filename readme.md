# Sistema de Jardineria - Proyecto Spring

## 📄 Descripción y Objetivo del Proyecto

Este proyecto es un sistema de jardinería desarrollado con Spring Boot, cuyo objetivo es permitir a los clientes solicitar
servicios de jardineria para su hogar, como por ejemplo: "Cortador de Pasto" y "Podador de Árboles".

Existen 3 tipos de roles principales: **Administrador, Jardinero y Cliente**, cada uno con permisos y responsabilidades específicas.

El **Admin** tendrá permisos para bloquear o desbloquear jardineros y clientes, también podrá hacer un mantenimiento sobre los tipos de servicios de jardineria,
ver a través de un listado todos los clientes y jardineros, lo recaudado, las transacciones, las contrataciones de clientes a jardineros.

Los **jardineros** podrán registrarse, activar su cuenta, inicar sesión, modificar su perfil, agregar fotos y descripciones de sus trabajos realizados(máximo 6),
ver que cliente solicita el trabajo, aceptar o no el trabajo solicitado, cuando acepta se cobra un adelanto y se termina con el pago una vez finalizado el trabajo;
en caso de cancelar se reintegrará el dinero al cliente.

Los **clientes** podrá registrarse, activar cuenta, iniciar sesión, modificar perfil, buscar jardinero por tipo de servicios y disponibilidad, elegir fecha del trabajo a realizar,
solicitar servicios, si el jardinero acepta se le paga por adelantado y se termina de pagar una vez finalizado.

Los pagos se realizarán con mercado pago.

## Arquitectura:
Para el backend se usará la arquitectura de Microservicios:
- [Servicio de usuarios ](https://github.com/ctnfimac/spring_cicd)
- [Servicio de Contrataciones](https://github.com/ctnfimac/contract-service)
- [Servicio de Trabajos](https://github.com/ctnfimac/work-service)

## Lenguajes a usar:
- El servicio de "usuarios" se desarrollará con Java y framework SpringBoot.
- El servicio de "contrataciones" se desarrollará con Goland.
- El servicio de "Trabajos" se desarrollará con Python y Libreria FastApi.

## Estructura General del proyecto:
![Image](https://github.com/user-attachments/assets/ebb9b47b-3dd2-4147-9bea-ffb3ab94d52d)

## Organización del proyecto
Las tareas se organizan en un tablero creado en el mismo repositorio de github, las cuales están divididas
en 3 etapas: 
- Todo: indica la tarea que se tiene que realizar
- In Progress: indica que la tarea se encuentra en proceso de resolución
- Done: indica que la tarea fue finalizada

[Link al Tablero del proyecto](https://github.com/users/ctnfimac/projects/1)

## Imágen del Front
No forma parte del proyecto actualmente pero se esta realizando un frontend con Angular para probar el funcionamiento
de los endpoints

![Image](https://github.com/user-attachments/assets/03ba125b-d5e5-4d85-921c-1bf93685a3cb)