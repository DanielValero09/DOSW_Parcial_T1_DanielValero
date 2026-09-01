# DOSW - Parcial Práctico Primer Tercio

## Información del estudiante

- **Nombre:** Daniel Valero
- **Grupo:** [ESCRIBIR GRUPO DE DOSW]
- **Enunciado:** [Se completará durante el parcial]

---

## Herramientas

### Herramienta de modelado

Herramienta seleccionada: **[Lucidchart / Draw.io / Miro]**

![Evidencia herramienta de modelado](docs/images/Lucid.png)

### Figma

Evidencia de acceso a Figma:

![Evidencia Figma](docs/images/Figma.png)

---

## Proyecto Maven

El proyecto Maven fue configurado con:

- **groupId:** `edu.dosw.parcial`
- **artifactId:** `DOSW-ParcialT1`

### Evidencia de ejecución

![Evidencia Maven](docs/images/Maven.png)

---

## Estructura del proyecto

```text
.
├── pom.xml
├── src/
│   ├── main/
│   │   └── java/
│   │       └── edu/dosw/parcial/
│   └── test/
│       └── java/
│           └── edu/dosw/parcial/
├── docs/
│   ├── uml/
│   ├── images/
│   └── requirements/
├── .gitignore
└── README.md

```


## PUNTO 1
Diagrama de contexto:
![Diagrama contexto](docs/images/diagramaContexto.png)



## PUNTO 2
5 REQUERIMIENTOS DEL SISTEMA: 3 FUNCIONALES Y 2 NO FUNCIONALES. 1 CON BUILDER Y 1 CON DECORATOR

-**FUNCIONALES:**

**1.** Un pedido puede contener hasta 5 productos diferentes. (BUILDER)

**2.** Cada producto base puede tener sus propios extras. (DECORATOR)

**3.** El precio minimo de un pedido es de $3.500

-**NO FUNCIONALES:**

**1.** El sistema debe responder en <= 1.5s para el 990% de las peticiones

**2.** Colores de la cafeteria: Azul (#1B3A5C) y Dorado (#C67A00)



## PUNTO 3

2 REQUERIMIENTOS FUNCIONALES MAS IMPORTANTES

Diagrama caso de uso
![Diagrama caso de uso](docs/images/diagramaCasoUso.png)
RF-01 — Armar pedido personalizado (patrón Builder):
El sistema debe permitir que el usuario (estudiante o docente) arme un pedido seleccionando un producto base, agregando una o más opciones de extras, y eligiendo un tipo de entrega, construyendo el pedido paso a paso mediante el patrón Builder.

RF-02 — Calcular precio final del pedido (patrón Decorator):
El sistema debe calcular y mostrar en tiempo real el precio final del pedido, sumando dinámicamente el costo de cada extra seleccionado sobre el precio base, usando el patrón Decorator.
Historias de usuario

RF-01: Como estudiante o docente, quiero armar mi pedido eligiendo un producto base, agregando extras y escogiendo el tipo de entrega paso a paso, para personalizar mi comida sin complicaciones.

RF-02: Como estudiante o docente, quiero ver el precio final de mi pedido actualizado en tiempo real a medida que agrego extras, para saber exactamente cuánto voy a pagar antes de confirmar.


# DOSW_Parcial_T1_DanielValero
https://github.com/DanielValero09/DOSW_BITACORA.git
# DOSW_Parcial_T1_DanielValero
https://github.com/DanielValero09/DOSW_BITACORA.git
