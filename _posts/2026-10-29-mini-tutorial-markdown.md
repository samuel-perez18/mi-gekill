---
title: "Mi Markdown"
---
# Mini Tutorial de Sintaxis Markdown

## Aprende a Documentar Proyectos de Forma Sencilla

Markdown es un lenguaje de marcado ligero que permite aplicar formato a un texto de forma rápida y legible, tanto en su versión en texto plano como una vez renderizado en plataformas como GitHub.

---

## 1. Encabezados y Formato de Texto

Para crear títulos en Markdown se utiliza el símbolo `#` al inicio de la línea. Cuantos más símbolos `#` incluyas, menor será el tamaño del encabezado.

Por ejemplo, un `#` genera un **H1** (título principal) y `##` genera un **H2** (subtítulo).

Dentro de un párrafo podemos aplicar distintos estilos de texto:
- Para aplicar **negrita**, envolvemos el texto entre dos asteriscos: `**texto en negrita**`.
- Para aplicar *cursiva*, usamos un solo asterisco: `*texto en cursiva*`.
- Para resaltar `código en línea`, utilizamos comillas invertidas simples: `` `código` ``.

---

## 2. Bloques de Código Multilínea

Cuando necesitamos incluir scripts o bloques de código más extensos, utilizamos tres comillas invertidas al inicio y al final del bloque. Podemos especificar el lenguaje (por ejemplo, `bash` o `python`) para que GitHub aplique resaltado de sintaxis:

```bash
#!/bin/bash
# Ejemplo de script en Debian para verificar el repositorio Git
echo "=== Estado del repositorio actual ==="
git status
```
---

## 3. Listas Organizadas

Markdown permite estructurar la información mediante dos tipos de listas:

### Lista Ordenada (Pasos secuenciales)
1. Clonar o vincular el repositorio Git en la máquina virtual.
2. Crear la estructura de carpetas `/docs` y `/assets`.
3. Redactar los documentos en formato `.md`.

### Lista Desordenada (Elementos sin orden específico)
- Compatibilidad nativa con GitHub y GitLab.
- Sintaxis limpia y fácil de leer sin renderizar.
- Soporte para enlaces, tablas e imágenes locales o remotas.

---

## 4. Enlaces y Documentación Relacionada

Los enlaces se crean utilizando corchetes para el texto visible `[Texto]` y paréntesis para la dirección `(URL)`:

- **Enlace externo:** Puedes consultar más detalles en la [Guía Oficial de Markdown](https://tutorialmarkdown.com/sintaxis-extendida).
- **Enlace relativo interno:** Consulta el archivo secundario con los [Detalles adicionales del proyecto](docs/detalles.md).

---

## 5. Tablas de Información

Las tablas en Markdown se construyen combinando barras verticales `|` para separar columnas y guiones `-` para definir la cabecera:

| Elemento Markdown | Sintaxis de Ejemplo | Resultado Renderizado |
| :--- | :---: | :--- |
| Encabezado H3 | `### Título` | Título de nivel 3 |
| Enlace | `[Nombre](URL)` | Hipervínculo ejecutable |
| Código en línea | `` `comando` `` | Texto monoespaciado |

---

## 6. Gestión e Inserción de Imágenes

### Imagen Local (Ruta Relativa)
Para insertar una imagen almacenada en la carpeta `/assets/`, usamos la sintaxis `![Texto alternativo](ruta-relativa)`:

![Diagrama o Imagen Local del Proyecto]({{ '/assets/images/mi-imagen.png' | relative_url }})

### Imagen Externa (Wikimedia / EducaMadrid)
Para insertar una imagen alojada en un servidor remoto o Wikimedia Commons, utilizamos su URL directa:

![Dos de Mayo por Joaquín Sorolla - IES Clara del Rey](https://site.educa.madrid.org/ies.claradelrey.madrid//wp-content/uploads/ies.claradelrey.madrid/2026/03/Dos_de_mayo_por_Joaquin_Sorolla-1.jpg)

<<<<<<< HEAD
edit rama main
=======
edit ramas
>>>>>>> segunda
