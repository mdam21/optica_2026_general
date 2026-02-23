# Capítulo de Óptica: Teoría y versionado de instrumentación.

Este repsotiorio contiene el desarrollo integral de un telescopio y un espectrofluorómetro, inclcuyendo todos los archivos necesarios para dar fin a este objetivo. Así mismo como sugerencias de materiales y posibles futuras mejoras. Además se añade el apartado de teoría donde se fundamentará teóricamente todos los talleres para entender a profundidad las actividades que se realizará. 

## Estructura del proyecto
```
/
├── hardware/
│   ├── telescopio/
│   │   ├── cad/           # Archivos de software CAD
│   │   └── docs/          # Manual de ensamblaje
│   └── espectrofluorometro/
│       ├── cad/
│       ├── electronics/   # Esquemas de circuitos (Kicad/EasyEDA)
│       └── docs/          # Manual de ensamblaje
├── software/
│   ├── drivers/           # Control de sensore
│   ├── processing/        # Scripts generales Python
│   └── firmware/          # Código para microcontroladores
├── theory/                # Documentación teórica y principios físicos
├── guides/                # Guías de usuario y protocolos de laboratorio
└── README.md              # Mapa general del sitio
```

## Hardware y Diseño
Los modelos y ensamblajes están originalmente desarrollados en **Solidworks**, sin embargo se busca migrar a una **OneShape**. 
Se puede acceder a los modelos aquí:
www.olakease.com

## Autoría y Propiedad Intelectual
Este proyecto es propiedad intelectual de:
* ** Damián Andrango** - *Desarrollo principal y revisor de teoría*
* Jhon __ - Soporte en teoría y práctica
* Sebastián Calderón - Presidente y representante general del capítulo
* **Andrey Mereshchenkov** - Tutor responsable del Capítulo de Öptica YT

## Licencia
Este proyecto posee licencia **MIT** para el código y software y **Creative Commons Atrbución-CompartirIgual 4.0 Internacional (CC BY-SA 4.0)** para la documentación y los diseños de hardware.

Esto permite:
* **Compartir:** Copiar y redistribuir el material en cualquier medio o formato.
* **Adaptar:** Remezclar, transformar y construir a partir del material para cualquier propósito.

**Bajo los términos:**
* **Atribución:** Se debe dar crédito de manera adecuada y proporcionar enlace a la licencia.
* **Compartir Igual:** Si reusas o transformas el material, se debe redistribuir las nuevas contribuciones bajo la mmisma licencia original.

---
*Proyecto desarrollado para el Capítulo de Óptica YT - 2026.*
