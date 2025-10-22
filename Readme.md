
## Parcial

### Creacion del repositorio

```
    brew instal gh
    gh auth login

```
- Luego de elegir github.com
- Autenticacion por repo
- https como método de conexión

```

gh repo create mi-proyecto --public --source=. --remote=origin

```

Luego completar versionando 

```

    git add .
    git commit -m "Initial commit"
    git push -u origin main

```

### Iniciar la aplicacion
fastapi dev main.py

Para produccion se usa: fastapi main.py como figura en render.yaml. No es necesario configurar deploy continuo

Si falla usar 
```unicorn fastapi dev main.py```