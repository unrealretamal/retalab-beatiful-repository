<p align="right">
  <a href="./README.md">English</a> · <strong>Español</strong> · <a href="./README.de.md">Deutsch</a>
</p>

<p align="center">
  <img src="./assets/readme/en/hero.gif" width="100%" alt="Beautify GitHub README: ayuda a los visitantes a entender un repositorio a primera vista.">
</p>

<p align="center">
  <img src="./assets/readme/en/theme-wall.svg" width="100%" alt="Seis direcciones de README nativas del proyecto para herramientas de desarrollo, productos de IA, recursos de diseño, investigación, proyectos de creadores y bibliotecas de código abierto.">
</p>

Organiza y diseña READMEs de repositorios para que el valor del proyecto, los ejemplos reales, las rutas de instalación y los límites de uso sean más fáciles de entender.

A continuación se muestran cuatro direcciones de héroe independientes. No comparten un mismo estilo; cada una deriva su tipografía, color, composición y prueba del propio proyecto.

<p align="center">
  <img src="./assets/readme/en/case-kubernetes.svg" width="100%" alt="Ejemplo de héroe README de Kubernetes con un diseño de sistema negro y diagrama de relaciones de clúster.">
</p>

<p align="center">
  <img src="./assets/readme/en/case-postgresql.svg" width="100%" alt="Ejemplo de héroe README de PostgreSQL con un diseño editorial azul profundo y tablas relacionales.">
</p>

<p align="center">
  <img src="./assets/readme/en/case-block-world.png" width="100%" alt="Héroe README híbrido de Block World que combina composición SVG estilo píxel con un personaje constructor generado por IA.">
</p>

**Block World** muestra una dirección híbrida y lúdica: SVG construye la tipografía pixelada, la cuadrícula, las etiquetas y la estructura de la escena, mientras que ImageGen y la eliminación de chroma-key suministran el personaje que sería engorroso dibujar de forma determinista.

<p align="center">
  <img src="./assets/readme/en/case-wolfcha.png" width="100%" alt="Héroe README híbrido de Wolfcha que combina tipografía SVG precisa y gráficos de mesa con un maestro de juego lobo generado por IA.">
</p>

<p align="center">
  <img src="./assets/readme/en/section-why.svg" width="100%" alt="01 Haz que el proyecto sea claro antes de pedir a la gente que siga leyendo.">
</p>

La mayoría de los repositorios ya contienen suficiente información. El problema suele ser el orden: los visitantes ven terminología interna, comandos de instalación y árboles de directorios antes de entender para qué sirve el proyecto.

`beautify-github-readme` primero lee el repositorio real, identifica el valor y la prueba más clara, y solo entonces decide cómo debe verse la página.

<p align="center">
  <img src="./assets/readme/en/before-after.svg" width="100%" alt="Un README que pasa de información densa sin un punto de entrada claro a una secuencia de valor, prueba, método y primer uso.">
</p>

En modo README completo, trabaja en tres capas:

| Contenido | Sistema visual | Ingeniería |
| --- | --- | --- |
| Eliminar repetición, adelantar la prueba y reemplazar la jerga interna con resultados concretos | Derivar color, tipografía, composición y motivos nativos del proyecto antes de diseñar el héroe y los módulos de soporte | Mantener los activos seguros para GitHub, las imágenes accesibles, los comandos copiables y el texto del cuerpo buscable |

Proyectos diferentes no deben recibir la misma plantilla. Una CLI puede usar ritmo de comandos y cursores; un sistema de iconos puede usar líneas clave y recortes; un repositorio de investigación puede usar coordenadas, gráficos y etiquetas de evidencia.

<p align="center">
  <img src="./assets/readme/en/section-method.svg" width="100%" alt="02 Pon la identidad visual en SVG y el contenido legible en Markdown.">
</p>

Los READMEs de GitHub no tienen la libertad de diseño de un sitio web. Esta Skill separa las capas visual y de contenido:

- SVG maneja héroes editables, transiciones de sección, comparaciones, diagramas e identidad.
- La composición SVG híbrida combina el diseño SVG determinista con sujetos opcionales generados por IA y sin fondo para personajes, textura orgánica, materiales complejos e iluminación cinematográfica.
- GIF maneja el movimiento aprobado mientras que el SVG estático sigue siendo el respaldo editable.
- El movimiento es opcional y nunca se genera por defecto.
- PNG/WebP maneja capturas de pantalla, arte generado y muros de exhibición complejos.
- Markdown maneja explicaciones, comandos, enlaces, configuración y detalles de contribución.

