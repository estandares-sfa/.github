# Directrices de Contribución

Se agradece su interés en contribuir a los repositorios de **Estándares-SFA**. Estas directrices están diseñadas para proporcionar claridad sobre cómo colaborar de manera eficiente y uniforme.

## Lineamientos para Diagramas
Todos los diagramas deben cumplir con los siguientes requisitos:

1. **Plataformas Admitidas**:
   - Los diagramas deben estar disponibles en **PlantUML** y **Mermaid**.

2. **Estructura del Repositorio**:
   - Cada diagrama deberá contar con su propio repositorio.
   - Estructura del nombre del repositorio:
      - `diagrama-{nombre-flujo}`
   - Debe incluir:
     - Un archivo `.puml` o `.iuml` (PlantUML).
     - Un archivo `.md` que contenga el código equivalente en Mermaid.

3. **Reglas de Creación**:
   - Los diagramas deben ser idénticos en ambas plataformas.
   - Se recomienda utilizar **Mermaid** para facilitar la visualización en GitHub.

4. **Formato de Archivos**:
   - **PlantUML**: Los diagramas deben ser guardados en archivos con extensión `.puml`.
   - **Mermaid**: El código correspondiente debe incluirse en un archivo `.md` utilizando un bloque de código ```mermaid.

6. **Nombres de Archivos**:
   - Es necesario utilizar nombres descriptivos y consistentes para los archivos.
     - Ejemplo: `diagrama-{nombre-flujo}.puml` y `README.md`.

7. **Ejemplo**:
   - Puede consultar un ejemplo en el siguiente enlace: ["Diagrama Secuencia OAuth 2.0 - Authorization Code Grant"](https://github.com/estandares-sfa/diagrama-auth-code-grant).
