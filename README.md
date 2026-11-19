# IA Bajo Control: de prompts débiles a profesionales

Proyecto intermodular 0616 · 2º DAW · 1.ª evaluación · curso 2026/2027.
Autores: Marc Penadés Roig y Alejandro Company del Olmo (grupo 8).

## Estructura

```
Entrega/
├── docs/
│   ├── Introduccion_al_Proyecto.pdf        introducción al proyecto (redactada por el equipo)
│   └── Memoria_del_Proyecto.pdf            memoria final (tablas, figuras, referencias APA 7, anexos)
├── Prompts/
│   └── P_01_… a P_08_…                     una carpeta por caso, con 2 .txt:
│        P_0X_prompt_debil.txt              el prompt débil
│        P_0X_prompt_fuerte.txt             el prompt fuerte, literal
├── Respuestas/
│   └── R_01_… a R_08_…                     una carpeta por caso, con 2 .txt:
│        R_0X_respuesta_debil.txt           respuesta al prompt débil
│        R_0X_respuesta_fuerte.txt          respuesta al prompt fuerte
└── README.md
```

## Los ocho casos

| Código | Caso                             | Prompt débil                            |
| ------ | -------------------------------- | --------------------------------------- |
| 01     | Web de reservas                  | «Hazme una página web de reservas»      |
| 02     | Revisión de código JavaScript    | «Revisa este código JavaScript»         |
| 03     | Explicación de PHP               | «Explícame PHP»                         |
| 04     | Base de datos para una tienda    | «Haz una base de datos para una tienda» |
| 05     | Creación de una API              | «Crea una API»                          |
| 06     | Diseño web accesible             | «Hazme un diseño bonito para una web»   |
| 07     | Búsqueda de errores en el código | «Encuentra errores en este código»      |
| 08     | Documentación del proyecto       | «Haz la documentación de mi proyecto»   |

## Origen de los archivos

- `docs/Introduccion_al_Proyecto.pdf` es una introducción propia al proyecto: objetivos, agencia, ocho casos, fases, método de los prompts y contenido de la entrega.
- `docs/Memoria_del_Proyecto.pdf` es la memoria redactada desde cero siguiendo los apartados del enunciado, con tablas, figuras, referencias APA 7 y dos anexos (prompts completos y plantillas). El cuerpo ocupa 12 páginas sin portada ni referencias.
- Los `.txt` de `Prompts/` reproducen literalmente los prompts del apartado 3 de la memoria, con sus erratas.
- Los `.txt` de `Respuestas/` contienen el texto de las respuestas de la IA extraído de `PROYECTO_INTERMODULAR_1 (1).pdf` (respuestas débiles del apartado 3 y 4.3; respuestas fuertes de los Anexos 1–8). En los casos 4 y 6 se incluye también la respuesta de ChatGPT al prompt débil.
