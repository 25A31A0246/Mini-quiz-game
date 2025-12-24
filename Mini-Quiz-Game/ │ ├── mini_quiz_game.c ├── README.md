# Mini-quiz-game
#include <stdio.h>

int main() {
    int score = 0;
    int answer;

    printf("=================================\n");
    printf("       MINI QUIZ GAME\n");
    printf("=================================\n\n");

    // Question 1
    printf("1. What is the capital of India?\n");
    printf("1) Mumbai\n2) Delhi\n3) Chennai\n4) Kolkata\n");
    printf("Enter your answer: ");
    scanf("%d", &answer);

    if (answer == 2) {
        score++;
    }

    // Question 2
    printf("\n2. Which language is used for system programming?\n");
    printf("1) Python\n2) Java\n3) C\n4) HTML\n");
    printf("Enter your answer: ");
    scanf("%d", &answer);

    if (answer == 3) {
        score++;
    }

    // Question 3
    printf("\n3. Who is the father of C language?\n");
    printf("1) Dennis Ritchie\n2) James Gosling\n3) Bjarne Stroustrup\n4) Guido van Rossum\n");
    printf("Enter your answer: ");
    scanf("%d", &answer);

    if (answer == 1) {
        score++;
    }

    // Question 4
    printf("\n4. Which symbol is used for comments in C?\n");
    printf("1) //\n2) <!-- -->\n3) #\n4) **\n");
    printf("Enter your answer: ");
    scanf("%d", &answer);

    if (answer == 1) {
        score++;
    }

    // Question 5
    printf("\n5. Which data type is used to store decimal values?\n");
    printf("1) int\n2) char\n3) float\n4) double\n");
    printf("Enter your answer: ");
    scanf("%d", &answer);

    if (answer == 3) {
        score++;
    }

    printf("\n=================================\n");
    printf("Quiz Completed!\n");
    printf("Your Score: %d / 5\n", score);
    printf("=================================\n");

    if (score >= 4) {
        printf("Excellent performance! 🎉\n");
    } else if (score >= 2) {
        printf("Good job! Keep practicing 👍\n");
    } else {
        printf("Better luck next time 😊\n");
    }

    return 0;
}
