Configurando sass:
baixe o node e execute os seguintes comandos:
    1 - npm install -g sass ---> para instalar o sass globalmente.
    2 - sass style.scss style.css ---> para compilar o arquivo scss para css.
    3 - sass --watch style.scss:style.css ---> para ativar o modo **watch** do sass que permite monitorar automaticamente o arquivo.scss e compilar automaticamente sempre que houver alterações.
    
    Obs, se você tiver vários arquivos SCSS, pode observar uma pasta inteira assim: sass --watch scss/:css/
    Nesse caso, todos os arquivos .scss na pasta scss/ serão compilados para .css na pasta css/.