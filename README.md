#include<stdio.h>
main()
{   
    float GPA[20],sum=0;
    int i,courses ;
    printf("Numbers of course :");
    //value of n
    scanf("%d",&courses);
    //value of courses 
    for(i=0;i<courses;i++)
    {
       printf("Enter GPA of courses %d:",i+1);
       scanf("%f"& GPA [i]);
       //array value 
       sum=sum+GPA[i];
       //total value
    }
      printf("Average GPA is:%.2f",sum/(float)courses);
      //avg result 
}
