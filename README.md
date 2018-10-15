# Vagrant

### Instalação Windows
  * [Guia](http://www.mateuspaduaweb.com.br/instalar-o-vagrant-e-utiliza-lo-como-ambiente-de-desenvolvimento-no-windows/)

Baixar e instalar na sequência:
  1. [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
  2. [Vagrant](https://www.vagrantup.com/downloads.html)
  3. [PuTTY](https://www.putty.org/)

Criar a pasta `C:\vagrant\<NOME_DA_PASTA>`

Inicie o `cmd` como administrador dentro da pasta criada e execute:
```
vagrant init ubuntu/trusty64
vagrant up
```

Depois de instalado a box, executar `vagrant ssh` para acessar a box.
