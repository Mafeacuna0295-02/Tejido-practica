# Ejercicio de Pull Request: Textiles

Este mini-repositorio contiene documentación sobre tejidos, pensado para practicar
el flujo de trabajo de **fork → clone → branch → commit → pull request**.

## Archivos

* `tipos-de-tejidos.md`: clasificación de tejidos por origen y fabricación.
* `tecnicas-de-tejido.md`: técnicas de tejeduría (calada, punto, fieltro, etc).

## Cómo usarlo para practicar PRs

1. **Crea un repositorio en GitHub** y sube estos archivos (o pídele a alguien
que lo haga por ti como "repo base").
2. **Haz un fork** del repositorio a tu cuenta.
3. **Clónalo localmente**:

```bash
   git clone https://github.com/tu-usuario/tu-repo.git
   cd tu-repo
   ```

4. **Crea una rama nueva**:

```bash
   git checkout -b agrega-tejidos-mixtos
   ```

5. **Haz un cambio**, por ejemplo agrega una sección de "Tejidos mixtos" en
`tipos-de-tejidos.md`, o corrige algún error.
6. **Guarda el cambio (commit)**:

```bash
   git add tipos-de-tejidos.md
   git commit -m "Agrega sección de tejidos mixtos"
   ```

7. **Sube la rama**:

```bash
   git push origin agrega-tejidos-mixtos
   ```

8. **Abre un Pull Request** desde GitHub, comparando tu rama contra el
repositorio original (o el `main` de tu propio fork).

## Ideas de ejercicios (para practicar distintos tipos de PR)

* ✏️ Corregir una errata (PR pequeño, fácil de revisar).
* ➕ Agregar una nueva sección o archivo (por ejemplo, `historia-del-tejido.md`).
* 🌐 Traducir un archivo al inglés.
* 🔀 Resolver un conflicto de merge (edita la misma línea en dos ramas distintas).
* 🧵 Agregar una tabla comparativa de propiedades de fibras.
* Tejuncho no es solo tejidos también tiene accesorios
* 

