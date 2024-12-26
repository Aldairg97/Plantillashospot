Hacer que el inicio de sesión de miembro sea por defecto
Configuración de login.html

javascript
Copiar código
var config = {
    loginvc : "Ingresa el código de voucher y luego haz clic en login.",
    loginup : "Ingresa el nombre de usuario y la contraseña <br> luego haz clic en login.",
    voucherCode : "Código de Voucher",
    setCase : "mayúsculas", // minúsculas, mayúsculas o false
    defaultMode : "voucher", // voucher o miembro
}
Función del Escáner de Código QR
Para usar la función del Escáner de Código QR, debes agregar el siguiente script en MikroTik a través de la Terminal.

bash
Copiar código
/ip hotspot walled-garden ip

add action=accept comment="Escáner QR de Mikhmon" disabled=no dst-host=laksa19.github.io
Marca la opción HTTP PAP en el perfil del servidor hotspot.