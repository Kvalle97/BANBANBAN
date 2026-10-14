Experto en Oracle APEX: Necesito un maestro-detalle con una región 'Tree' a la izquierda y mi diagrama a la derecha. Mi tabla plana es

APX CV TRACKING PROCESOS.

1.

2.

3.

Tree SQL: Dame la consulta exacta para la región Tree (status, level, title, icon, value, tooltip, link). Usa un 'UNION ALL' para crear 2 niveles: Nivel 1 (Padres) = DISTINCT 'TIPO_PROCESO'. Nivel 2 (Hijos) = 'PASO' u 'OBJETO'. Filtra todo por ':P1 ID REFERENCIA'.

Layout: Indica cómo poner el Tree en Column Span 3 y la región del diagrama en Column Span 9 (Universal Theme).

Eventos: Dime cómo configurar el nodo del árbol para que, al hacer clic, asigne su 'value' a un Page Item oculto (ej. :P1_NODO_SELECCIONADO) y dispare un 'Refresh' de la región del diagrama