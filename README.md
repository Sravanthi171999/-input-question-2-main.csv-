# -input-question-2-main.csv-
#include <stdio.h>

int main()
{   
    int i;
    for(i=1;i<=24;i++)
    {
        switch(i)
        {
            case 1: printf("\t\t");
                    printf("min  max\n");break;
            case 2: printf("occupation\n");break;   
            case 3: printf("administrator\t""21""  70\n");break;
            case 4: printf("artist\t\t""19""  48\n");break;
            case 5: printf("doctor\t\t""28""  64\n");break;
            case 6: printf("educator\t""23""  63\n");break;
            case 7: printf("engineer\t""22""  70\n");break;
            case 8: printf("entertainment\t""15""  50\n");break;
            case 9: printf("executive\t""22""  69\n");break;
            case 10: printf("healthcare\t""22""  62\n");break;
            case 11: printf("homemaker\t""20""  50\n");break;
            case 12: printf("lawyer\t\t""21""  53\n");break;
            case 13: printf("librarian\t""23""  69\n");break;
            case 14: printf("marketing\t""24""  55\n");break;
            case 15: printf("none\t\t""11""  55\n");break;
            case 17: printf("other\t\t""13""  64\n");break;
            case 18: printf("programmer\t""20""  63\n");break;
            case 19: printf("retaired\t""51""  73\n");break;
            case 20: printf("salesman\t""18""  65\n");break;
            case 21: printf("scientist\t""23""  55\n");break;
            case 22: printf("student\t""23""  55\n");break;
            case 23: printf("technician\t""23""  55\n");break;
            case 24: printf("writer\t""23""  55\n");break;     
        }
    }
    
   
    
    

    return 0;
}
