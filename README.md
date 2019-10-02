#include <stdio.h>
#include <stdlib.h>

int main()
{
    int ageSpectateur = 0 ;

    printf("bonjour quel age avez vous ?\n");
    scanf("%d", &ageSpectateur);
    if (ageSpectateur<=10)
        { printf ("billet enfant\n");}
     else if (ageSpectateur>17)
        {printf("billet adulte\n");}
     else
        printf("billet adolescent\n");
    return 0;
}

