QUIZ GAME














#include <stdio.h>

int main() // initialization of code
{
    int i;
    int ans1, ans2, ans3, ans4, ans5, ans6, ans7, ans8, ans9, ans10;
    int total;
    int points = 0;
    printf("   Welcome to the Game\n");
    printf("> press 7 to start the game\n");
    printf("> press 0 to quit the game\n");
    scanf("%d", &i);

    if (i == 7)
    {
        printf(" 5 points added on a correct answer\n 5 points deducted on a wrong answer\n");

        printf("The game has been started \n");
        printf("i) Which one is the first search engine on the internet? \n");
        printf(" 1) Google \n 2) Archie \n 3) Wais \n 4) Altavista \n");
        printf("Enter your answer: ");
        scanf("%d", &ans1);
        if (ans1 == 2)
        {
            printf("Congratulations! Your answer is correct. But the next one is different. \n");
            points += 5;
        }
        else
        {
            printf("Wrong answer! Try again.\n");
            points -= 5;
        }
        printf(" ii) Which of the following is NOT a type of computer memory?\n");
        printf(" 1) RAM \n 2) ROM \n 3) CPU \n 4) CACHE \n");
        printf("Enter your answer: \n");
        scanf("%d", &ans2);
        if (ans2 == 3)
        {
            printf("Congratulations! Your answer is correct. You've got the game. \n");
            points += 5;
        }
        else
        {
            printf("Wrong answer! Try again.\n");
            points -= 5;
        }
        printf(" iii) What does the acronym 'CPU' stand for: \n");
        printf(" 1) Core Processing Unit \n 2) Computer Processing Unit \n 3) Control Processing Unit \n 4) Central Processing Unit \n");
        printf("Enter your answer: \n");
        scanf("%d", &ans3);
        if (ans3 == 4)
        {
            printf("Congratulations! Your answer is correct. It's just the start of your journey. \n");
            points += 5;
        }
        else
        {
            printf("Wrong answer! Try again.\n");
            points -= 5;
        }

        printf(" iv) Which programming language is often used for web development? \n");
        printf(" 1) Python \n 2) Java \n 3) C++ \n 4) JavaScript \n");
        printf("Enter your answer: \n");
        scanf("%d", &ans4);
        if (ans4 == 4)
        {
            printf("Congratulations! Your answer is correct. Keep going. \n");
            points += 5;
        }
        else
        {
            printf("Wrong answer! Try again.\n");
            points -= 5;

            printf(" v) What is the purpose of an operating system? \n");
            printf(" 1) To store data on a hard drive \n 2) To run applications on a computer \n 3) To connect to the internet \n 4) To create software programs \n");
            printf("Enter your answer: \n");
            scanf("%d", &ans5);
            if (ans5 == 2)
            {
                printf("Congratulations! Your answer is correct. You are doing great. \n");
                points += 5;
            }
            else
            {
                printf("Wrong answer! Try again.\n");
                points -= 5;
            }

            printf(" vi) What does the term 'bandwidth' refer to? \n");
            printf(" 1) The amount of data that can be transmitted over a network in a given time \n 2) The speed of a computer's processor \n 3) The size of a computer's hard drive \n 4) The amount of RAM in a computer \n");
            printf("Enter your answer: \n");
            scanf("%d", &ans6);
            if (ans6 == 1)
            {
                printf("Congratulations! Your answer is correct. Keep working hard. \n");
                points += 5;
            }
            else
            {
                printf("Wrong answer! Try again.\n");
                points -= 5;
            }
            printf(" vii) What is the function of a firewall? \n");
            printf(" 1) To speed up internet connections \n 2) To protect a computer network from unauthorized access \n 3) To store data on a remote server \n 4) To create backups of computer files \n");
            printf("Enter your answer: \n");
            scanf("%d", &ans7);
            if (ans7 == 2)
            {
                printf("Congratulations! Your answer is correct. Keep the pace! \n");
                points += 5;
            }
            else
            {
                printf("Wrong answer! Try again.\n");
                points -= 5;
            }
            printf(" viii) What does the acronym 'HTML' stand for? \n");
            printf(" 1) Home Tool Markup Language \n 2) Hypertext Machine Language \n 3) Hypertext and Links Markup Language \n 4) Hypertext Markup Language \n");
            printf("Enter your answer: \n");
            scanf("%d", &ans8);
            if (ans8 == 4)
            {
                printf("Congratulations! Your answer is correct. \n");
                points += 5;
            }
            else
            {
                printf("Wrong answer! Try again.\n");
                points -= 5;
            }
            printf(" ix) Which of the following is NOT a common input device? \n");
            printf(" 1) Keyboard \n 2) Mouse \n 3) Monitor \n 4) Printer \n");
            printf("Enter your answer: \n");
            scanf("%d", &ans9);
            if (ans9 == 3)
            {
                printf("Congratulations! Your answer is correct. Almost done! \n");
                points += 5;
            }
            else
            {
                printf("Wrong answer! Try again.\n");
                points -= 5;
            }

            printf(" x) What is the term for software that is designed to harm a computer system?\n");
            printf(" 1) Antivirus \n 2) Malware \n 3) Firewall \n 4) Spam \n");
            printf("Enter your answer: \n");
            scanf("%d", &ans10);
            if (ans10 == 2)
            {
                printf("Congratulations! Your answer is correct. You've got the game. \n");
                points += 5;
            }
            else
            {
                printf("Wrong answer! Try again.\n");
                points -= 5;
            }

            printf("Total points: %d\n", points);
        }
    }
    else if (i == 0)
    {
        printf("The game has ended.\n");
    }
    else
    {
        printf("Invalid input.\n");
    }

    return 0; // ending of code
}
