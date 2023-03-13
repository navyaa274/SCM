# SCM
Source Code Management Project
#include<stdio.h>
#include<string.h>
struct Driver
{
    char Name[34];
    char DlNo[45];
    char Route[47];
    int Kms;
};


int main()
{
    struct Driver d1,d2,d3;
    printf("enter the details of drivers\n");

    printf("Enter the details of drivers number 1\n");
    printf("Enter the name of first drive:");
    scanf("%s",&d1.Name);
    printf("\n");



    printf("Enter the dlNo. of first drive:");
    scanf("%s",&d1.DlNo);
    printf("\n");


    printf("Enter the route of first drive:");
    scanf("%s",&d1.Route);
    printf("\n");


    printf("Enter the Kms of first drive:");
    scanf("%d",&d1.Kms);
    printf("\n");


    printf("Enter the details of driver number 2\n");

    printf("Enter the name of second drive:");
    scanf("%s",&d2.Name);
    printf("\n");


    printf("Enter the dlNo. of second drive:");
    scanf("%s",&d2.DlNo);
    printf("\n");


    printf("Enter the route of second drive:");
    scanf("%s",&d2.Route);
    printf("\n");


    printf("Enter the Kms of second drive:");
    scanf("%d",&d2.Kms);
    printf("\n");


    printf("Enter the details of driver number 3\n");

    printf("Enter the name of third drive:");
    scanf("%s",&d3.Name);
    printf("\n");


    printf("Enter the dlNo. of third drive:");
    scanf("%s",&d3.DlNo);
    printf("\n");


    printf("Enter the route of third drive:");
    scanf("%s",&d3.Route);
    printf("\n");


    printf("Enter the Kms of third drive:");
    scanf("%d",&d3.Kms);
    printf("\n");


    printf("****printing information of the following drivers****\n");
    printf("for driver number 1:\nName is %s\n",d1.Name);
    printf("DL Number is %s\n",d1.DlNo);
    printf("Route is %s\n",d1.Route);
    printf("Kms are %d Kms\n",d1.Kms);

    printf("for driver number 2:\nName is %s\n",d2.Name);
    printf("DL Number is %s\n",d2.DlNo);
    printf("Route is %s\n",d2.Route);
    printf("Kms are %d Kms\n",d2.Kms);

    printf("for driver number 3:\nName is %s\n",d3.Name);
    printf("DL Number is %s\n",d3.DlNo);
    printf("Route is %s\n",d3.Route);
    printf("Kms are %d Kms\n",d3.Kms);


    return 0;

}
