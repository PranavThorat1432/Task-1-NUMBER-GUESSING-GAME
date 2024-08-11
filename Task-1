#include <iostream>
#include <cstdlib>   // For rand() 
#include <ctime>     // For time()

using namespace std;

int main() {

    // Generate a random number between 1 to 100
    int randomNumber = rand() % 100 + 1;
    int guess;
    int attempts = 0;
    bool correct = false;

    cout << "Welcome to the Random Number Guessing Game!" << endl;
    cout << "Can You guess a number between 1 to 100?" << endl;

    // Loop until the user guesses correctly
    while (!correct) {
        cout << "Enter your guess: ";
        cin >> guess;
        attempts++;

        if (guess == randomNumber) {
            cout << "Congratulations! You guessed the correct number (" << randomNumber << ") in " << attempts << " attempts." << endl;
            correct = true;
        } else if (guess < randomNumber) {
            cout << "Too low! Try guessing a higher number." << endl;
        } else {
            cout << "Too high! Try guessing a lower number." << endl;
        }
    }

    return 0;
}