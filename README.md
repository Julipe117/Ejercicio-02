# Ejercicio-02
Ejercicio 02 - Formularios en HTML

      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Ejercicio 02 - Formularios en HTML</title>
      </head>
      <body>
          <form action="/" method="GET">
              <div>
                  <label for="nombre"> Nombre </label>
                  <input type="text" name="nombre" id="nombre">
              </div>
              <br>
              <div>
                  <label for="edad"> Edad <label>
                      <input type="number" name="edad" id="edad" min="0">
              </div>
              <br>
              <div>
                  <label for="fraseFavorita">Frase favorita</label>
                  <textarea name="fraseFavorita" id="fraseFavorita"></textarea>
              </div>
              <br>
              <button type="reset">Reset</button>
              <button type="submit">Enviar</button>
          </form>
      </body>
      </html>
