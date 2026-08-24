# Instrucciones para crear tu repositorio privado de entregas

## 1. Crear el repositorio desde la plantilla

1. Entra en el repositorio plantilla indicado por el profesor.
2. Pulsa **Use this template**.
3. Elige **Create a new repository**.
4. Pon este nombre:

```text
python-intro-entregas-nombre-apellido
```

5. Marca la visibilidad como **Private**.
6. Crea el repositorio.

## 2. Invitar al profesor

1. Entra en tu nuevo repositorio privado.
2. Ve a **Settings**.
3. Entra en **Collaborators** o **Collaborators and teams**.
4. Pulsa **Add people**.
5. Añade el usuario de GitHub del profesor.
6. Envía la invitación.

## 3. Clonar el repositorio

```bash
git clone URL_DE_TU_REPOSITORIO
cd python-intro-entregas-nombre-apellido
```

## 4. Trabajar por ramas

Para cada bloque de ejercicios, crea una rama nueva:

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

## 5. Hacer commits frecuentes

No subas todo el trabajo en un único commit final.

Ejemplo:

```bash
git status
git add .
git commit -m "Completa ejercicio 1 de la unidad 1"
git push -u origin u01-introduccion-python-practicar
```

## 6. Abrir Pull Request

Cuando termines un bloque de ejercicios de practicar o entregar:

1. Entra en GitHub.
2. Abre una Pull Request desde tu rama hacia `main`.
3. En la descripción indica qué ejercicios has completado, si pertenecen a `practicar` o a `entregar`, y si has usado IA.
4. No hagas merge hasta que el profesor lo indique.

## 7. Uso permitido de IA

Puedes usar IA para:

- pedir explicaciones;
- encontrar errores;
- comparar alternativas;
- mejorar comentarios;
- pedir ejemplos parecidos.

No debes usar IA para entregar código que no entiendes.

En cada unidad debes completar `reflexion.md`.
