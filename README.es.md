<p align="center">
  <img src="logo.png" alt="Phoenix Studio" width="160">
</p>

<h1 align="center">Phoenix Studio</h1>

<p align="center"><b>Diseñador visual y editor de código para AutoIt.</b><br>
Dibuja tus ventanas, escribe solo la lógica y obtén un <code>.au3</code> limpio.</p>

<p align="center"><a href="README.md">Read in English</a></p>

---

![Ventana principal de Phoenix Studio](capturas/ventana-principal.png)

## Qué es

Phoenix Studio es una aplicación nativa de Windows (sin .NET ni nada que instalar) donde **diseñas las ventanas de un programa de AutoIt arrastrando controles**, y genera el código AutoIt por ti. El código generado es AutoIt normal y legible: puedes seguir editándolo a mano, y el diseñador respeta tus funciones de eventos.

## Lo que ofrece

- **Diseñador visual de formularios.** Arrastrar, redimensionar, alinear, ajustar a la cuadrícula y a las guías, definir el orden de Tab con clics, copiar formato, deshacer y rehacer, zoom.
- **Paleta de controles completa.** Etiquetas, cajas de texto, botones, casillas, radios, listas, combos, grupos, pestañas, ListView y TreeView (con grupos, filas alternadas y orden numérico y por fecha), menús y menús emergentes, barras de herramientas y de estado, RichEdit, fechas, deslizadores, IP, controles de datos y más.
- **Inspector de propiedades** con editores listos para listas, columnas, menús, imágenes, nodos de árbol, SQL y claves INI.
- **Eventos.** Eliges un evento y se agrega al código una función con el nombre correcto. El IDE solo agrega funciones, nunca borra las tuyas.
- **Editor de código.** Resaltado de sintaxis, autocompletado, biblioteca de código, buscar, reemplazar y buscar en archivos, renombrar en el código, comentar y descomentar, panel de variables y revisión de errores en vivo con **Au3Check**.
- **Ejecutar y compilar.** Ejecutar con una tecla, detener, revisar y compilar a `.exe` (32 o 64 bits), con opciones de proyecto como icono, versión y carpeta de salida.
- **Proyectos de varias ventanas** (`.afp`) con programa principal, y plantillas de ventanas listas para usar.
- **Importa scripts de AutoIt existentes** y sigue trabajando en ellos de forma visual.
- **Datos.** Controles con SQLite y una rejilla que muestra registros reales al diseñar, con soporte de reportes.
- **Asistente de IA integrado** (con tu propio proveedor y tu clave).
- **Interfaz en 9 idiomas:** español, inglés, alemán, francés, italiano, polaco, portugués, ruso y chino.

## Capturas

### Diseño

![Pantalla de inicio: proyectos y ventanas recientes en tarjetas con vista previa, los fijados arriba, las cuatro formas de empezar y las herramientas de AutoIt encontradas](capturas/pantalla-de-inicio.png)
*Pantalla de inicio: proyectos y ventanas recientes en tarjetas con vista previa, los fijados arriba, las cuatro formas de empezar y las herramientas de AutoIt encontradas*

![Ventana principal: vista de diseño con un control elegido y el inspector de propiedades lleno](capturas/ventana-principal.png)
*Ventana principal: vista de diseño con un control elegido y el inspector de propiedades lleno*

![Caja de herramientas con categorías plegables y el árbol de estructura que sigue la selección](capturas/caja-de-herramientas.png)
*Caja de herramientas con categorías plegables y el árbol de estructura que sigue la selección*

![Panel de propiedades: la pestaña de eventos](capturas/propiedades-eventos.png)
*Panel de propiedades: la pestaña de eventos*

![ListView con grupos en el diseñador (Groups, GroupView y AlternateRows en el inspector)](capturas/listview-grupos.png)
*ListView con grupos en el diseñador (Groups, GroupView y AlternateRows en el inspector)*

![Controles de datos: DBGrid, DBEdit y DBNavigator con registros reales de SQLite al diseñar](capturas/controles-de-datos.png)
*Controles de datos: DBGrid, DBEdit y DBNavigator con registros reales de SQLite al diseñar*

![Proyecto de varias ventanas (.afp) y panel del proyecto](capturas/proyecto-varias-ventanas.png)
*Proyecto de varias ventanas (.afp) y panel del proyecto*


### Código, ejecución e IA

