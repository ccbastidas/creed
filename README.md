# creed
# para permitir peticiones al backend sin problema de cors se debe crear el archivo proxy.conf.json 
# de igual forma se debe poner en el angular json 

  "serve": {
    "options": {
      "proxyConfig": "proxy.conf.json"
    }
  }

# .ignore me quita las librerias de node modules 
