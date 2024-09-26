#include <stdio.h>

int main() {
    char nom[20];
    char prenom[20];
    char email[40];
    int age;
    char sexe;
    printf("entre nom de etudiant : ");
    scanf("%s",&nom);
    
    printf("entre prenom de etudiant: ");
    scanf("%s" ,&prenom);
    
    printf("entre age. de etudiant: ");
    scanf("%d" ,&age);
    
    printf("entre sexe de etudiant: ");
    scanf("%s" ,&sexe);
    
    printf("entre adresse email de etudiant: ");
    scanf("%s", email); 
}