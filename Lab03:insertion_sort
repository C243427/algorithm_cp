#include<stdio.h>
int main(){
    int n,k;
    printf("enter the element number ");
    scanf("%d",&n);
    int arr[n+1];
    printf("enter the elements:");
    for(int i=0;i<n;i++){
        scanf("%d",&arr[i]);
    }
    for(int i=0;i<n;i++){
        k=arr[i];
       int j= i-1;
       while (j>=0 && arr[j]> k){
           arr[j+1]=arr[j];
           j--;
       }
       arr[j+1]=k;
    }
    printf("sorted values are:"); 
    for(int i=0;i<n;i++){
        printf("%d  ",arr[i]);
    }
    return 0;
}