![Pestaña Código: .au3 con colores y la lista de autocompletar abierta](capturas/codigo-autocompletado.png)
*Pestaña Código: .au3 con colores y la lista de autocompletar abierta*

![Biblioteca de código (Ctrl+J): búsqueda, ejemplos y vista previa](capturas/biblioteca-de-codigo.png)
*Biblioteca de código (Ctrl+J): búsqueda, ejemplos y vista previa*

![Salida de Au3Check con la línea del error marcada](capturas/au3check-salida.png)
*Salida de Au3Check con la línea del error marcada*

![El programa generado corriendo (ventana de AutoIt)](capturas/programa-corriendo.png)
*El programa generado corriendo (ventana de AutoIt)*

![Panel del asistente de IA (con tu propio proveedor y clave)](capturas/asistente-ia.png)
*Panel del asistente de IA (con tu propio proveedor y clave)*


### Editores, plantillas e interfaz

![Editor de grupos con vista previa](capturas/editor-grupos.png)
*Editor de grupos con vista previa*

![Editor de columnas (ListView)](capturas/editor-columnas.png)
*Editor de columnas (ListView)*

![Diseñador de menús](capturas/editor-de-menus.png)
*Diseñador de menús*

![Nuevo desde plantilla, con vista previa de la ventana](capturas/nuevo-desde-plantilla.png)
*Nuevo desde plantilla, con vista previa de la ventana*

![Menú Editar](capturas/menu-editar.png)
*Menú Editar*

![Acerca de: logo, versión y botón de donar](capturas/acerca-de.png)
*Acerca de: logo, versión y botón de donar*

![Ver > Idioma: los nueve idiomas de la interfaz](capturas/menu-idioma.png)
*Ver > Idioma: los nueve idiomas de la interfaz*

![Ventana principal en español](capturas/ventana-principal-es.png)
*Ventana principal en español*

## Requisitos

- Windows 10 u 11, de 64 bits.
- [AutoIt v3](https://www.autoitscript.com/site/autoit/downloads/) instalado, para ejecutar, revisar y compilar los programas que crees. Phoenix Studio no incluye AutoIt.

## Instalación

1. Descarga el último `.zip` desde la página de **Releases**.
2. Comprueba el SHA-256 que aparece en las notas de la versión (abajo).
3. Descomprímelo donde quieras y ejecuta `ps.exe`. No hay instalador y no escribe nada fuera de su carpeta y de tu perfil de usuario.

Para comprobar la descarga:

```powershell
Get-FileHash .\PhoenixStudio-vX.Y.zip -Algorithm SHA256
```

El valor debe coincidir con el de las notas de la versión.

> Windows SmartScreen o tu antivirus pueden advertir de un programa sin firma digital. Si lo bajaste de esta página y el hash coincide, puedes elegir *Más información > Ejecutar de todas formas*.

## Apoya el proyecto

Phoenix Studio es gratuito. Si te ahorra tiempo y quieres ayudar a que siga creciendo, puedes donar aquí (es opcional y el programa solo lo muestra si abres *Ayuda > Donar*):

**https://paypal.me/laudrupmx**

## Licencia y uso responsable

Phoenix Studio se distribuye **sin costo y sin garantía ni responsabilidad alguna**: el autor no responde por lo que cualquier persona haga o pueda hacer con el programa. Es una herramienta para hacer programas de scripting para Windows de forma correcta, ética y de buena fe. No debe usarse para crear o difundir virus, malware, ransomware, gusanos ni herramientas o ataques de hacking de ningún tipo, y el autor no lo apoya de ninguna forma. Cualquiera puede redistribuir Phoenix Studio siempre que sea **sin modificar** (sin ingeniería inversa ni modificación de ningún tipo). **Los programas que crees con él son tuyos**: puedes distribuirlos libremente, sin dar crédito a Phoenix Studio y sin pagarle nada, aunque las vendas. Los términos completos están en [LICENSE.txt](LICENSE.txt).

## Notas

- El código fuente no se publica.
- **AutoIt es el creador del lenguaje y de todo lo que hace funcionar los programas.** Phoenix Studio es solo una interfaz que facilita la creación de scripts de AutoIt. AutoIt tiene sus propias reglas y licencias, y deben respetarse al usar Phoenix Studio; Phoenix Studio cumple con ellas.
- «AutoIt» es marca de sus propietarios. Phoenix Studio es una herramienta independiente, sin relación con el proyecto AutoIt ni respaldada por él.
