# Evento de Junio

## Creando librerias: Las buenas partes

Speaker: [Cristhian Duran](https://twitter.com/DuranCristhian)

Resumen: *Experiencias y aprendizajes adquiridos creando una libreria OpenSource con JavaScript*.

Slides: http://bit.ly/banode-libraries

Fuentes y recursos:

* [meetup-randomizer](https://github.com/durancristhian/meetup-randomizer): libreria sobre la cual estuvimos hablando.
* [package.json bin](https://docs.npmjs.com/files/package.json#bin): propiedad que nos permite especificar un nombre de comando para un script de nuestro paquete, útil para crear una CLI.
* [npm link](https://docs.npmjs.com/cli/link): disponibiliza en el SO un paquete, muy útil para desarollar.
* [commitizen](https://github.com/commitizen/cz-cli): Interfaz de línea de comando que reemplaza a `git commit -m "my awesome new feature"`.
* [cz-conventional-changelog](https://github.com/commitizen/cz-conventional-changelog): Convención proveniente de Angular.js para escribir mensajes de commit que nos ayudan a autogenerar el changelog en el proceso de Integración contínua.
* [semantic-release](https://github.com/semantic-release/semantic-release): Libreria que nos ayuda a automatizar el proceso de publicación, haciendose responsable de la generación del próximo número de versión (*semver*) conforme al historial de git (*Gracias commitizen*), publicando a npm, generando el tag de la versión, pusheando a Github y haciendo el release con el changelog autogenerado (*Gracias commitizen* :+1:).
