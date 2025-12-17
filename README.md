# input-matrix-using-arrays-in-c

#include <stdio.h>
int main(){
int i,j,a[3][4];
int b[3][4];
//scan elements for a and b matrix:
printf("A: ");
for(i=0;i<3;i++){
        printf("\n");
for(j=0;j<4;j++){
printf("a[%d][%d]: ",i,j);
scanf("%d",&a[i][j]);
}
}
printf("\n");
for(i=0;i<3;i++){
    printf("\n");
    for(j=0;j<4;j++){
        printf("b[%d][%d]: ",i,j);
        scanf("%d",&b[i][j]);
    }
}
printf("\n\n");
//printing elements for a and b matrix:
printf("A: ");
for(i=0;i<3;i++){
        printf("\t");
for(j=0;j<4;j++){
printf("%d ",a[i][j]);
}
printf("\n");
}
printf("\n\n");
printf("B: ");
for(i=0;i<3;i++){
    printf("\t");
    for(j=0;j<4;j++){
        printf("%d ",b[i][j]);
    }
    printf("\n");
}
}
