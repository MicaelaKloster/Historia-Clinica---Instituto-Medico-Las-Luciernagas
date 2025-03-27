# 🧑🏻‍⚕️ Historia Clínica - Instituto Médico Las Luciérnagas

## Descripción del Proyecto

Este proyecto es una solución de software para la gestión de historias clínicas en el "Instituto Médico Las Luciérnagas". Permite registrar, editar y consultar la información de pacientes, médicos y sus historias clínicas, asegurando una organización eficiente y accesible de los datos.

## Tecnologías Utilizadas

- **Lenguaje**: Python
- **Formato de almacenamiento**: JSON
- **Interfaz de usuario**: Consola interactiva

## Características Principales

### Gestión de Pacientes

- Registrar un nuevo paciente.

- Editar los datos de un paciente existente.

- Eliminar un paciente.

- Búsqueda de pacientes por:

  - Nombre y/o Apellido.

  - Rango de fechas en las que fueron atendidos.

  - Enfermedad/Afección.

  - Médico que los atendió.

  - Nacionalidad.

- Cálculo de la edad del paciente a partir de su fecha de nacimiento y la fecha actual del sistema.

### Gestión de Historias Clínicas

- Cada paciente tiene asignado un número de historia clínica único e incremental.

- Agregar una historia clínica a un paciente con los siguientes datos:

  - Fecha.

  - Enfermedad o afección.

  - Médico tratante.

  - Observaciones.

### Gestión de Profesionales de la Salud

- Registrar nuevos médicos con:

  - Nombre.

  - Apellido.

  - Especialidad.

- Listar los médicos existentes.

## Instalación y Ejecución

1. Clonar el repositorio:

   ```bash

   git clone https://github.com/tu-usuario/tu-repositorio.git

   ```

2. Navegar al directorio del proyecto:

   ```bash

   cd tu-repositorio

   ```

3. Instalar dependencias (si aplica):

   ```bash

   pip install -r requirements.txt

   ```

4. Ejecutar la aplicación:

   ```bash

   python main.py

   ```

## Estructura del Proyecto

```
📂 historia_clinica
│── 📂 data                 # Archivos JSON de almacenamiento
│── 📂 src                  # Código fuente del proyecto
│── ├── main.py             # Archivo principal de ejecución
│── ├── pacientes.py        # Gestión de pacientes
│── ├── historias.py        # Gestión de historias clínicas
│── ├── medicos.py          # Gestión de médicos
│── ├── utils.py            # Funciones auxiliares
│── 📂 tests                # Pruebas unitarias
│── README.md               # Documentación del proyecto
│── requirements.txt        # Dependencias del proyecto
```

## Contribuciones

Las contribuciones son bienvenidas. Para colaborar:

1. Realizar un fork del repositorio.

2. Crear una nueva rama (`feature-nombre`).

3. Hacer un commit con los cambios.

4. Enviar un pull request.

## Licencia

Este proyecto está bajo la licencia MIT.

---
📌 *Desarrollado por Micaela Kloster*
