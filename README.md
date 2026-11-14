# Proyecto VV - Pruebas automatizadas con Selenium IDE

Materia: Validación y Verificación de Software
Sitio probado: https://www.saucedemo.com/
Herramienta: Selenium IDE (Firefox)

## Contenido
- Proyecto_VV_Grupo_8.side: proyecto exportado de Selenium IDE
- Suite_Regresion_Basica con tres casos:
  - CP01 - Login exitoso (assert)
  - CP02 - Login fallido (verify del mensaje de error)
  - CP03 - Filtro de productos y carrito (elementos dinámicos)

## Cómo ejecutarlo
1. Instalar la extensión Selenium IDE.
2. Abrir Selenium IDE y elegir "Open an existing project".
3. Seleccionar el archivo .side.
4. Ejecutar la suite Suite_Regresion_Basica.

## Nota
En Firefox 147 el comando type falla (initKeyEvent is not a function).
Se reemplazó por execute script para ingresar el usuario y la contraseña.
