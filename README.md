#inciude <studio.h>

int main() {
    char operator;
    double first, second;
    printf("Enter the operator (+, -, *, /) : ");
    scanf("%c",&operator);

    printf("Enter the two Numbers one by one : ");
    scanf("%lf %lf",&first,&second);

    switch (operator){

    case '+':
      printf("%.lf + %.lf = %.lf", first, second, first + second);
      break;
    case '-':
      printf("%.lf - %.lf = %.lf", first, second, first - second);
      break;
    case '*':
      printf("%.lf * %.lf = %.lf", first, second, first * second);
      break;
    case '/':
      printf("%.lf / %.lf = %.lf", first, second, first / second);
      break;
     // operator doesn't match any case constant
     default:
       printf("Error! operator is not correct");
    }

    return operator;
    }

    return 0;
}
