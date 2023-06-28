# Informe de busqueda de API EXTERNAS para Sitio Web de Casino

## Descripción general
El siguiente informe se realiza con elfin de recopilar información necesaria para integracion y/o consumo de una o varias API externas para la creación de un sitio web de casino.

---

## Autenticación
Antes de poder acceder a los datos de la API, es necesario autenticarse correctamente. El proceso de autenticación puede variar según la implementación específica de la API. A continuación se muestra un ejemplo de cómo se podría llevar a cabo la autenticación:

1. Obtener las credenciales de autenticación proporcionadas por el proveedor de la API.
2. Enviar una solicitud POST al punto de entrada de autenticación de la API con las credenciales proporcionadas.
3. Recibir y almacenar el token de autenticación devuelto en la respuesta.
4. Incluir el token de autenticación en el encabezado de todas las solicitudes subsiguientes a la API.

Es importante tener en cuenta que la autenticación puede requerir la renovación periódica del token para mantener la seguridad. Asegúrate de consultar la documentación oficial de la API para obtener instrucciones detalladas sobre cómo autenticarse correctamente.

---

## Endpoints y operaciones

A continuación se detallan algunos de los endpoints y operaciones más comunes que se pueden utilizar para interactuar con la API del casino:

### API Wisdom of Athena - Proveedor: Pragmatic Play

- **Descripción**: Wisdom of Athena es una tragamonedas de Pragmatic Play. Se solicita en el sitio deb del proveedor por correo electronico información de costos y documentacion de la API, se encuentra a la espera de respuesta del correo enviado al proveedor del juego, se agrega enlace de casino.guru el cual permite consumir la demo del presente juego. 
- **Método**: GET
- **Endpoint**: `https://es.casino.guru/embedGame?identifier=fe940e0f-48d5-49bf-9663-517161d98718`
- **Contacto**: `https://pragmatic.solutions/contact-us`

### API Lucky Leprechaun - Proveedor: Microgaming

- **Descripción**: Lucky Leprechaun es una tragamonedas de Microgaming, se solicita en el sitio deb del proveedor por correo electronico información de costos y documentacion de la API, se encuentra a la espera de respuesta del correo enviado al proveedor del juego, se agrega enlace de casino.guru el cual permite consumir la demo del presente juego. 
- **Método**: GET
- **Endpoint**: `https://es.casino.guru/embedGame?identifier=35d74f10-f8c6-4a86-b302-7fbf53b89a8f`
- **Contacto**: `https://www.microgaming.co.uk/contact`

### API Valley of the Gods - Proveedor: YGGDRASIL GAMING

- **Descripción**: Valley of the Gods es una tragamonedas de YGGDRASIL GAMING, se solicita en el sitio deb del proveedor por correo electronico información de costos y documentacion de la API, se encuentra a la espera de respuesta del correo enviado al proveedor del juego, se agrega enlace de casino.guru el cual permite consumir la demo del presente juego. 
- **Método**: GET
- **Endpoint**: `https://es.casino.guru/embedGame?identifier=595a7c05-489c-49d6-8649-19d40b15ff7a`
- **Contacto**: `https://www.yggdrasilgaming.com/contact`


### API Street Fighter II - Proveedor: NetEnt GAMING

- **Descripción**: Street Fighter II es una tragamonedas de NetEnt, se solicita en el sitio deb del proveedor por correo electronico información de costos y documentacion de la API, se encuentra a la espera de respuesta del correo enviado al proveedor del juego, se agrega enlace de casino.guru el cual permite consumir la demo del presente juego. 
- **Método**: GET
- **Endpoint**: `https://es.casino.guru/embedGame?identifier=595a7c05-489c-49d6-8649-19d40b15ff7a`
- **Contacto**: `https://games.netent.com/es/contact-us/`

### Otros proveedores a los que se envian peticiones

- **Endpoint**: `https://uplatform.com/contact-us` - Ruby Play
- **Endpoint**: `https://www.kaga88.com/` - Ka gaming
- **Endpoint**: `https://slotegrator.pro/apigrator.html` integrador de juegos de casino
- **Endpoint**: `https://nuxgame.com/es` integrador de juegos de casino y deporte  
- **Endpoint**: `https://www.softgamings.com/` integrador de juegos de casino y deporte  



Estos son los proveedores de juegos de casino registrados en el sitio web casio. `https://casinozeus.vip/.`

---

- **Informe realizado por:**
¡Enoc Soto Arenilla!
