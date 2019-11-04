# YAML to PHP - configuração no Linux/Ubuntu

Para instalar  e configurar o YAML no PHP 7.2 segue os passos:

**_1 - Instale as bibliotecas do linux com o seguinte comando:_**

sudo apt install libyaml-dev php-dev php-pear
sudo apt-get install php-xml php7.2-xml

**_2 - Instale o YAML com o seguinte e deixe-o default:_**

pecl install yaml

**_3 - Instale a bibliateca YAML para PHP com so seguinte comando:_**

sudo apt-get install -y php7.2-yaml

**_4 - Coloque no php.ini a seguinte extensão:_**

extension=yaml.so
