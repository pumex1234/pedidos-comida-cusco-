# Laboratorio 1: Introducción al entorno de desarrollo y Git

**Estudiante:** Jose Puma  
**Correo:** josefranciscopuma20@gmail.com  
**Caso Práctico:** Sistema Web de Gestión de Pedidos de Comida Local - Cusco  

---

## 1. Descripción del Proyecto

Este repositorio contiene la estructura inicial del sistema web para la gestión de pedidos de comida tradicional en la ciudad imperial del Cusco. El proyecto busca interconectar a los restaurantes locales de comida típica cusqueña (como chicharronerías, picanterías y quintas) con clientes locales y turistas.

---

## 2. Configuración e Historial de Comandos

En cumplimiento con la guía del laboratorio, se ejecutaron las siguientes actividades de configuración y control de versiones:

### Parte 1: Configuración Global de Git
```bash
git config --global user.name "Jose Puma"
git config --global user.email "josefranciscopuma20@gmail.com"
```

### Parte 2: Inicialización del Repositorio Local
```bash
git init
git branch -M main
```

### Parte 3: Versionamiento
```bash
git add .
git commit -m "Primer commit"
```

### Parte 4: Vinculación con Repositorio Remoto en GitHub
```bash
git remote add origin https://github.com/pumex1234/pedidos-comida-cusco-.git
git push -u origin main
```

---

## 3. Reflexión

### ¿Por qué Git es crítico en proyectos colaborativos?
Git es fundamental en proyectos colaborativos por las siguientes razones:
1. **Historial Trazable:** Permite conocer con precisión quién realizó cada cambio, qué líneas de código se modificaron y la razón de cada actualización a través de los mensajes de *commit*.
2. **Trabajo en Paralelo (Ramificación/Branching):** Permite que múltiples desarrolladores trabajen en distintas funcionalidades (*features*) simultáneamente sin interferir con el código principal o en producción.
3. **Respaldo e Integración Continua:** Facilita la sincronización del código local con plataformas remotas como GitHub, garantizando un punto centralizado y actualizado para todo el equipo.

### ¿Qué problemas evita?
El uso de Git previene problemas críticos en el desarrollo de software, tales como:
- **Pérdida de Código:** Evita el riesgo de sobreescribir el trabajo de un compañero de equipo al guardar cambios.
- **Caos de Versiones Manuales:** Elimina prácticas obsoletas e inseguras como crear carpetas duplicadas tipo `proyecto_v1`, `proyecto_final_v2`, `proyecto_definitivo`.
- **Dificultad en la Recuperación de Errores:** En caso de que un cambio rompa la aplicación, Git permite volver (*rollback*) a una versión anterior funcional en segundos.
- **Falta de Claridad en Conflictos:** Git detecta automáticamente disputas de código y ofrece mecanismos estructurados para resolverlos antes de integrar los cambios.
