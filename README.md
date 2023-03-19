# Django Girls tutorial complementario

Pasos complementarios que aún no se encuentran en el tutorial oficial de Django Girls.

## Subiendo tu código a GitHub

Sigue esta sección de manera normal en el tutorial oficial,
hasta antes de ejecutar el comando:

```
$ git push -u origin master
```

Antes de ejecutar este comando, hay un paso importante que debes realizar para subir tu código a GitHub.
Debemos generar un token de acceso. Este procedimiento lo debes realizar una sola vez.

Para crear el token debemos seguir los siguientes pasos:

- Ingresa a https://github.com/settings/tokens/new
- En el campo `Note` ingresa una descripción para el token, por ejemplo: `Django Girls Cuenca`.
- En el campo `Select scopes` selecciona la opción `repo`.
- Deja los demás campos como están.

![](new-token.png)

- En la parte inferior de la página da click en `Generate token`.
- Guarda el token generado en un lugar seguro, ya que no se mostrará nuevamente,
  y lo necesitarás para subir tu código a GitHub.

![](generated-token.png)

Ahora sí, cuando ejecutes el comando `git push` te pedirá el usuario y contraseña.
Ingresa tu nombre de usuario de GitHub y el token generado en el paso anterior como la contraseña.

Eso es todo, ya puedes volver al tutorial oficial 😃.
