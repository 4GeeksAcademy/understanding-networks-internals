# Entendiendo las redes desde dentro

<!-- hide -->
> By [@arnaldoperez](https://github.com/arnaldoperez) and [other contributors](https://github.com/4GeeksAcademy/installing-windows-on-virtual-machine/graphs/contributors) at [4Geeks Academy](https://4geeksacademy.co/)

![last commit](https://img.shields.io/github/last-commit/4geeksacademy/understanding-networks-internals)
[![build by developers](https://img.shields.io/badge/build_by-Developers-blue)](https://4geeks.com)
[![build by developers](https://img.shields.io/twitter/follow/4geeksacademy?style=social&logo=twitter)](https://twitter.com/4geeksacademy)

<!-- endhide -->

## 📝 Instrucciones

### Basados en la red configurada en el prework:

![intro network](https://github.com/4GeeksAcademy/understanding-networks-internals/blob/master/assets/network.png?raw=true)

Eres un consultor de redes y te han contratado para mejorar la arquitectura de red de una pequeña empresa. La empresa actualmente tiene una red que ha crecido orgánicamente con el tiempo y está experimentando problemas de rendimiento y seguridad. Tu tarea es evaluar la situación actual y proponer mejoras. Cuentas con la siguiente información:

### La empresa tiene los siguientes requerimientos

- Que la red tenga capacidad para crecer hasta 100 dispositivos
- La red debe dividirse en subredes para los departamentos de Mercadeo, Tecnología y Contabilidad
- La capacidad de la red de cada departamento es la siguiente:
  - Mercadeo: 30 dispositivos
  - Tecnología: 40 dispositivos
  - Contabilidad: 15 dispositivos
  - El restante de la capacidad se reserva para futuros crecimientos
- Cada subred debe tener su propio servidor privado. Solo el servidor del departamento de Tecnología debe estar disponible para todas las redes

### Preguntas y Desafíos:

1. **Evaluación de la Situación Actual:**
    - ¿Cuál es el alcance de la red actual?
    - ¿Qué problemas pueden ocurrir de no haber mejoras en la red de la empresa?
2. **Topología de Red:**
    - ¿Qué topología de red utilizarías para esta empresa?
    - ¿Cómo se deben conectar los dispositivos y los servidores?
3. **Equipos de Red:**
    - ¿Qué tipo de dispositivos de red se necesitan? (routers, switches, firewalls, etc.)
    - ¿Qué especificaciones técnicas deben cumplir estos dispositivos?
4. **Seguridad de la Red:**
    - ¿Cuáles son las medidas de seguridad necesarias para proteger la red?
    - ¿Qué políticas se deben implementar en cuanto al personal para tener una red segura?
    - ¿Qué reglas se deben configurar los dispositivos de seguridad, como el firewall?
5. **Gestión de la Red:**
    - ¿Cómo se gestionarán y supervisarán los dispositivos de red?
    - ¿Sería conveniente implementar un sistema de gestión de red (NMS) o herramientas de monitoreo? ¿Por qué?
6. **Plan de Implementación:**
    - ¿Cuál es el cronograma de implementación de las mejoras propuestas?
    - ¿Cómo se comunicarán estos cambios a los empleados?
7. **Mantenimiento Continuo:**
    - ¿Qué medidas se tomarán para garantizar el mantenimiento y la actualización continua de la red?
    - ¿Se establecerán políticas de seguridad y procedimientos de respuesta a incidentes?
8. **Evaluación del Éxito:**
    - ¿Cómo se medirá el éxito de las mejoras? ¿Qué métricas se utilizarán para evaluar el rendimiento y la seguridad de la red después de la implementación?
    
> ⚠️ **Recuerda: No hay respuestas incorrectas en cuanto a topologías de red y dispositivos, intenta hacer la red lo más óptima posible.**

## 🚛 ¿Cómo entregar este proyecto?

Elabora un documento de texto con las respuestas a las preguntas que están en las instrucciones. Una vez tengas listo tu documento cárgalo en la plataforma 4geeks.com en el proyecto correspondiente.


<!-- hide -->
## Colaboradores

Gracias a estas personas maravillosas ([emoji key](https://github.com/kentcdodds/all-contributors#emoji-key)):

1. [Arnaldo Perez (arnaloperez)](https://github.com/arnaloperez) contribution: (build-tutorial) ✅, (documentation) 📖
  
2. [Alejandro Sanchez (alesanchezr)](https://github.com/alesanchezr),  contribution: (bug reports) 🐛

3. [Lorena Gubaira (lorenagubaira)](https://github.com/lorenagubaira), contribution: (bug reports) 🐛, contribution: (coder), (translation) 🌎

Este proyecto sigue la especificación [all-contributors](https://github.com/kentcdodds/all-contributors). ¡Todas las contribuciones son bienvenidas!

Este y otros ejercicios son usados para [aprender a programar](https://4geeksacademy.com/es/aprender-a-programar/aprender-a-programar-desde-cero) por parte de los alumnos de 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) realizado por [Alejandro Sánchez](https://twitter.com/alesanchezr) y muchos otros contribuyentes. Conoce más sobre nuestros [Cursos de Programación](https://4geeksacademy.com/es/curso-de-programacion-desde-cero?lang=es) para convertirte en [Full Stack Developer](https://4geeksacademy.com/es/coding-bootcamps/desarrollador-full-stack/?lang=es), o nuestro [Data Science Bootcamp](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning). Tambien puedes adentrarte al mundo de ciberseguridad con nuestro [Bootcamp de ciberseguridad](https://4geeksacademy.com/es/coding-bootcamps/curso-ciberseguridad)
<!-- endhide -->