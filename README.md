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

sudo apt install sassc lib

```
sudo apt install sassc libglib2.0-dev-bin libglib2.0-dev libxml2-utils
```

### Instalar o tema
```
git clone https://github.com/vinceliuice/WhiteSur-gtk-theme.git ~/custom-theme/whitesur-gtk-theme
cd $HOME/custom-theme/whitesur-gtk-theme
./install.sh
```

