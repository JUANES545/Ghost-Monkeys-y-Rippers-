# Ghost [Monkeys & Rippers]


Este repositorio contiene las pruebas realizadas utilizando monkey testing con Cypress y rippers con RIPuppet en la aplicación GHOST, de acuerdo al material del curso. Aquí se detallan las herramientas utilizadas, los procedimientos para ejecutar las pruebas y los incidentes reportados.

## Herramientas Utilizadas

- **Cypress Monkey**: Herramienta para realizar pruebas a través de clics y entradas aleatorias en la aplicación.
- **RIPuppet**: Biblioteca de Node.js para realizar scraping de la interfaz gráfica de aplicaciones web.

## Instalación

Para utilizar las herramientas de este proyecto, asegúrate de tener instaladas las siguientes dependencias:

1. **Node.js**: Se recomienda usar la versión v12.22.12. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).
  
2. **Cypress**: Asegúrate de que Cypress esté instalado en tu entorno de desarrollo. Puedes instalarlo mediante npm:

   ```bash
   npm install cypress --save-dev
   ```

3. **RIPuppet**: Si no lo tienes, puedes instalarlo mediante npm:

   ```bash
   npm install ripuppet
   ```

## Configuración

### RIPuppet

Asegúrate de que el archivo `config.json` contenga los parámetros necesarios para la ejecución. Modifica los parámetros requeridos según tus necesidades antes de ejecutar la herramienta.

## Ejecución de Pruebas

Para ejecutar las pruebas, puedes usar los siguientes comandos:

### Cypress Monkey

Para realizar pruebas de monkey con Cypress, asegúrate de que tu entorno de pruebas esté correctamente configurado, y luego ejecuta:

```bash
npx cypress open
```

Sigue las instrucciones en el entorno de Cypress para configurar y ejecutar las pruebas.

### RIPuppet

Para ejecutar RIPuppet, usa el siguiente comando:

```bash
node index.js
```

Por ejemplo:

```bash
node index.js
```

## Reportes de Incidentes

En el apartado de **Issues** de este repositorio, se han documentado los incidentes encontrados durante las pruebas con RIPuppet. Cada reporte incluye información sobre los problemas identificados y las acciones tomadas en respuesta a ellos.

## Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de hacer un fork y enviar tus pull requests. También puedes reportar problemas y sugerencias a través de la sección de **Issues**.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

---

¡Gracias por tu interés en nuestro proyecto de pruebas en Ghost!
```

Este archivo `README.md` proporciona información clara y estructurada sobre el proyecto, incluyendo las herramientas utilizadas, instrucciones de instalación y ejecución, así como detalles sobre los reportes de incidentes. Puedes personalizarlo aún más si es necesario.
