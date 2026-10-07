Experto en Oracle APEX y PL/SQL: Tengo la tabla 'APX_CV_TRACKING_PROCESOS' (columnas: id_tracking, id_referencia, paso, estado, fecha_registro). Quiero generar un diagrama de flujo dinámico con Mermaid.js basado en la secuencia histórica de un proceso.
​Dame el código exacto para una región de 'PL/SQL Dynamic Content' en APEX. El código debe:
​Imprimir <div class="mermaid"> graph LR;
​Usar un cursor con la función analítica LEAD(paso) OVER (ORDER BY id_tracking) para obtener el 'siguiente_paso' filtrando por :P1_ID_REFERENCIA.
​Imprimir las conexiones (ej: paso --> siguiente_paso).
​Aplicar estilos a los nodos según su 'estado' (OK = verde, ERROR = rojo, PROCESANDO = amarillo).
​Dame solo el código PL/SQL (con HTP.P) y la URL del CDN de Mermaid para poner en las propiedades de la página."