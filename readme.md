# learn from chai aur code

## Install

To install the necessary dependencies, run the following command:

```sh
npm install
```

## Run 

To run the necessary dependencies, run the following command:

```sh
npm run dev
```

## To install specific package

Installs a specific package and adds it to your package.json file as a dependency. 

```sh
npm install <package-name>
```

## To install specific package as development

Installs a package as a development dependency (used during development, not production).

```sh
npm install --save-dev <package-name>
```
or
```sh
npm install -D <package-name> 
```

## To install specific package as production

Installs a package as a production dependency (used in the final application). 

```sh
npm install --save-prod <package-name>
```
or
```sh
npm install -S <package-name>
```

## To install specific package as optional dependency

Installs a package as an optional dependency.  

```sh
npm install --save-optional <package-name>
```
or
```sh
npm install -O <package-name>
```

## To install specific package as peer dependency

Installs a package as a peer dependency. 

```sh
npm install --save-peer <package-name>
```

## To install specific version of a package

Installs a specific version of a package. 

```sh
npm install <package-name>@<version>
```

## To install specific version of a package

Installs a package without adding it to package.json. 

```sh
npm install --no-save
```
