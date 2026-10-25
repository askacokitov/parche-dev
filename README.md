# Parche Dev 2026

Sitio oficial del encuentro Parche Dev 2026, construido solo con HTML semántico.
Reto individual del Módulo 1 · HTML y CSS, RIWI.

Sitio publicado: https://askacokitov.github.io/parche-dev/

## Páginas

- Inicio (index.html)
- Agenda (agenda.html)
- Ponentes (ponentes.html)
- Inscripción y confirmación (inscripcion.html - gracias.html)
- Código de conducta (conducta.html)

## Cómo verlo en tu computador

1. Clona el repositorio. 
2. Ábrelo en VS Code.
3. Abre index.html con Live Preview.

## Decisiones que tomé

1. En el ticket 2 decidí usar un <ul> en la sección "Lo que vas a encontrar" (Inicio - index.html) debido a que las actividades se especifican con su orden en la agenda (Agenda - agenda.html) sin mencionar que para algunos usuarios este orden sería un poco confuso:
        1. 4 charlas en dos salas paralelas
        2. 1 taller práctico
        ...

Hacerlo como una lista con viñetas donde el orden no importa (teniendo en cuenta que este se especifíca en la programación del evento) es más práctico, fácil de entender y de alguna manera se ve mejor estéticamente.

2. En el Código de Conducta (conducta.html) decidí hacer las listas también con un <ul> debido a que no se especifíca un orden en el reglamento, a excepción de cómo reportar una situación que, aunque no es una lista de pasos, son una lista de opciones que se pueden realizar para hacer reporte.

3. En el Inicio (index.html) también decidí hacer las Secciones con listas ya que siento que se ve más organizado y estético de esa manera que un simple texto largo con varias cosas que fácilmente se pueden enlistar.

2. 
-¿Qué sale despues del "?"?
        En mi URL no sale el ? file:///c%3A/Users/Aska/OneDrive/Documentos/cocoPruebas/parche-dev/parche-dev/gracias.html
-¿Cómo se ven los espacios, las tildes y la arroba?
        Según el formato se ve como se espera: Las tildes las acepta y se ven organizadas. El arroba lo exige si no se pone y también se ve bien. Y los espacios los acepta o rechaza según lo que se necesite (documento, teléfono o correo no lo permiten).
-¿Qué pasa con los campos que no llenaste?
        Depende de cuál sea el espacio. Si son los obligatorios, el formulario no permitirá la inscripción hasta que no se llene. Si es el espacio opcional de llenado "¿Qué esperas de Parche Dev 2026?" lo deja pasar. 
¿Por qué un formulario con contraseñas nunca debería usar method="get"?
        Por privacidad y seguridad del usuario. Ya que ese método lo que hace es extraer la información y la convierte en una URL. Si tomamos los datos de un usuario y usamos el metodo method="get" esto hará que esa contraseña se vea en la URL haciendo que todo el que tenga ese link pueda acceder a la información de otros usuarios.

## Lo que aprendí

- Es mi segunda página web y aprendí a hacer tablas con el comando <table> y a hacer sus marcos con el <border="#"> lo que lo centra y organiza en una VERDADERA tabla.
- Los formularios. Esto me sorprendió un poco más porque no esperaba que fuese tan sencillo y práctico. Solo hay que saber qué poner en cada <label> para ajustarlo según nuestras necesidades. 
- Los links enlazados entre páginas. Lo admito, juraba que todo esto del HTML era más complejo debido a que solo he trabajado con Java. Pero el tema de links enlazados entre páginas es quizás la mejor idea para llevar de una página a otra sin salir de tu proyecto (a menos que sea un link de otra página externa). Solo es saber dónde está ubicado cada carpeta o archivo y usar los comandos adecuados.

## Hecho por

Laura Daniela Trujillo Martínez · [GitHub](https://github.com/askacokitov)