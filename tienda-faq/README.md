# Brisa Store — Agente de preguntas frecuentes

Agente de atención al cliente de una tienda online (ropa y accesorios).

> **Importante:** todos los datos de `docs/negocio.md` son **de ejemplo, inventados**. Reemplazalos por los de tu tienda real antes de usar el agente con clientes.

## Estructura

```
tienda-faq/
├── AGENTS.md                 # Reglas del agente
├── README.md                 # Este archivo
└── docs/
    ├── negocio.md            # Fuente de verdad: datos, envíos, pagos, cambios
    ├── glosario.md           # Términos de la tienda
    ├── preguntas-abiertas.md # Lo que todavía no está definido
    └── pruebas-agente.md     # 20 preguntas para comprobar que no inventa
```

## Cómo usarlo

1. Reemplazá los datos de ejemplo en `docs/negocio.md` por los reales.
2. Abrí la carpeta en Cursor o Claude Code (o cargá los archivos como contexto en un proyecto).
3. Empezá un chat nuevo y hacé las preguntas de `docs/pruebas-agente.md`, una por vez.
4. Anotá los resultados. Si inventa, cambiá UNA instrucción de `AGENTS.md` y repetí.
5. Cuando una duda no tenga respuesta, anotala en `docs/preguntas-abiertas.md` y definila en `negocio.md`.
