# Sistema-Veterinaria-Django
Sistema web desarrollado en Django para la gestión integral de una clínica veterinaria.

## 🏥 Funcionalidades Implementadas

### Gestión de Personal
- **Registrar Veterinarios**: Crear nuevos veterinarios con información completa
- **Listar Veterinarios**: Ver todos los veterinarios registrados
- **Editar Veterinarios**: Modificar información de veterinarios existentes

### Gestión de Clientes
- **Registrar Propietarios**: Crear nuevos propietarios de mascotas
- **Listar Propietarios**: Ver todos los propietarios registrados
- **Editar Propietarios**: Modificar información de propietarios
- **Exportar Propietarios**: Descargar lista de propietarios en formato CSV

### Gestión de Mascotas
- **Registrar Mascotas**: Crear nuevas mascotas con información detallada
- **Listar Mascotas**: Ver todas las mascotas registradas
- **Editar Mascotas**: Modificar información de mascotas
- **Exportar Mascotas**: Descargar lista de mascotas en formato CSV

### Gestión de Medicamentos
- **Registrar Medicamentos**: Crear nuevos medicamentos veterinarios
- **Listar Medicamentos**: Ver todos los medicamentos registrados
- **Editar Medicamentos**: Modificar información de medicamentos
- **Exportar Medicamentos**: Descargar lista de medicamentos en formato CSV

### Gestión de Citas
- **Registrar Citas**: Programar citas entre veterinarios y mascotas
- **Listar Citas**: Ver todas las citas programadas
- **Editar Citas**: Modificar información de citas

### Gestión de Cirugías
- **Registrar Cirugías**: Crear nuevos registros de cirugías
- **Listar Cirugías**: Ver todas las cirugías realizadas
- **Editar Cirugías**: Modificar información de cirugías
- **Eliminar Cirugías**: Eliminar registros de cirugías

### Gestión de Bitácoras
- **Registrar Bitácoras**: Crear nuevos registros de consultas médicas
- **Listar Bitácoras**: Ver todas las bitácoras de consultas
- **Editar Bitácoras**: Modificar información de bitácoras
- **Eliminar Bitácoras**: Eliminar registros de bitácoras

### Información General
- **Página Principal**: Dashboard con información general
- **Servicios**: Información sobre servicios veterinarios

## 🚀 Instalación y Configuración

### Prerrequisitos
- Python 3.9 o superior
- pip (gestor de paquetes de Python)

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd veterinaria_web
   ```

2. **Instalar dependencias**
   ```bash
   pip install -r requirements.txt
   ```

3. **Aplicar migraciones**
   ```bash
   python manage.py migrate
   ```

4. **Crear superusuario (opcional)**
   ```bash
   python manage.py createsuperuser
   ```
   - Usuario: carlos
   - Contraseña: 000000a

5. **Ejecutar el servidor**
   ```bash
   python manage.py runserver
   ```

6. **Acceder a la aplicación**
   - URL principal: http://127.0.0.1:8000/
   - Panel de administración: http://127.0.0.1:8000/admin/

## 📋 Validación de Funcionalidades

### 1. Validar Gestión de Veterinarios
1. Ir a http://127.0.0.1:8000/registrar_veterinario/
2. Llenar formulario con datos de prueba
3. Verificar redirección a lista de veterinarios
4. Ir a http://127.0.0.1:8000/lista_veterinarios/
5. Confirmar que el veterinario aparece en la lista

### 2. Validar Gestión de Propietarios
1. Ir a http://127.0.0.1:8000/registrar_propietario/
2. Llenar formulario con datos de prueba
3. Verificar redirección a lista de propietarios
4. Ir a http://127.0.0.1:8000/lista_propietarios/
5. Confirmar que el propietario aparece en la lista
6. Probar función de exportar CSV

### 3. Validar Gestión de Mascotas
1. Ir a http://127.0.0.1:8000/registrar_mascota/
2. Llenar formulario con datos de prueba
3. Verificar redirección a lista de mascotas
4. Ir a http://127.0.0.1:8000/lista_mascotas/
5. Confirmar que la mascota aparece en la lista
6. Probar función de exportar CSV

### 4. Validar Gestión de Medicamentos
1. Ir a http://127.0.0.1:8000/registrar_medicamento/
2. Llenar formulario con datos de prueba
3. Verificar redirección a lista de medicamentos
4. Ir a http://127.0.0.1:8000/lista_medicamentos/
5. Confirmar que el medicamento aparece en la lista
6. Probar función de exportar CSV

### 5. Validar Gestión de Citas
1. Ir a http://127.0.0.1:8000/registrar_cita/
2. Llenar formulario con datos de prueba
3. Verificar redirección a lista de citas
4. Ir a http://127.0.0.1:8000/lista_citas/
5. Confirmar que la cita aparece en la lista

### 6. Validar Gestión de Cirugías
1. Ir a http://127.0.0.1:8000/registrar_cirugia/
2. Llenar formulario con datos de prueba
3. Verificar redirección a lista de cirugías
4. Ir a http://127.0.0.1:8000/lista_cirugias/
5. Confirmar que la cirugía aparece en la lista
6. Probar funciones de editar y eliminar

### 7. Validar Gestión de Bitácoras
1. Ir a http://127.0.0.1:8000/registrar_bitacora/
2. Llenar formulario con datos de prueba
3. Verificar redirección a lista de bitácoras
4. Ir a http://127.0.0.1:8000/lista_bitacoras/
5. Confirmar que la bitácora aparece en la lista
6. Probar funciones de editar y eliminar

### 8. Validar Panel de Administración
1. Ir a http://127.0.0.1:8000/admin/
2. Iniciar sesión con credenciales del superusuario
3. Verificar acceso a todos los modelos
4. Probar funciones de creación, edición y eliminación

   ## 👤 Superusuario

- **Usuario**: carlos
- **Contraseña**: 000000a
- **Acceso**: http://127.0.0.1:8000/admin/
