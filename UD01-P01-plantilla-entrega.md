# Entrega Práctica UD01 · Auditoría y fortificación Clínica Dental Sonrisas

- **Nombre y apellidos del alumno/a:**Samuel Cote Prieto**
- **Grupo:** 2º SMR
- **Fecha de realización:** 24/11/2026**

---

### Actividad 1 · Mecanismos y objetivos de la seguridad informática

| ID | Mecanismo | Objetivo principal (C, I, D, NR) | Física / Lógica | Activa / Pasiva | Justificación |
|:---|:---|:---:|:---:|:---:|:---|
| 1.1 | SAI servidor | Disponibilidad | Fisica | Pasiva |  **Fisica por que previene que el hardawre se dañe por un apagon repentino o por un corto,pasiva por que se activa cuando hay un corte de electricidad y disponibilidad por que es accesible** 
| 1.2 | Cifrado BitLocker |No repudio |Logica|Activa | **Logica por que cifre contenido que esta en e software, activa por que previene y no repudio por que si esta cifrado tu tendras la llave para descrifrarlo**
| 1.3 | Cortafuegos perimetral |Disponibilidad |Logica | Activa| **Logica y activa por que previene que entre algun malware y disponibilidad por que lo tienes activo y disponible**
| 1.4 | Copias de seguridad NAS |Integridad | Logica| Pasiva| **Logica por que copia todo los archivos que hay en tu ordenador en ese momento y pasiva por que minimiza el daño dado que si se pierden los datos tienes tu copia y puedes volver a hacer funcionar tus archivos e integridad por que son tus archivos y no estan modificados por nadie**
| 1.5 | Antivirus corporativo |Disponibilidad|Logica |Activa | **Logica y activa por que previene que en tu equipo entre cualquier virus u otros tipos de malware y disponibilidad por que esta hay para que accedas a el simepre que lo necesites**

---

### Actividad 2 · Cadena del incidente de seguridad

1. **Activos afectados:**
   - Activo 1: Copia de la base de datos con datos de los clientes
   - Activo 2: Registro de citas
2. **Amenaza:** Atacante remoto
3. **Vulnerabilidad y clasificación:** Es una vulnerabilidad sobre software instalado y era un servicio de accesp remoto que no se actualizaba desde hace un año y tenia un parche que no se instalo.
4. **Riesgo previo:** El riesgo es que al no tenerlo actualizado cualquiera que viera que no estaba actualizado podria meterse de forma remota.
5. **Ataque:** El atacante ejecuto un script publico(exploit) 
6. **Impacto:**
   - Impacto cuantitativo: Perdida de 3200 en tratamientos cancelados
   - Impacto cualitativo: Quejas de pacientes
---

### Actividad 3 · Plan de contingencia

1. **Clasificación de medidas:**
   - Medida A: **Emergencia**
   - Medida B: **Respaldo**
   - Medida C: **Recuperacion**
   - Medida D: **Emergencia**
   - Medida E: **Recuperacion**
   - Medida F: **Respaldo**
2. **Diferencia entre plan de respaldo y plan de recuperación:**
El plan de respaldo son cosas que se hacen antes de que ocurra todo y se hace para prevenir que ocurra y el plan de recuperacion se hace despues de que ocurra algo y como su propio nombre indica sirve para recuperarte de cualquier incidente.
---

### Actividad 4 · Software malicioso y test de intrusión

#### 4.1. Diagnóstico de malware
- **Caso 1:**
  - Tipo de malware: Troyano
  - Justificación (archivo anfitrión e intervención usuario): Requiere de la intervencion del usuario para propagarse, por que le hicieron creer que era un archivo normal y al descargarselo y ejecutarlo era un archivo malicioso
- **Caso 2:**
  - Tipo de malware: Gusano
  - Justificación (archivo anfitrión e intervención usuario): No requiere un archivo anfitrion ni intervencion del usuario, aprovecho un fallo no parcheado y se metio en los ordenadores a traves de la red.
- **Medida preventiva para Caso 2:**

#### 4.2. Secuenciación de test de intrusión
- Secuencia ordenada cronológicamente (letras):
- Fases correspondientes:
  - Acción **Z** : Fase **Footprinting**
  - Acción **X** : Fase **Fingerprinting**
  - Acción **W** : Fase **Vulnerabilidades**
  - Acción **Y** : Fase **Correcion**

---

### Actividad 5 · Contraseñas e identificación digital

#### 5.1. Contraseñas
1. **Comparativa de seguridad frente a fuerza bruta:** La contraseña del Empleado 2 es mas segura por que convina letras, numeros y simbolos especiales y aunque tenga menos caracteres que la del Empleado 1 la de este solo usa minisculas y numeros y por eso es menos segura.
2. **Política de contraseñas (3 reglas):**
   - Regla 1: **Que tenga una longitud minima de 8 caracteres.
   - Regla 2: Combinar mayusculas, minusculas, numeros y simbolos
   - Regla 3: Cambiar las contraseñas periodicamente por ejemplo cada 2 semanas.

#### 5.2. Identificación digital
3. **Mecanismos aplicados:**
   - Trámite A: **No repudio**
   - Trámite B: **Integridad**
4. **Objetivo de seguridad garantizado y diferencia con usuario/contraseña:** Estos mecanismos acreditan que eres tu mediante firmas y certificados legales mientras que las contraseñas y los usuarios los compartes con la empresa que se lo has dicho y en cualquier momento pueden tener algun tipo de flitracion y los atacantes se harian pasar por ti facilmente.