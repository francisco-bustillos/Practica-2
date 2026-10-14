# Qué es un SSG 
Un SSG (Static Site Generator) es una herramienta que genera las páginas de una web antes de que el usuario las visite. En vez de crear la página cuando una persona entra, el SSG crea todas las páginas por adelantado y las deja preparadas.

![](SSG.png)

# Compara Jekyll, Hugo y Astro a partir de tu investigación.

| **Aspecto a investigar** | **Jekyll** | **Hugo** | **Astro** |
| --- | --- | --- | --- |
| **Lenguaje:** | Ruby. | Go. | JavaScript / TypeScript. |
| **Año de aparición:** | 2008. Es el más veterano. | 2013. | 2021. Es el más moderno. |
| **Plantillas:** | Liquid. | Go templates. | Componentes .astro, y permite usar componentes de React, Vue o Svelte. |
| **Fortaleza:** | GitHub Pages lo integra de forma nativa, así que se puede publicar un sitio sin configurar nada más. | Es muy rápido, capaz de generar miles de páginas en pocos segundos. Se distribuye como un único ejecutable, sin dependencias complejas. | Por defecto no envía JavaScript al navegador y solo activa los componentes interactivos que lo necesitan. A esto se le llama arquitectura de islas. |
| **Velocidad de compilación:** | Media. Se nota en sitios con muchas páginas. | Muy alta. | Alta. |
| **Curva de aprendizaje:** | Baja, ideal para empezar. | Media, porque la sintaxis de las plantillas resulta menos intuitiva. | Media, sobre todo si no se conoce JavaScript. |
| **Inconveniente:** | Requiere instalar Ruby y sus dependencias, lo que a veces da problemas en Windows. | Para publicar en GitHub Pages hay que usar GitHub Actions. | Es más un framework web que un SSG puro, por lo que puede resultar más complejo para sitios muy simples. |
| **Ideal para:** | Blogs, portfolios y documentación sencilla. | Sitios grandes, blogs con muchos artículos y documentación extensa. | Webs modernas con buen rendimiento y partes interactivas puntuales. |

## Videos de referencia

Si quieres profundizar un poco más en el tema, aquí puedes ver un vídeo corto (menos de 5 minutos) que explica qué es un SSG y cómo funciona:

[¿Que es un Generador de Sitio Estático? - Static Site generator (SSG)](https://www.youtube.com/watch?v=osWfEtbP_sk)

Si quieres conocer más sobre los CMS (Content Management Systems) y cómo funcionan, puedes consultar la siguiente información: [enlace](cms.md).