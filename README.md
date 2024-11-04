# Ghost [Monkeys & Rippers]



Este repositorio contiene las pruebas realizadas utilizando monkey testing con Cypress y rippers con RIPuppet en la aplicación GHOST, de acuerdo al material del curso. Aquí se detallan las herramientas utilizadas, los procedimientos para ejecutar las pruebas y los incidentes reportados.

## Herramientas Utilizadas

- **Cypress Monkey**: Herramienta para realizar pruebas a través de clics y entradas aleatorias en la aplicación.
- **[RIPuppet](https://github.com/TheSoftwareDesignLab/RIPuppetCoursera)**: Biblioteca de Node.js para realizar scraping de la interfaz gráfica de aplicaciones web.

## Instalación

Para utilizar las herramientas de este proyecto, asegúrate de tener instaladas las siguientes dependencias:

1. **Node.js**: Se recomienda usar la versión v12.22.12. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).
  
2. **Cypress**: Asegúrate de que Cypress esté instalado en tu entorno de desarrollo. Puedes instalarlo mediante npm:

   ```bash
   npm install cypress --save-dev
   ```


## Configuración

### RIPuppet

Sigue las istrucciónes del siguiente [repositorio](https://github.com/TheSoftwareDesignLab/RIPuppetCoursera)

## Ejecución de Pruebas

Para ejecutar las pruebas, puedes usar los siguientes comandos:

### Cypress Monkey

Para realizar pruebas de monkey con Cypress, asegúrate de que tu entorno de pruebas esté correctamente configurado, y luego ejecuta:

```bash
npx cypress open
```

Sigue las instrucciones en el entorno de Cypress para configurar y ejecutar las pruebas y ejecuta el script **monkey_testing.js**


## Reportes de Incidentes

https://github.com/user-attachments/assets/641bd9c3-810a-4091-a55d-3b145715b378

En el apartado de **Issues** de este repositorio, se han documentado los incidentes encontrados durante las pruebas con RIPuppet. Cada reporte incluye información sobre los problemas identificados y las acciones tomadas en respuesta a ellos.

