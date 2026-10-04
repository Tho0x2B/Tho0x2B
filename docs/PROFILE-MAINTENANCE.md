# Mantenimiento del perfil

## Tarjeta de actividad

El README muestra un SVG generado por [GitHub Readme Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats). La URL original del servicio, no una URL de caché de Camo, es:

```text
https://streak-stats.demolab.com/?user=Tho0x2B&hide_border=false&background=18181b&border=52525b&stroke=3f3f46&ring=fbbf24&fire=18181b&currStreakNum=fafafa&sideNums=fafafa&currStreakLabel=fbbf24&sideLabels=d4d4d8&dates=a1a1aa&border_radius=0&card_width=560&card_height=190&locale=es&timezone=America%2FBogota&disable_animations=true
```

- `user`: cuenta consultada.
- `locale=es`: etiquetas en español.
- `timezone=America/Bogota`: zona horaria para determinar el día actual.
- `disable_animations=true`: presenta las cifras inmediatamente; las animaciones decorativas del perfil permanecen en los tres SVG locales.
- Diseño sin tema predefinido: fondo grafito, acentos ámbar, texto neutro, marco visible y esquinas rectas. `fire` coincide con el fondo para ocultar la llama decorativa.
- `background`, `border`, `ring`, `fire`, `stroke` y colores de texto: apariencia de la tarjeta. `card_width=560` y `card_height=190` definen sus proporciones.
- Las cifras se calculan desde los datos de contribuciones disponibles, no se escriben manualmente. No representan todos los commits ni un nivel de experiencia.

GitHub sirve imágenes externas mediante Camo y puede almacenar en caché su respuesta. El servicio externo puede sufrir caídas o límites; el enlace textual permite consultar la actividad directamente. Esta integración no contiene tokens ni secretos y no se ha configurado ningún workflow ni servicio propio.

Como alternativa, el proyecto de Streak Stats permite generar un SVG con GitHub Actions y guardarlo en el repositorio. Esa opción exige configurar un workflow y permisos de escritura. No debe añadirse un token al README ni al código público.

## Animaciones

`assets/header.svg`, `assets/calculator.svg` y `assets/game.svg` incorporan animaciones CSS dentro del propio SVG. Se insertan en el README con etiquetas `img`; no requieren JavaScript, fuentes externas ni generación periódica.

Las animaciones indican movimiento decorativo e ilustrativo, no actividad real de una FPGA. Cada gráfico se inserta mediante `picture`: su `source` selecciona el SVG `-static.svg` cuando se solicita `prefers-reduced-motion: reduce`. Además existe una regla CSS interna de movimiento reducido. El texto se mantiene estático y legible.

## Tecnologías comprobadas

- VHDL y diseño para FPGA: `Tho0x2B/Project1_2530_Disdi` y `Tho0x2B/Project2_2530_Disdi`.
- C y gráficos 3D: `Tho0x2B/3DEngine-ThomasLeal`.
- Java, jMonkeyEngine, Maven, H2, JUnit y SQL: `Samu-Kiss/UNI-25-30-FIS-NullPointerException`, su `pom.xml` y sus fuentes.
- Spring Boot, Java, HTML, CSS y JavaScript: `P1p2gamer26/Hotel-Macondo`, su `pom.xml` y sus fuentes.
- Angular y TypeScript: `Lunax320/hotel-macondo-frontend` y `package.json`.
- C# y Unity: `Tho0x2B/Proyecto-Ondas` y `Tho0x2B/Simple-Jam-2022-main`.
- Python: `P1p2gamer26/CODEFEST_2026-1`.
- Prolog: `SDM30/Proyecto1-Solucion-Problemas`.
- Kotlin y Android / Jetpack Compose: fuentes y manifiestos de un proyecto en equipo de acceso restringido; no se publican su nombre, sus enlaces ni sus archivos.

Estos iconos identifican tecnologías presentes en los repositorios propios o de equipos a los que pertenece el titular. No afirman dominio experto, autoría exclusiva ni trabajo actual en cada tecnología. Los tres proyectos destacados se mantienen separados de esta lista.

Los iconos de marca y su licencia se documentan en [assets/ATTRIBUTION.md](../assets/ATTRIBUTION.md).
