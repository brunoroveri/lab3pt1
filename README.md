LABORATÓRIO DE SISTEMAS OPERACIONAIS - PTHREADS PARTE 1

Bruno Roveri - 10401752

Lucas Farias - 10402521

Leonardo Binder - 10402289

Execução da instância AWS e instalação do git no terminal:
![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/1317e845-c793-4616-9229-33813d87088a)

Geração da chave SSH e clonagem do repositório:
![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/88e3f34d-7ba7-4bab-b850-f9c9a878b903)

Criação do arquivo para o exercício dentro da pasta 'lab03':
![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/e116c42c-d95f-4489-9b39-b859efd148a2)

Código desenvolvido:
![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/bf754be8-b797-4918-949b-8594a5b9818a)
![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/19699f8d-4910-4161-90d0-c6595133a7fb)
![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/2df6cec2-67e8-404c-9f88-beddce4b96f8)

Envio do arquivo criado para staging area, realização do commit e do push ao repositório:
![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/23813105-bd09-4fef-8823-33f741bbfe15)

Instruções para compilação e execução do código:

Compilação:
Use o compilador gcc para compilar o código. O código utiliza a biblioteca pthread para threads, então é necessário incluir a flag -lpthread:


gcc nome_do_arquivo.c -o nome_do_programa -lpthread
Execução:
Para executar o programa, você precisa especificar o número de threads como argumento. Por exemplo, para executar o programa com 4 threads:

./nome_do_arquivo 4


Demonstração do código em funcionamento:

![image](https://github.com/brunoroveri/lab3pt1/assets/142548195/ef5bb2cb-30d1-490d-8f2c-dee044a115ba)

