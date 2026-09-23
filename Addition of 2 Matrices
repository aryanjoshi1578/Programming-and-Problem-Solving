#include <stdio.h>
int main() {
  int r, c, i, j, mat1[r][c], mat2[r][c], sum[r][c];

  printf("Enter the number of rows and columns: ");
  scanf("%d %d", &r, &c);

  printf("Enter elements of the 1st matrix: ");
  for(i=0, i<=r; i++) {
    for(j=0; j<=c; j++) {
      scanf("%d", &mat1[i][j]);
    }
  }
  printf("Enter elements of the 2st matrix: ");
  for(i=0, i<=r; i++) {
    for(j=0; j<=c; j++) {
      scanf("%d", &mat2[i][j]);
    }
  }
  for(i=0, i<=r; i++) {
      for(j=0; j<=c; j++) {
        sum[i][j]=mat1[i][j]+mat2[i][j];
      }
  }
  printf("Sum of the 2 matrices: ");
  for(i=0, i<=r; i++) {
    for(j=0; j<=c; j++) {
      printf("%d", sum[i][j]);
    }
    printf("\n");
  } 
  return 0;
}
