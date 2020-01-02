# Curso de Introdução ao [Laravel](https://laravel.com/) (5.3) - [GuiaCódigo](https://www.udemy.com/course/introducao-ao-laravel-53/)

* Instalar e configurar um projeto com Laravel
* Trabalhar com Rotas do Laravel
* Implementar com *Blade*
* Trabalhar com Migrações
* Criar registros com *Tinker*
* Realizar um CRUD com Laravel
* Implementar um sistema de *Login* com Laravel

###  Requisitos:
  * PHP >= 5.6.4
  * OpenSSL PHP *Extension*
  * PDO PHP *Extension*
  * Mbstring PHP *Extension*
  * Tokenizer PHP *Extension*
  
###  Instalação do [Composer](https://getcomposer.org/)
  O *Composer* é um gerenciador de bibliotecas PHP, e será usando para configuração dos projetos.
  Para instalação do *Composer* use:

  > sudo apt install composer
  
  ###  Criando Novo Projeto
  Para iniciar um novo projeto usando o *Composer*, no seu diretório de preferência, use:
  
  > composer create-project --prefer-dist laravel/laravel [nome_do_projeto] [versão_do_laravel*]
  
  *A versão do lavarel é opcional.
  
  ###  Rodando Servidor PHP
  Para iniciar o servidor local PHP sem a necessidade de download de um servidor Apache, entre no diretório que foi criado com as dependência do laravel e use:
  
  > php artisan serve 
  
  Assim que executar esse comando será informado o local e a porta em que o servidor está rodando.
  
  
  ### Comandos PHP
 
  Para criar uma Controller:
  > php artisan make:controller [nome_da_controller]
  
  Para criar um modelo: 
  >php artisan make:model [nome_do_model]
  
  Para criar uma nova Classe Seeder:
 >php artisan make:seeder
