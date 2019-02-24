### Actualizar o sistema

```
$ sudo apt update && sudo apt upgrade -y
```

### Adicionar um programa à PATH do sistema

Abrir o ficheiro ```.profile``` que está escondido na /home/o_seu_user e acrescentar:

```
export PATH=$PATH:/path/to/my/program
```

fazer logout e login de novo e o programa fica acessivel no terminal. Na linha anterior basta incluir a pasta onde está o programa e não o ficheiro do programa.
