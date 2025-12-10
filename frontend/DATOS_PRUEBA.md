# Datos de Prueba - SmartHealth

## Documentos Reales de la Base de Datos

Aquí tienes ejemplos reales de pacientes que puedes usar para probar el frontend:

### 📋 Ejemplos por Tipo de Documento

#### **CC - Cédula de Ciudadanía (Tipo 1)**
- **Documento:** `30613036`
- **Paciente:** Juliana Álvarez Rodríguez
- **Estado:** Activo ✅
- **Fecha de Nacimiento:** 1971-01-04
- **Género:** Femenino
- **Tipo de Sangre:** O+

#### **TI - Tarjeta de Identidad (Tipo 2)**
- **Documento:** `30163023`
- **Paciente:** Diego Pérez Pineda
- **Estado:** Activo ✅
- **Fecha de Nacimiento:** 1972-02-20
- **Género:** Masculino
- **Tipo de Sangre:** AB+

**Alternativa:**
- **Documento:** `30387212`
- **Paciente:** Diego Enrique Castro Díaz
- **Estado:** Activo ✅
- **Fecha de Nacimiento:** 1985-03-15

#### **CE - Cédula de Extranjería (Tipo 3)**
- **Documento:** `1461283`
- **Paciente:** Gabriela López Cifuentes
- **Estado:** Activo ✅
- **Fecha de Nacimiento:** 1964-01-07
- **Género:** Femenino
- **Tipo de Sangre:** AB+

#### **PA - Pasaporte (Tipo 4)**
- **Documento:** `1471045`
- **Paciente:** Miguel Darío Castaño Díaz
- **Estado:** Activo ✅
- **Fecha de Nacimiento:** 2005-06-26
- **Género:** Masculino
- **Tipo de Sangre:** O+

---

## 🧪 Ejemplos de Prueba Recomendados

### Prueba 1: Paciente con CC
```
Tipo de Documento: CC (1)
Número: 30613036
Pregunta: "¿Cuál es el historial médico de este paciente?"
```

### Prueba 2: Paciente con TI
```
Tipo de Documento: TI (2)
Número: 30163023
Pregunta: "¿Qué diagnósticos recientes tiene este paciente?"
```

### Prueba 3: Paciente con CE
```
Tipo de Documento: CE (3)
Número: 1461283
Pregunta: "Muéstrame las citas médicas de los últimos 6 meses"
```

### Prueba 4: Paciente con Pasaporte
```
Tipo de Documento: PA (4)
Número: 1471045
Pregunta: "¿Qué medicamentos está tomando actualmente?"
```

---

## 📝 Notas

- Todos estos pacientes están marcados como **activos** en la base de datos
- Los tipos de documento en el frontend son:
  - **1** = CC (Cédula de Ciudadanía)
  - **2** = TI (Tarjeta de Identidad)
  - **3** = CE (Cédula de Extranjería)
  - **4** = PA (Pasaporte)

- Estos datos provienen del archivo: `content/smart-health/data/sql/Bulk-Load/08-INSERT-PATIENTS.sql`

---

## 🚀 Uso Rápido

**Copia y pega en el frontend:**

1. Selecciona el tipo de documento
2. Ingresa el número de documento
3. Escribe tu pregunta
4. Envía el mensaje

**Ejemplo rápido:**
- Tipo: **CC**
- Documento: **30613036**
- Pregunta: **"¿Cuál es el historial clínico completo?"**

