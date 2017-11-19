# Contract Studio
Powered By:
[![N|Solid](https://image.ibb.co/d542tR/Home_Soft2.png)](https://www.facebook.com/CristianHome)

Sistema de creación, parametrización, seguimiento y supervisión de contratos, ajustable al manual de contratación de las entidades publicas o privadas.

  - Intuitivo y fácil de usar.
  - Interfaz adaptable para uso en cualquier dispositivo.
  - Creación y edicion de minutas de contrato directamente el en aplicativo.
  - Soporte para varios tipos de contratos.
  - Trazabilidad con historial cláusula a cláusula para modificaciones de contratos y otrosis.
  - Generador de documentos como contratos de distintos tipos (Prestación de servicios, interadministrativos, cartas de adjudicación ...etc), memorandos de supervisión, actas de inicio, informes de supervision periodicos o finales ...etc.
  - Carga de plan anual de adquisiciones con vigencias respectivas.
  - Conjunto de reglas editables por tipo de contrato o modalidad de contratación.
  - Planeación de ejecución técnica y financiera contra tiempo y contra producto.
  - Notificaciones via correo electronico.
  - Supervisión por productos vinculados a obligaciones del contrato.
  - Reportes de ejecución y proyecciones de cumplimiento.
  - Registro de avance y pagos realizados.
  - Administracion de participantes, terceros, usuarios, roles y permisos.
  - Reportes de auditoría.
  - Integración con Colombia Compra Eficiente y SECOP.
# Caracteristicas Técnicas!
  - Robusta y segura creada en PHP 7.1 bajo Laravel 5.5.
  - Aplicación Web-Based Multi Plataforma.
  - Cliente web y aplicación nativa para escritorio o móvil.
  - Api Rest con soporte para clientes no oficiales.
  - API para conexión con otros sistemas.

### Instalación

Contract Studio requiere en el servidor [PHP](http://php.net/) 7+ [Node.js](https://nodejs.org/) v4+ para correr.

Se requiere de composer para los comandos Artisan de Laravel.

Instalar todas las dependencias e iniciar el servidor.

```sh
$ cd ContractStudio
$ composer install
$ npm install -d
$ node app
```

Para entornos de producción...

```sh
$ composer install
$ npm install --production
$ NODE_ENV=production node app
```
Crear base de datos...

```sh
$ php artisan migrate
```

Software creado por Cristian David Home Acosta.
