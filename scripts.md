### Actualizar o sistema

```
$ sudo apt update && sudo apt upgrade -y
```

### Adicionar um programa à PATH do sistema

Abrir o ficheiro ```.profile``` que está escondido na /home/o_seu_user e acrescentar:

```
export PATH=$PATH:/path/to/my/program
```

De forma a ficar com acesso ao programa, basta carregar novamente para sessão as variáveis contidas no ficheiro ```.profile``` usando o seguinte comando:
```
source <caminho para o .profile>
```

Nota: Na variável do **PATH** inclui-se o caminho para o directório onde o software está e não o caminho completo para o software.
