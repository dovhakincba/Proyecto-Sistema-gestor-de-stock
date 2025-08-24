Sistema de Gestión de Stock - StokPoint®

Descripción
El Sistema de Gestión de Stock (StokPoint®) es una aplicación orientada a pequeños negocios,
depósitos, talleres y PYMES. Permite registrar productos, controlar inventario en tiempo real y
gestionar movimientos de entrada y salida, asegurando un seguimiento eficiente de los recursos.

Objetivos
- Mantener actualizado el stock automáticamente.
- Permitir diferentes roles de usuario con permisos específicos.
- Facilitar la toma de decisiones con informes claros.
- Brindar una herramienta digital adaptable a distintos tipos de negocio.

Funcionalidades principales
Productos: Registro, modificación, consulta de stock.
Movimientos: Registro de entradas y salidas, validación y actualización automática.
Usuarios y Roles: Administración de usuarios, asignación de roles y permisos.
Reportes: Consulta de inventario en tiempo real, exportación digital.

Modelo de datos
El sistema se basa en una base de datos relacional con entidades: Producto, Movimiento, Usuario,
Rol, Permiso y Rol_Permiso.

Clases principales
- Producto: updateInfoProducto, cambiarPrecio, obtenerStock.
- Movimiento: afectarStock, validarMovimiento, registrarMovimiento, mostrarMovimiento.
- Usuario: verificar_permiso.
- Rol: tiene_permiso, agregar_permiso, remover_permiso.

Requerimientos
- Python 3.10+
- Librerías: sqlite3, tabulate

Instalación y uso
1. Clonar el repositorio:
git clone https://github.com/usuario/gestion-stock.git
2. Instalar dependencias:
pip install -r requirements.txt
3. Ejecutar el sistema:
python main.py
4. Iniciar sesión con un usuario válido.

Autores
Juan Daniel Opazo
Alexis Gabriel Baracat Peralta
Natalia Martorina
Pilar Janet Molina

Licencia
Proyecto académico – Instituto Politécnico de Córdoba. Uso educativo.
