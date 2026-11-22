# Sistema Integral de Gestión de Clientes, Servicios y Reservas

## Descripción

Este proyecto fue desarrollado para la Fase 4 del curso Programación de la Universidad Nacional Abierta y a Distancia (UNAD).

El sistema permite gestionar clientes, servicios y reservas para la empresa Software FJ, aplicando los principios de Programación Orientada a Objetos y el manejo avanzado de excepciones exigidos en la actividad.

La aplicación funciona sin bases de datos, utilizando objetos, listas y archivos de registro para almacenar y gestionar la información durante la ejecución.

---

## Objetivo

Desarrollar una solución orientada a objetos capaz de administrar clientes, servicios y reservas, garantizando la estabilidad del sistema mediante validaciones, manejo de excepciones y registro de eventos.

---

## Principios de Programación Orientada a Objetos Aplicados

### Abstracción

- Clase abstracta `Entidad`.
- Clase abstracta `Servicio`.

### Encapsulación

- Protección de atributos mediante acceso controlado.
- Validación de datos de entrada para mantener la integridad del sistema.

### Herencia

- La clase `Cliente` hereda de `Entidad`.
- Los servicios especializados heredan de la clase abstracta `Servicio`.

### Polimorfismo

- Implementación de métodos sobrescritos para describir servicios.
- Implementación de métodos especializados para cálculo de costos.
- Comportamiento específico según el tipo de servicio solicitado.

---

## Servicios Implementados

### Reserva de Sala

Permite gestionar la reserva de espacios físicos para reuniones y actividades corporativas.

Funciones:

- Validación de disponibilidad.
- Cálculo de costos.
- Confirmación y cancelación de reservas.

### Alquiler de Equipos

Permite gestionar el préstamo o alquiler de equipos tecnológicos.

Funciones:

- Control de disponibilidad.
- Cálculo automático de costos.
- Gestión de reservas asociadas.

### Asesoría Especializada

Permite solicitar servicios de consultoría profesional.

Funciones:

- Registro de asesorías.
- Cálculo de costos.
- Gestión de disponibilidad.

---

## Gestión de Clientes

El sistema permite:

- Registrar clientes.
- Validar información personal.
- Consultar datos registrados.
- Gestionar clientes asociados a las reservas.

---

## Gestión de Reservas

La clase `Reserva` permite:

- Crear reservas.
- Confirmar reservas.
- Cancelar reservas.
- Gestionar estados de reserva.

Estados disponibles:

- Pendiente
- Confirmada
- Cancelada

---

## Manejo de Excepciones

El proyecto implementa:

- Excepciones personalizadas.
- Bloques `try - except`.
- Bloques `try - except - else`.
- Bloques `try - finally`.
- Encadenamiento de excepciones.

Esto permite controlar errores sin detener la ejecución completa del sistema.

---

## Registro de Eventos

Se utiliza el módulo `logging` para registrar:

- Operaciones exitosas.
- Errores de validación.
- Reservas creadas.
- Reservas canceladas.
- Eventos importantes del sistema.

Los registros quedan almacenados en un archivo de log para facilitar el seguimiento de la aplicación.

---

## Simulación de Operaciones

El sistema ejecuta una simulación de más de diez operaciones diferentes que incluyen:

- Registros válidos de clientes.
- Registros inválidos.
- Creación correcta de servicios.
- Creación incorrecta de servicios.
- Reservas exitosas.
- Reservas fallidas.
- Cancelaciones de reservas.
- Manejo de errores controlados.

---

## Tecnologías Utilizadas

- Python 3
- Programación Orientada a Objetos
- Git
- GitHub
- Logging

---

## Estructura General del Proyecto

```text
proyecto/

├── entidad.py
├── cliente.py
├── servicio.py
├── reserva_sala.py
├── alquiler_equipo.py
├── asesoria_especializada.py
├── reserva.py
├── excepciones.py
├── main.py
├── logs/
└── README.md
```

---

## Ejecución del Proyecto

Desde la carpeta principal ejecutar:

```bash
python main.py
```

---

## Resultados Alcanzados

El proyecto cumple con los requisitos establecidos para la actividad:

✅ Clase abstracta Entidad.

✅ Clase Cliente.

✅ Clase abstracta Servicio.

✅ Reserva de Sala.

✅ Alquiler de Equipos.

✅ Asesoría Especializada.

✅ Clase Reserva.

✅ Encapsulación.

✅ Herencia.

✅ Polimorfismo.

✅ Excepciones personalizadas.

✅ try/except.

✅ try/except/else.

✅ try/finally.

✅ Encadenamiento de excepciones.

✅ Parámetros opcionales para cálculo de costos.

✅ Registro de logs.

✅ Operaciones válidas e inválidas.

✅ Reservas exitosas.

✅ Reservas fallidas.

✅ Cancelación de reservas.

✅ Simulación de más de diez operaciones.

---

## Autora

**Yehinny González**

Estudiante de Ingeniería de Sistemas

Universidad Nacional Abierta y a Distancia (UNAD)

Fase 4 - Programación
