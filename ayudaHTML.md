## 01 - Formularios
## 02 - Tablas
### 01
```html
<!-- Como conectar un formulario -->
<form>
        <label for="nombreApellido">Nombre y apellido</label>
        <input type="text" id="nombreApellido" required>

        <br>
        <label for="mensaje">Mensaje</label>
        <textarea name="" id="mensaje" cols="70" rows="10"></textarea>
</form>

<!-- Cuestionarios de marcar casillas
 Name nos ayuda a conectar varios formularios y solamente poder elegir una opcion-->
<form>
        <label for="radio-email">Email</label>
        <input type="radio" name="contacto" value="email" id="radio-email">

        <label for="radio-telefono">Telefono</label>
        <input type="radio" name="contacto" value="telefono" id="radio-telefono">

        <label for="radio-whatsapp">Whatsapp</label>
        <input type="radio" name="contacto" value="whatsapp" id="radio-whatsapp">

        <input type="submit" value="Enviar Formulario">
</form>

<!-- Legend: Nos ayuda a guardar todas nuestras preguntas en un solo grupo de inputs 
Legend - Es como un agrupador de tipos de cuestioanrios-->
<form>
        <fieldset>
            <legend>Información personal</legend><br>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre"><br><br>
            <label for="apellido">Apellido:</label>
            <input type="text" id="apellido" name="apellido"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
        </fieldset>
    </form>

```
### 02 - Tablas
```html
<table>
    <thead>
      <tr>
        <th>Nombre</th>
        <th>Apellido</th>
        <th>Edad</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>John</td>
        <td>Doe</td>
        <td>30</td>
      </tr>
      <tr>
        <td>Jane</td>
        <td>Doe</td>
        <td>25</td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <td colspan="2">Total</td>
        <td>55</td>
      </tr>
    </tfoot>
</table>
```
