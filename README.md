# DiverCityPark · demo para testers

**Abre la web:** https://jchavanel.github.io/divercitypark-demo/

**Android:** descarga la APK en [Releases](https://github.com/Jchavanel/divercitypark-demo/releases/latest) e instálala (hay que permitir «instalar apps de origen desconocido»).

DiverCityPark ayuda a encontrar plazas de aparcamiento para personas con movilidad reducida en Las Palmas de Gran Canaria (piloto: Guanarteme y Mesa y López) y a saber si se pueden usar.

## Novedades de la versión 0.9.0

- **La demo ya trae el listado real de plazas PMR del equipo: 243 plazas**, en sus puntos exactos, con su número de plazas, si están verificadas y sus observaciones. No hace falta importar nada.
- Al abrir esta versión, la demo se regenera sola con el listado (se pierden las pruebas que hubieras hecho antes).
- Administración puede importar plazas desde un Excel o un CSV en **Panel → Plazas registradas → Importar desde Excel o CSV**: antes de importar se ve qué filas entran, cuáles ya están registradas y cuáles tienen problemas.

## Novedades de la versión 0.8.0

- Con las cuentas de moderación o administración, en **Panel → Plazas registradas** se ven todas las plazas, también las dadas de baja, con filtros y buscador.
- Desde esa lista se edita cualquier plaza y se da de alta una nueva eligiendo el punto en un mapa (no hace falta estar allí); la dirección se rellena sola con la calle más cercana.
- Administración puede eliminar con la papelera una plaza que ya no existe.

## Novedades de la versión 0.7.0

- En el mapa todas las plazas llevan el símbolo de silla de ruedas. El estado (libre, ocupada, fuera de servicio o sin estado) aparece al tocar la plaza y en su ficha.
- Un aviso de libre u ocupada dura 60 minutos; después la plaza vuelve a «Sin estado».
- Nuevo botón **«No se puede usar (fuera de servicio)»** en la ficha. Ese aviso no caduca: la plaza sigue fuera de servicio hasta que alguien confirme que está libre u ocupada.
- Si ya habías usado la demo, pulsa **Perfil → Restablecer datos de demostración** para ver los ejemplos nuevos (por ejemplo, Calle República Dominicana aparece fuera de servicio por el aviso de un usuario).

## Antes de empezar

- **Las plazas son reales** (el listado del equipo). **Los estados (libre, ocupada, fuera de servicio), los avisos, los comentarios y las estadísticas son de ejemplo** para poder probar la app: no reflejan la situación real de esas plazas.
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
