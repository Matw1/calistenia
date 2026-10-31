# Calistenia

App offline de entrenamiento de calistenia. El instructor escribe cada sesión en Notion; la app la muestra, registra cada serie (reps o segundos, kg, RIR, lado, variante), los descansos, las isometrías, el EMOM/AMRAP, las molestias y los clips de técnica, y entrega el registro a Notion. **La app nunca califica.**

**App:** https://matw1.github.io/calistenia/ — en Chrome del celular: ⋮ → «Instalar app».

## Actualizar
1. Edita `src/calistenia.html`.
2. `node build.js` (regenera `index.html` y sube la versión del caché).
3. Commit y push.

`make-icons.js` regenera los íconos.
