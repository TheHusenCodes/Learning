# Learning
During learning time


// Online C compiler to run C program online
#include <stdio.h>
#include <string.h>

struct student{
    int roll;
    float cgp;
    char name[100];
};
int main() {
    struct student s1;
    s1.roll = 07;
    s1.cgp = 9.0;
    strcpy(s1.name,"Sneha");
    
    printf("Student name: %s\n",s1.name);
    printf("Student Roll no: %d\n",s1.roll);
    printf("Student CGP: %f\n",s1.cgp);
    
    struct student s2;
    s2.roll = 8;
    s2.cgp = 8.9;
    strcpy(s2.name,"reshma");
    
    printf("Student name: %s\n",s2.name);
    printf("Student Roll no: %d\n",s2.roll);
    printf("Student CGP: %f\n",s2.cgp);


  struct student s3;
  s3.roll =9;
  s3.cgp =7.8;
  strcpy(s3.name,"Husen");
  
    printf("Student name: %s\n",s3.name);
    printf("Student Roll no: %d\n",s3.roll);
    printf("Student CGP: %f\n",s3.cgp);  
    return 0;
}
