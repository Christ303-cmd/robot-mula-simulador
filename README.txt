ROBOT MULA — FASE 21
Diseño fiel al plano, carga corregida y estabilidad adaptativa

CONTENIDO
- Modelo visual basado en el plano conceptual: dimensiones generales de referencia 200 x 65 x 95 cm.
- Cabeza cuadrada frontal con panel solar superior, luces LED y cámaras.
- Una única cápsula transparente alargada para proteger los cultivos.
- Caja agrícola central con nervaduras laterales.
- Compartimiento trasero para herramientas.
- Cuatro patas articuladas con actuadores, amortiguadores/vástagos visuales y apoyos de goma.
- Corrección semántica de escenarios: “Carga centrada” coloca la carga en el centro; “Carga lateral” desplaza la carga hacia la izquierda del robot (+Z).
- El cálculo de estabilidad pondera el centro de masa combinado del robot y la carga.
- La fuerza normal estimada considera el peso propio y la carga útil.
- La base de apoyo se ensancha moderadamente cuando la carga está desplazada.
- Mejor elevación anticipada de patas y compensación de postura amortiguada.
- Se evita marcar peligro solo por una pendiente pronunciada o por los dos apoyos diagonales normales del trote.

EJECUCIÓN EN WINDOWS
1. Extraer la carpeta completa del ZIP.
2. Abrir CMD dentro de la carpeta donde está index.html.
3. Ejecutar: py -m http.server 8000
4. Abrir: http://localhost:8000
5. Se necesita conexión a Internet para cargar Three.js y OrbitControls desde jsDelivr.
6. Detener el servidor con Ctrl+C.

PRUEBAS SUGERIDAS
1. Pulsar “Carga centrada”: debe indicar 35 kg, X centrado y lateral centrado.
2. Pulsar “Carga lateral”: debe indicar 35 kg, X centrado y lateral izquierda (+45%).
3. Comparar el margen de estabilidad en ambas configuraciones.
4. Probar marcha lenta y trote diagonal en terreno plano.
5. Probar terreno irregular y pendientes de 6° a 12°.

NOTA TÉCNICA
Es una simulación educativa y cinemática. Las dimensiones y el comportamiento son aproximados; no constituyen validación mecánica, estructural ni de estabilidad real para fabricar el robot.