El resultado puede sentirse diseñado sin convertirse en una imagen larga que nadie puede buscar, copiar o mantener.

La guía de producción reutilizable se encuentra aquí:

- [Diseñar un héroe nativo del proyecto](./skills/beautify-github-readme/references/project-native-hero.md)
- [Escribir SVGs README seguros para GitHub](./skills/beautify-github-readme/references/svg-production.md)
- [Componer SVG con material ráster generado](./skills/beautify-github-readme/references/hybrid-svg-production.md)
- [Producir movimiento README seguro para GitHub](./skills/beautify-github-readme/references/motion-production.md)

<p align="center">
  <img src="./assets/readme/en/workflow.svg" width="100%" alt="Comprender el proyecto, definir la dirección, estructurar el contenido, construir los visuales y revisar la vista previa.">
</p>

El proceso mantiene tres promesas: usar material real del proyecto, nunca inventar capacidades y nunca publicar sin aprobación explícita.

<p align="center">
  <img src="./assets/readme/en/section-use.svg" width="100%" alt="03 Envía el repositorio a tu Agente.">
</p>

**Opción 1 · Instalar desde la línea de comandos**

```bash
npx skills add unrealretamal/retalab-beatiful-repository
```

**Opción 2 · Pide a tu Agente que lo instale**

```text
Instala esta Skill: https://github.com/unrealretamal/retalab-beatiful-repository
```

La Skill tiene dos modos explícitos:

| Modo | Qué cambia | Qué deja sin cambios por defecto |
| --- | --- | --- |
| README completo | Orden de lectura, jerarquía de contenido, prueba, Markdown y el sistema visual completo | No hará commit, push ni publicará sin aprobación |
| Solo activos | Un héroe SVG estático, encabezados de sección, flujo de trabajo, insignia, diagrama o un GIF opcional seguro para GitHub con fuente SVG | No editará el texto del README, orden, referencias de imágenes ni enlaces |

Si la solicitud ya indica el alcance, la Skill comienza directamente. Si un usuario solo dice "embellece este repositorio" o proporciona una URL de repositorio, el Agente pregunta:

```text
¿Quieres que mejore todo el README o solo cree activos visuales?
Si solo activos, ¿necesitas un héroe, encabezados de sección, flujo de trabajo, insignia, gráfico animado o un conjunto coordinado?
```

**Modo README completo**

```text
Usa $beautify-github-readme para rediseñar la página de inicio de este repositorio en torno a su tema real del proyecto.
Muéstrame una vista previa local primero y no hagas push de nada.
```

**Modo solo activos**

```text
Usa $beautify-github-readme para mantener el README sin cambios y crear un héroe GIF animado con su fuente SVG.
Deriva el estilo del proyecto existente y muéstrame la vista previa renderizada primero.
```

Leer un README para contexto no otorga permiso para editarlo. En modo solo activos, incrustar los nuevos activos requiere una aprobación explícita por separado.

También puedes solicitar una auditoría de solo lectura:

```text
Usa $beautify-github-readme para auditar este README en claridad, jerarquía, confianza y costo de mantenimiento. No edites archivos.
```

El modo README completo entrega una vista previa local, activos visuales y un diff del README. El modo solo activos entrega activos fuente, vistas previas renderizadas, derivados GIF opcionales y fragmentos de inserción. Los commits, pushes, PRs y publicaciones siempre requieren autorización explícita.

Licencia MIT

---

Este README es también un ejemplo funcional: combina un héroe nativo del proyecto, un muro temático, ejemplos ilustrativos, transiciones de sección y Markdown legible en lugar de rasterizar toda la página.

## Configuración, Dependencias y Límites de Uso

Markdown/SVG en sí no requiere cuenta ni API Key; generar PNG/WebP o usar generación de imágenes por IA requiere las herramientas de renderizado y generación autorizadas correspondientes.

No inventes estrellas, rendimiento, usuarios ni respaldos de marca; después de las modificaciones, revisa los enlaces, los activos y la renderización real. La publicación y fusión cumplen con la autorización de la tarea actual.

Ejemplo de uso:

```text
Embellece la página de inicio del README de este repositorio, conservando los hechos reales del proyecto.
```
