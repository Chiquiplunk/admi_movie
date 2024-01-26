[x] 1) Al registrar películas con el campo "release date" ingresando un dato vacío se tiene:

Exception in thread "main" java.time.format.DateTimeParseException: Text '' could not be parsed at index 0
at java.base/java.time.format.DateTimeFormatter.parseResolved0(DateTimeFormatter.java:2052)
at java.base/java.time.format.DateTimeFormatter.parse(DateTimeFormatter.java:1954)
at java.base/java.time.LocalDate.parse(LocalDate.java:430)
at java.base/java.time.LocalDate.parse(LocalDate.java:415)
at Main.addMovie(Main.java:365)
at Main.showAdminMenu(Main.java:174)
at Main.main(Main.java:33)
Terminando inmediatamente con la aplicación.

[x] 2) Los usuarios pueden registrarse con el mismo nombre varias veces si son diferentes letras mayúsculas o minúsculas.
[ ] 3) Se pueden registrar los usuarios con campos vacíos para username y password.   
[ ] 4) Agregar películas con los campos vacíos no debe ser permitido.
[ ] 5) Se puede agregar películas con la misma información, duplicados.
[ ] 6) Registrar películas con mucha información o campos muy largos puede deformar la aplicación al momento de mostrarlos.
[ ] 7) Un usuario puede votar (Rating) varias veces por la misma película.
[ ] 8) La búsqueda de películas no parece estar completa, solo lista las películas de las que se puedan seleccionar alguna para verla.