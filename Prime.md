# Practice
For Exam 
int main()
{
    int x,y,z,a;

    a=0;
    scanf("%d",&x);
    for(y=1;y<=x;y++)
    {
      z=x%y;
      if(z==0)
      {

          a=a+1;
      }
    }

    if(a==2)
    {

        printf("Prime Number");
    }
    else{
        printf("Not Prime");
    }

}
