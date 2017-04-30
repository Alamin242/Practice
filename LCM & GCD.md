# Practice
For Exam 
/*---------LCM & GCD---------------*/
    int a,b,c,x,y,gcd,lcm;
    printf("Insert Two Number\n");
    scanf("%d%d",&x, &y);
    a=x;
    b=y;
    while(b!=0)
    {
        c=a%b;
        a=b;
        b=c;
    }
    gcd=a;
    lcm=(x*y)/gcd;
    printf("GCD of %d and %d= %d\n",x,y,gcd);
    printf("LCM of %d and %d= %d",x,y,lcm);
}
