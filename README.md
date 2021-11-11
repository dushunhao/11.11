#define _CRT_SECURE_NO_WARNINGS

#include<stdio.h>

int main()

{

	int a = printf("Hello world!");
  
	printf("\n%d", a);
  
	
	return 0;
  
}



int main()

{

    int a = 0;
    
    int b = 0;
    
    int c = 0;
    
    scanf("%d %d %d", &a, &b, &c);
    
    printf("score1=%d,score2=%d,score3=%d\n", a, b, c);
    
    return 0;
    
}


int main()
{

    int a = 0;
    
    float b, c, d;
    
    scanf("%d;%f,%f,%f", &a, &b, &c, &d);
    
    printf("The each subject score of No.%ld is %.2f, %.2f, %.2f.", a, b, c, d);
    
    return 0;
    
}


int main()

{

    int a = 0;
    
    int b = 0;
    
    int c = 0;
    
    scanf("%4d%2d%2d", &a, &b, &c);
    
    printf("year=%4d\n", a);
    
    printf("month=%02d\n", b);
    
    printf("date=%2d\n", c);
    
    return 0;
    
}

int main()

{

    int a, b;
    
    scanf("a=%d,b=%d", &a, &b);
    
    int tmp = a;
    
    a = b;
    
    b = tmp;
    
    printf("a=%d,b=%d", a, b);
    
    return 0;
    
}

int main()

{

    int a = 40;
    
    int c = 212;
    
    int num = (-8 + 22) * a - 10 + c / 2;
    
    printf("%d", num);
    
    return 0;
    
}

int main()

{

    int a = 0;
    
    int b = 0;
    
    scanf("%d %d", &a, &b);
    
    int num1 = a / b;
    
    int num2 = a % b;
    
    printf("%d %d\n", num1, num2);
    
    return 0;
    
}

int main()

{

    int n = 0;
    
    scanf("%d", &n);//n=1234
    
    int a = n % 10;//4
    
    int b = n / 10 % 10;//3
    
    int c = n / 100 % 10;//2
    
    int d = n / 1000;//1
    
    printf("%d%d%d%d", a, b, c, d);
    
    return 0;
    
}

int main()

{

    int a = 0;
    
    int b = 0;
    
    scanf("%d %d", &a, &b);
    
    int num = a + b;
    
    int n1 = num % 10;//5
    
    int n2 = num / 10 % 10;//2
    
    int sum = n2 * 10 + n1;
    
    printf("%d", sum);
    
    return 0;
    
}

int main()

{

    float a = 0;
    
    scanf("%f", &a);
    
    int b = (int)a % 10;
    
    printf("%d\n", b);
    
    return 0;
    
}

#include<math.h>

int main()

{

	int a = 0;
  
	scanf("%d", &a);
  
	long b = a * 3.156 * pow(10, 7);
  
	printf("%ld", b);
  
	return 0;
  
}

int main()

{

	int a = 0;
  
	scanf("%d", &a);//3661
  
	int n1 = a % 60;//1
  
	int n2 = a / 60 % 60;//1
  
	int n3 = a / 3600;//1
  
	printf("%d %d %d", n3, n2, n1);
  
	return 0;
  
}

int main()

{

    float a = 0;
    
    float b = 0;
    
    float c = 0;
    
    scanf("%f %f %f", &a, &b, &c);
    
    float n = a + b + c;
    
    float s = n / 3;
    
    printf("%.2f %.2f", n, s);
    
    return 0;
    
}

int main()

{

    float a = 0;//身高
    
    float b = 0;//体重
    
    scanf("%f %f", &b, &a);
    
    float a1 = a / 100.00;
    
    printf("%.2f", b / (a1 * a1));
    
    return 0;
    
}

#include<math.h>

int main()

{
    float a1 = 0;
    
    float a2 = 0;
    
    float a3 = 0;
    
    scanf("%f %f %f", &a1, &a2, &a3);
    
    float circumference = a1 + a2 + a3;
    
    float p = circumference / 2;
    

    float area = sqrt(p * (p - a1) * (p - a2) * (p - a3));
    
    printf("circumference=%.2f area=%.2f", circumference, area);
    
    return 0;
    
}

int main()

{

    float r = 0;
    
    double π = 3.1415926;
    
    scanf("%f", &r);
    
    float V = 4.0 / 3 * π * r * r * r;
    
    printf("%.3f", V);
    
    return 0;
    
}

int main()

{

    char a = 0;
    
    char b = 0;
    
    scanf("%c %c", &a, &b);
    
    printf("%c\n", a+32);
    
    printf("%c\n", b+32);
    
    return 0;
    
}

int main()

{

    int n = 0;
    
    int s = 1;
    
    int b = 1;
    
    scanf("%d", &n);
    
    while (s <= n)
    
    {
    
        b = b << 1;
        
        s++;
        
    }
    
    printf("%d\n", b);
    
    return 0;
    
}

int main()

{

    int n = 0;//8
    
    int h = 0;//5
    
    int m = 0;//16
    
    int sum = 0;
    
    scanf("%d %d %d", &n, &h, &m);
    
    if (m % h != 0)
    
    {
    
        sum = n - (m / h + 1);
        
    }
    
    else
    
    {
    
        sum = n - (m / h);
        
    }
    
    printf("%d\n", sum);
    
    return 0;
    
}
