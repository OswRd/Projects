</div>
<img src="https://github.com/XUnix-Corp/Projects/blob/master/HBlanqueto/Images/WAllpaper%20Zone1.png" align="center" align="center">
<br>

# PARA CUALQUIER DISTRIBUCIÓN GNU/LINUX
#### Tip: Solo vas a necesitar copiar, pegar estos comandos y agregar unos textos a tu archivo .zshrc

## ¿Qué encontraré aquí?
Aqui podrás encontrar la configuración que utilizo en la terminal de Linux, tanto los temas, plugins y otros tips que te daré para que puedas recrear lo que utiizo.

## Comenzemos..

### Temas que utilizo


### Plugins

- **zsh-autosuggestions:** Predice los comandos que vas a escribir
- **zsh-syntax-highlighting:** Resalta los comandos de manera que muestra si esta bien escrito o no
- **Lsd:** Este te muestra una manera diferente de como se ven los archivos al ejecutar "**ls**"

### Instalación

**Descargar zsh-autosuggestions**
```bash
~ $ git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```
**Descargar zsh-syntax-highlighting**
```bash
~ $ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

**Una vez lo tengas instalado**

- Ejecuta: **nano ~/.zshrc** y busca el apartado que dice **plugins=(git)**
- Ahí mismo deves agregar el siguiente texto: zsh-autosuggestions zsh-syntax-highlighting

**Ejemplo de como debe ser**
Como te lo estoy mostando aqui, debes hacerlo igual en el tuyo para que pueda funcionar

- Antes
```bash
plugins(git)
```
- Después
```bash
plugins(git zsh-autosuggestions zsh-syntax-highlighting)
```








