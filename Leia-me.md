#include <stdio.h>
#include <stdlib.h>
#include <locale.h>

int main(void){
    setlocale(LC_ALL, "Portuguese");

    printf("Olá. \n\n");
    printf("Me chamo João Vitor R. da Silva. \n");
    printf("Atualmente estudo linguagem C através de livros e cursos online. \n");
    printf("Meu objetivo é poder contribuir para a comunidade open source e trabalhar em projetos pessoais. \n");
    printf("E quem sabe um dia ter a oportunidade de entrar no mercado de trabalho. \n\n");

    /*printf("Para entrar em contato comigo: https://www.linkedin.com/in/jo%C3%A3o-silva-90bb8722a ");*/


    return 0;
}