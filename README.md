# The-function-named-odd_-even-to-find-out-whether-the-integer-sent-into-it-is-odd-or-even-and-prints-
The function named odd_ even to find out whether the integer sent into it is odd or even and prints to the screen. C Program.
int main(void)
{
    int num;
    printf("Enter a number : ");
    scanf("%i",&num);
    if( num % 2 == 0 )
        printf("\n%i is an even number.", num);
    else
        printf("\n%i is an odd number.", num);
    return 0;
}




