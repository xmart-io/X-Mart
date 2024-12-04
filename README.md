# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`


#### Sincronizar repositorio con Mintlify 

Una vez creada la cuenta en Mintlify, es necesario descargar el repositorio de Mintlify a nuestro entorno local y subirlo a GitHub. Tras subirlo a GitHub, sincronizaremos la organización y el repositorio en el panel de control de Mintlify.

### Subir cambios a localhost

Para implementar los cambios en Localhost, debemos ubicarnos en el directorio principal del proyecto y ejecutar el comando `mintlify dev`. Cada vez que guardemos cambios en algún archivo del proyecto, estos se actualizarán automáticamente en Localhost.

### Subir cambios al repositorio de GitHub y Mintlify

Al realizar un commit dentro del proyecto, los cambios se subirán automáticamente tanto al repositorio de GitHub como al panel de control de Mintlify.