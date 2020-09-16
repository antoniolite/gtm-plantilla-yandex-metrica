# Plantilla de Yandex.Metrica para GTM

Esta plantilla personalizada (no oficial) permite implementar **Yandex.Metrica** con Google Tag Manager.

**También disponible en ruso e inglés.**

- [Histórico de cambios y actualizaciones](https://www.antoniolite.com/plantilla-de-yandex-metrica-para-gtm/)
- [Más información sobre Yandex.Metrica](https://metrica.yandex.com)
- [Documentación de Yandex.Metrica](https://yandex.com/support/metrica/index.html)

# Autor

Antonio Lite (https://www.antoniolite.com/)

# Información

La plantilla permite la configuración de los siguientes métodos:

- init
- hit
- extLink
- file
- reachGoal
- params
- userParams
- setUserID
- notBounce

Admite la configuración de parámetros y opciones para todos los métodos que lo permiten, incluido el coste del objetivo y divisa (_order\_price_ y _currency_)

Permite configurar el código de seguimiento de Yandex.Metrica:

- No enviar datos automáticamente
- Bloquear indexación de la página
- No registrar rebote
- Usar CDN alternativo
- Mapa de clics
- Grabación de sesiones
- Registrar enlaces salientes
- Registrar hash en las URLs
- Rebote más preciso
- Evento de inicialización
- Grabación de iframe
- Dominios de confianza
- Extensiones adicionales de fichero
- Parámetros de sesión
- Parámetros de usuario

Permite también activar el modo de depuración (debug) nativo de Yandex.Metrica.

Es recomendable la lectura de estos tres artículos para conocer todas las funcionalidades y características de la plantilla. En ellos se explican con detalle todas las funciones que se han ido añadiendo:

[Plantilla de Yandex.Metrica para GTM](https://www.antoniolite.com/2019/06/plantilla-de-yandex-metrica-para-gtm/)

[Plantilla de Yandex.Metrica para GTM (09.2019)](https://www.antoniolite.com/2019/09/plantilla-de-yandex-metrica-para-gtm-09-2019/)

[Plantilla de Yandex.Metrica para GTM (07.2020)](https://www.antoniolite.com/2020/07/plantilla-de-yandex-metrica-para-gtm-07-2020)

# Actualizaciones

## 16.09.2020

- Revisión de textos
- Disponible versión en inglés
- Disponible versión en ruso

## 31.07.2020

- Añadido parámetros de coste de objetivo al evento hit
- Añadido parámetros de coste de objetivo al evento reachGoal
- Añadido parámetros de coste de objetivo al evento file
- Añadido parámetros de coste de objetivo al evento extLink
- Reorganización de algunos bloques de campos
- Solución de pequeños bugs
- Optimización de código

## 25.09.2019

- Añadido parámetro childIframe en la inicialización de la etiqueta
- Añadido parámetro trustedDomains en la inicialización de la etiqueta
- Añadido parámetro userParams en la inicialización de la etiqueta
- Añadido parámetro triggerEvent en la inicialización de la etiqueta
- Solucionado bug con el método setUserId
- Solucionado bug al añadir extensiones de fichero para monitorizar
- Mejoras en la interfaz de configuración de la etiqueta
- Optimización de código

## 16.06.2019

- Versión inicial

