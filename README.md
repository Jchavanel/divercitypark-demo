# DiverCityPark · demo para testers

**Abre la web:** https://jchavanel.github.io/divercitypark-demo/

**Android:** descarga la APK en [Releases](https://github.com/Jchavanel/divercitypark-demo/releases/latest) e instálala (hay que permitir «instalar apps de origen desconocido»).

DiverCityPark ayuda a encontrar plazas de aparcamiento para personas con movilidad reducida en Las Palmas de Gran Canaria (piloto: Guanarteme y Mesa y López) y a saber si se pueden usar.

## Novedades de la versión 0.7.0

- En el mapa todas las plazas llevan el símbolo de silla de ruedas. El estado (libre, ocupada, fuera de servicio o sin estado) aparece al tocar la plaza y en su ficha.
- Un aviso de libre u ocupada dura 60 minutos; después la plaza vuelve a «Sin estado».
- Nuevo botón **«No se puede usar (fuera de servicio)»** en la ficha. Ese aviso no caduca: la plaza sigue fuera de servicio hasta que alguien confirme que está libre u ocupada.
- Si ya habías usado la demo, pulsa **Perfil → Restablecer datos de demostración** para ver los ejemplos nuevos (por ejemplo, Calle República Dominicana aparece fuera de servicio por el aviso de un usuario).

## Antes de empezar

- Es una **demostración con datos de ejemplo**: las plazas están sobre calles reales, pero sus datos y los avisos son ficticios.
- Los datos se guardan **solo en tu navegador o en tu móvil**. Lo que hagas no lo ve nadie más, y si borras los datos del navegador se pierde.
- Para volver a empezar: **Perfil → Restablecer datos de demostración**.
- El mapa y la búsqueda de direcciones necesitan conexión a internet.

## Cuentas para probar

En la pantalla de inicio puedes entrar como invitado o con un botón por cada cuenta. Todas usan la contraseña `demo1234`.

| Cuenta | Para probar |
|---|---|
| laura@demo.divercitypark.es | Ciudadana con avisos en distintos estados |
| carlos@demo.divercitypark.es | Otro ciudadano |
| moderacion@demo.divercitypark.es | Revisar avisos y fotos |
| admin@demo.divercitypark.es | Todo lo anterior, usuarios, alta y eliminación de plazas |

Si no estás en Guanarteme, en la ficha de una plaza puedes pulsar **«Simular que estoy aquí»** para probar la confirmación de libre, ocupada o fuera de servicio.

---

Este repositorio solo contiene la versión compilada de la app. El código fuente no está aquí.
