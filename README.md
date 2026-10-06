Experto en Oracle APEX y Base de Datos: Necesito implementar un tracking de estados. Dame exactamente dos cosas, sin introducciones:

1.

2.

Script DDL: Crea la tabla

'MO PACKAGES TRACKING' con las columnas: tracking_id (PK identity), package_id (number), estado_nuevo (varchar2), fecha_registro (timestamp default systimestamp), usuario (varchar2) y observaciones (varchar2).

Configuración APEX: Dame los pasos en Page Designer y el query SQL exacto para crear una región de tipo 'Timeline' que lea esta tabla. El query debe filtrar por el ítem ':P1_PACKAGE_ID' y mapear: 'estado_nuevo' como Título, 'fecha_registro' como Fecha, y 'usuario/ observaciones' como Descripción. Solo código y

pasos."

Con este texto, Copilot