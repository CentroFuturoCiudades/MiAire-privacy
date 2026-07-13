# Política de Privacidad de HealthWind

*Última actualización: 13 de julio de 2026*

## Resumen

HealthWind es una aplicación informativa sobre calidad del aire desarrollada por el Tecnológico de Monterrey. Usamos tu ubicación únicamente para mostrarte información del sensor más cercano a ti. No creamos cuentas de usuario ni almacenamos datos personales identificables.

## Responsable del tratamiento de datos

El responsable del tratamiento de tus datos personales es:

**Instituto Tecnológico y de Estudios Superiores de Monterrey**
Av. Eugenio Garza Sada 2501 Sur, Tecnológico, Distrito Tec, 64700 Monterrey, Nuevo León, México.

## Información que recolectamos

### Ubicación

HealthWind solicita acceso a tu ubicación con precisión aproximada de 100 metros para:

- Encontrar el sensor de calidad del aire más cercano a ti.
- Mostrarte información relevante de tu zona en el mapa.

Puedes limitar esta precisión en cualquier momento activando la opción **"Ubicación precisa: Apagado"** en *Configuración > HealthWind > Ubicación*. En ese caso, iOS entregará a la app una ubicación aproximada (~3 km) y HealthWind seguirá funcionando con menor exactitud al calcular el sensor más cercano.

### Cómo procesamos tu ubicación

- Tu ubicación (latitud y longitud) se envía a nuestro servidor únicamente para calcular qué sensor está más cerca.
- El servidor está hospedado en **Microsoft Azure (West US 2, Estados Unidos)**. Microsoft actúa como procesador de datos bajo los términos del [Data Protection Addendum de Microsoft](https://www.microsoft.com/licensing/docs/view/Microsoft-Products-and-Services-Data-Protection-Addendum-DPA).
- Nuestra base de datos (**Azure Database for PostgreSQL**) almacena únicamente información pública de los sensores de calidad del aire; **no** guarda tu ubicación ni ningún dato personal de usuarios.
- **NO** almacenamos un historial de tus ubicaciones.
- **NO** asociamos tu ubicación con ningún identificador personal.
- La ubicación se usa solo en el momento de la consulta y se descarta inmediatamente después.

### Transferencia internacional de datos

Al usar HealthWind, aceptas que tu ubicación se transfiera temporalmente a servidores ubicados en **Estados Unidos** (Microsoft Azure, región West US 2) para su procesamiento. Esta transferencia se realiza:

- Únicamente para calcular el sensor más cercano a tu ubicación.
- Sin almacenamiento posterior de la ubicación transmitida.
- Bajo las garantías contractuales de Microsoft como procesador de datos.

Si no deseas que tu ubicación cruce fronteras internacionales, puedes revocar el permiso de ubicación en cualquier momento (ver sección "Tus derechos").

### Logs técnicos del servidor

Para operación y seguridad, nuestro servidor genera logs con dirección IP y marca de tiempo de la petición. Estos logs se retienen **máximo 30 días** y se eliminan automáticamente. **No contienen** el resultado de la consulta ni la ubicación enviada.

## Información que NO recolectamos

- No recolectamos nombre, email, teléfono ni datos de contacto.
- No requerimos crear una cuenta de usuario.
- No usamos cookies ni rastreadores.
- No recolectamos identificadores de dispositivo (IDFA, IDFV).
- No hacemos seguimiento de tu actividad entre sesiones.
- No compartimos datos con terceros para publicidad.
- No mostramos publicidad en la app.

## SDKs de terceros

HealthWind **no integra ningún SDK de analítica, publicidad o tracking**. Las únicas bibliotecas de terceros que utiliza la app son componentes de renderizado visual (imágenes y Markdown) que no envían datos a servidores externos.

## App Tracking Transparency (iOS)

HealthWind **no rastrea tu actividad** a través de aplicaciones o sitios web de otras compañías. Por lo tanto, no solicitamos el permiso de *App Tracking Transparency* de iOS.

## Datos de menores de edad

HealthWind no está dirigida a menores de 13 años y no recolecta intencionalmente información de menores. Si te enteras de que un menor nos ha proporcionado información, por favor contáctanos para eliminarla (aunque, como se detalla arriba, no almacenamos datos personales identificables).

## Permisos de la app

| Permiso | Uso | Obligatorio |
|---------|-----|-------------|
| Ubicación (cuando se usa) | Encontrar sensor cercano | No, pero la funcionalidad principal requiere ubicación |
| Notificaciones push | No solicitado | — |
| Cámara / Micrófono / Fotos | No solicitado | — |

## Seguridad

- Las comunicaciones con nuestro servidor usan **HTTPS (TLS 1.2+)**.
- No almacenamos tu ubicación ni datos que te identifiquen directamente. La única excepción son los logs técnicos (dirección IP y marca de tiempo) descritos en la sección *"Logs técnicos del servidor"*, que se conservan un máximo de 30 días con fines de seguridad y se eliminan automáticamente.
- La infraestructura de Microsoft Azure cumple con las certificaciones ISO 27001, SOC 2 y otras normas internacionales de seguridad.

## Tus derechos

### Control del permiso de ubicación

Puedes revocar el acceso a tu ubicación en cualquier momento:

1. Abre **Configuración** en tu iPhone.
2. Busca **HealthWind**.
3. Toca **Ubicación**.
4. Selecciona **"Nunca"** para revocar el permiso.

Si revocas el permiso de ubicación, podrás seguir usando la app para ver la lista de sensores y el mapa, pero no podremos mostrarte cuál es el sensor más cercano a ti.

### Derechos ARCO (Ley Federal de Protección de Datos Personales en Posesión de los Particulares — México)

Como titular de datos tienes derecho al **Acceso, Rectificación, Cancelación y Oposición** (derechos ARCO) del uso de tus datos personales. Aunque HealthWind no almacena datos personales identificables, puedes ejercer estos derechos o hacer cualquier pregunta relacionada con privacidad escribiendo a los contactos listados abajo.

## Marco legal

Esta política se rige por las leyes de los Estados Unidos Mexicanos, en particular la **Ley Federal de Protección de Datos Personales en Posesión de los Particulares (LFPDPPP)** y su Reglamento.

## Cambios a esta política

Si actualizamos esta política, publicaremos los cambios en esta página con la nueva fecha de actualización. Cambios sustanciales se anunciarán también dentro de la app.

## Contacto

Para preguntas sobre privacidad, ejercer tus derechos ARCO o cualquier tema relacionado con esta política, puedes contactar a:

- **Roberto Ponce López** — [rpl@tec.mx](mailto:rpl@tec.mx) *(responsable principal)*
- **Silke Alida Enkerlin Madero** — [silke@tec.mx](mailto:silke@tec.mx)
- **Lizzie Montserrat Cañamar Carrillo** — [lizziecc@tec.mx](mailto:lizziecc@tec.mx)

---

*HealthWind es un proyecto desarrollado por el Tecnológico de Monterrey.*
