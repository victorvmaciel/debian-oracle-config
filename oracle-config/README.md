Script para instalar oracle em Debian para configuração do ambiente de Dev Ruby on Rails

*Dar permissão ao arquivo*

    $ chmod a+x oracle-config.sh

*Necessário instalar o unzip*

    $ sudo apt install unzip
    
*Carregar as env do oracle*

    $ source ~/.oracle
    
 Fechar o terminal 
 
*Instalar a GEM ruby-oci8  e instalar o Oracle enhance utilizando o rmv

*No Gemfile do Projeto adicionar a linha activerecord-oracle_enhanced-adapter e a ruby-oci8. Ver na figura abaixo como ficará o Gemfile.


    $gem 'activerecord-oracle_enhanced-adapter'
    $gem 'ruby-oci8'
    
OBS: essa gem tem que estar no GEMFILE do projeto.
    
    $gem install ruby-oci8
    $gem install activerecord-oracle_enhanced-adapter



