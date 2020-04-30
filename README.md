## Tablas de Multiplicar en Consola

Esta es una aplicación para generar archivos .txt de tablas de múltiplicar a través de la consola de comandos

Después de clonar el repositorio ejecuta el siguiente comando:

```
npm install
```

Para probar la aplicación puedes ensayar este par de comandos:

# Para crear una Tabla

```
node app crear --limite 3 --base 5

ó

node app crear --limite 3 -b 5
```

# Para listar una Tabla 

```
node app listar --limite 3 --base 5

ó

node app listar --limite 3 -b 5
```

El limite es opcional, ya que esta definido por defecto que este sea igual a 10