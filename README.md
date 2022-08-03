# Customizações no Linux Mint

Créditos ao [LinuxScoop](https://www.youtube.com/c/LinuxScoop), baseado no [vídeo](https://www.youtube.com/watch?v=DMs7DX3Um9E).

## Configurações Iniciais

### Janelas

Abra o Menu Iniciar >> Preferências >> Configurações do sistema >> Janelas

![](assets/img/clm-001.png)

Deixe a disposição dos botões a esquerda:

![](assets/img/clm-002.png)

É possível trocar a aparência do ALT + TAB, na aba Alt + Tab:

![](assets/img/clm-003.png)

### Extensões

Abra o Menu Iniciar >> Preferências >> Configurações do sistema >> Extensões:
![](assets/img/clm-004.png)

Na aba de Download, procure ou busque por Transparent panels e faça o download:
![](assets/img/clm-005.png)

Após efetuar o download volte para a aba de 'Gerenciamento', selecione o 'Painéis transparentes', adicione pelo botão '+' e clique no botão de configurações:
![](assets/img/clm-006.png)

Deixe o Tipo de tranparência como 'Semitransparente' e marque 'Usar os estilos do tema atual':
![](assets/img/clm-007.png)

## Install Gtk Theme - Whitesur Gtk Theme Light/Dark

### Dependências
Instale as seguintes dependências:
```
sudo apt install sassc libglib2.0-dev-bin libglib2.0-dev libxml2-utils -y
```

### Instalar o tema
```
git clone https://github.com/vinceliuice/WhiteSur-gtk-theme.git ~/custom-theme/whitesur-gtk-theme
cd $HOME/custom-theme/whitesur-gtk-theme
./install.sh
```

### Instalar os icones
```
git clone https://github.com/vinceliuice/WhiteSur-icon-theme.git ~/custom-theme/whitesur-icon-theme
cd $HOME/custom-theme/whitesur-icon-theme
./install.sh
```

### Instalar o cursor
```
git clone https://github.com/vinceliuice/McMojave-cursors.git ~/custom-theme/mcmojave-cursors
cd $HOME/custom-theme/mcmojave-cursors
./install.sh
```

### Configurando o tema

Abra o Menu Iniciar >> Preferências >> Temas

Selecione icones >> WhiteSur-dark

![](assets/img/clm-008.png)


Selecione aplicativos >> WhiteSur-Dark

![](assets/img/clm-009.png)


Selecione Cursor do Mouse >> McMojave-cursors

![](assets/img/clm-010.png)


Selecione Área de Trabalho >> WhiteSur-Dark

![](assets/img/clm-011.png)


### Mudar a barra do menu

Clique com o botão direito do mouse no meio da barra >> Mover >> Selecione o top

![](assets/img/clm-012.png)


Habilite o modo de edição do menu, clicando com botão direito do mouse >> Modo edição do painel
![](assets/img/clm-013.png)


Remover a 'Lista de janelas agrupadas', clicando com o botão direito do mouse
![](assets/img/clm-014.png)


Remover 'Mostrar àrea de trabalho', clicando com o botão direito do mouse
![](assets/img/clm-015.png)


Remover o 'Menu', clicando com o botão direito do mouse
![](assets/img/clm-016.png)


Adicionar Applets, clicando com o botão direito do mouse na opção 'Applets'
![](assets/img/clm-017.png)


Na aba de Download, baixe os sequintes applets: Cinnamenu, Weather 
![](assets/img/clm-018.png)


#### Configurando Cinnamenu

Na aba de gerenciamento dos applets, selecione o Cinnamenu e clique em +, vai ser adicionando na barra do Menu o icone

![](assets/img/clm-019.png)


Arraste o icone para a esquesda
![](assets/img/clm-020.png)



