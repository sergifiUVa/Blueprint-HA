# Blueprint-HA
La que funciona correctamente es Prueba_medicina.

Para que funcione primero tienes qu crear un ayudante boolean para que "recuerde" que se ha tomado las medicinas, que se activará mediante otra automatización cuando te tomes la medicación (ya sea con un sensor de movimiento, un pulsador de confirmación o un sensor virtual que represente dicha actividad).

Puedes modificar el trigger de mqtt por un selector de hora modificando ligeramente la plantilla.
