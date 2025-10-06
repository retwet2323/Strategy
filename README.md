# Strategy
ejemplo de `patron q elimina el IF anidado ( si, se desean agregar mas condiciones..solo se agregan clases)

Ambos ejemplos aplican el patrón Strategy: encapsulan comportamientos en clases separadas y el contexto sólo delega a estas. Pero el primero usa inyección de dependencias para pasar la estrategia, lo que mejora modularidad y testabilidad. El segundo crea las estrategias internamente, acoplando más el contexto y dificultando cambios o pruebas.
