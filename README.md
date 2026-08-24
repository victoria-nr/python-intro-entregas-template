# Plantilla de entregas - Introducción a Python

Este repositorio sirve como plantilla para crear el repositorio privado personal de entregas de cada alumno.

## Nombre recomendado del repositorio

```text
python-intro-entregas-nombre-apellido
```

Ejemplo:

```text
python-intro-entregas-ana-garcia
```

## Estructura

```text
unidades/
├── u01-introduccion-python/
│   ├── README.md
│   ├── ejercicios/
│   │   ├── practicar/
│   │   └── entregar/
│   └── reflexion.md
├── u02-objetos-cadenas/
│   ├── README.md
│   ├── ejercicios/
│   │   ├── practicar/
│   │   └── entregar/
│   └── reflexion.md
├── u03-control-flujo-sysadmin/
│   ├── README.md
│   ├── ejercicios/
│   │   ├── practicar/
│   │   └── entregar/
│   └── reflexion.md
├── u04-poo-ampliacion/
│   ├── README.md
│   ├── ejercicios/
│   │   ├── practicar/
│   │   └── entregar/
│   └── reflexion.md
├── u05-estructuras-datos/
│   ├── README.md
│   ├── ejercicios/
│   │   ├── practicar/
│   │   └── entregar/
│   └── reflexion.md
└── u06-funciones-ficheros/
	├── README.md
	├── ejercicios/
	│   ├── practicar/
	│   └── entregar/
	└── reflexion.md
```

## Forma de trabajo

Para cada bloque de ejercicios de una unidad se recomienda crear una rama:

```bash
git checkout -b u01-introduccion-python-practicar
# o
git checkout -b u01-introduccion-python-entregar
```

Trabaja en la carpeta correspondiente:

```text
unidades/u01-introduccion-python/ejercicios/practicar/
# o
unidades/u01-introduccion-python/ejercicios/entregar/
```

Después de trabajar:

```bash
git add .
git commit -m "Completa ejercicio 1 de la unidad 1"
git push -u origin u01-introduccion-python-practicar
```

Cuando termines ese bloque de ejercicios, abre una Pull Request hacia `main`.

## Uso de IA

Puedes usar IA como apoyo, pero debes entender todo lo que entregas y declararlo en el archivo `reflexion.md` de cada unidad.
