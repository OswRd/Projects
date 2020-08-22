</div>
<img src="https://github.com/XUnix-Corp/Projects/blob/master/HBlanqueto/Images/WAllpaper%20Zone1.png" align="center" align="center">
<br>

# PARA CUALQUIER DISTRIBUCIÓN GNU/LINUX
#### Tip: Solo vas a necesitar copiar, pegar estos comandos y agregar unos textos a tu archivo .zshrc

## ¿Qué encontraré aquí?
Aqui podrás encontrar la configuración que utilizo en la terminal de Linux, tanto los temas, plugins y otros tips que te daré para que puedas recrear lo que utiizo.

# Necesitas:
- Zsh
- Oh_my_zsh
- Git

### ¿No sabes instalarlos? Pasate por estos links para tenerlos en tu sistema
- Zsh: https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH
- Oh_my_zsh: https://github.com/ohmyzsh/ohmyzsh
- Git: https://www.atlassian.com/es/git/tutorials/install-git

## Oh_my_zsh Themes 
**Te dejaré el link de descarga de cada una de los temas para Oh_my_zsh, en el caso de el tema ArchCraft lo saqué directamente de la distribución con el mismo nombre, NO OBSTANTE PODRÁN ENCONTRAR LOS TEMAS EN ESTOS REPOSITORIOS**

- Link a los temas: https://github.com/XUnix-Corp/Projects/tree/master/HBlanqueto/Themes

### Passion
- Link: https://github.com/Hblanqueto/ohmyzsh-theme-passion
![passion](https://raw.githubusercontent.com/ChesterYue/ohmyzsh-theme-passion/master/passion.gif)

### Arch Craft 
- Link a la Distro: https://archcraft-os.github.io/
![gif](https://raw.githubusercontent.com/archcraft-os/archcraft-os.github.io/master/img/main.gif) <br />

## Plugins

- **zsh-autosuggestions:** Predice los comandos que vas a escribir
- **zsh-syntax-highlighting:** Resalta los comandos de manera que muestra si esta bien escrito o no

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
plugins=(git)
```
- Después
```bash
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```

## LSD
Creditos: Peltoche
- **Lsd:** Este te muestra una manera diferente de como se ven los archivos al ejecutar "**ls**"


![image](https://raw.githubusercontent.com/Peltoche/lsd/assets/screen_lsd.png)

Para instalarlo, te dejaré su repositorio oficial ya que este esta muy bien explicado y tiene todo lo que necesitas para configurarlo como yo, solo es cuestion de instalarlo según tu distribución Linux y sería todo.

Respositorio: https://github.com/Peltoche/lsd








