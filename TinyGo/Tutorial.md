Usando o TinyGo! Muito simples. 

Basei-me no tutorial desse video:

TinyGo on the Raspberry Pi Pico

https://www.youtube.com/watch?v=Fl5eFIYU1Xg

Para instalar Go:

https://go.dev/doc/install

Para instalar o TinyGo usei esse guia:

https://tinygo.org/getting-started/install/windows/

Eu uso o VS Code IDE - é o melhor atualmente para editar o programa. 

https://code.visualstudio.com/docs/setup/windows

Configuração no VScode:

https://tinygo.org/docs/guides/ide-integration/vscode/

Instale a extensão TinyGo também. 

Crie uma pasta para editar os seus programas. Por exemplo:

C:\Users\jgust\tinygo\programas\Blinky>

Edite o programa Blinky nessa pasta acima. O exemplo está nesse link: 

https://tinygo.org/docs/tutorials/blinky/

No meu caso chamei o programa de main.go

Dê os comandos do GO dentro da pasta Blinky

go mod init main.go
go mod tidy
Aperte o botão de boot do Raspberry Pico e conecte o cabo USB no seu PC. 

Para compliar e gravar no Raspberry Pico, dê o comando abaixo. 

tinygo flash -target=pico main.go



Site do TinyGo no Github

https://github.com/tinygo-org

TinyGo - Go compiler for small places

https://github.com/tinygo-org/tinygo

Drivers:

https://github.com/tinygo-org/drivers

Visual Studio Code support for TinyGo
https://github.com/tinygo-org/vscode-tinygo
