#include <iostream>
#include <stdlib.h>
#include <iomanip>
#include <cmath>

using namespace std;

// Define a class named question1
class question1 {
public:
    // Define a public method called myMethod
    void myMethod() {
        string nm;
        string cn = "Animal Adventure";
        char an;

        // Display a decorative title
        cout << "  ___        _                 _    ___      _                 _                  " << endl;
        cout << " / _ \\      (_)               | |  / _ \\    | |               | |                 " << endl;
        cout << "/ /_\\ \\_ __  _ _ __ ___   __ _| | / /_\\ \\ __| |_   _____ _ __ | |_ _   _ _ __ ___ " << endl;
        cout << "|  _  | '_ \\| | '_ ` _ \\ / _` | | |  _  |/ _` \\ \\ / / _ \\ '_ \\| __| | | | '__/ _ \\" << endl;
        cout << "| | | | | | | | | | | | | (_| | | | | | | (_| |\\ V /  __/ | | | |_| |_| | | |  __/" << endl;
        cout << "\\_| |_/_| |_|_|_| |_| |_|\\__,_|_| \\_| |_/\\__,_| \\_/ \\___|_| |_|\\__|\\__,_|_|  \\___|\n" << endl;

        // Ask for the user's name
        cout << "Enter your name: \n";
        cin.ignore();
        getline(cin, nm);

        cout << "\n" << nm << ", this program will allow you to investigate the names and spellings of unusual animals.\n";
        cout << "The computer can offer you information on animal names beginning with the letters A, C, H, M, P, and W.\n";

        // Ask the user to enter a letter
        cout << "\nEnter a letter: ";
        cin >> an;

        cout << "\n";

        // Use a switch statement to display information based on the entered letter
        switch (an) {
            case 'A':
            case 'a':
                cout << "Animals beginning with the letter ‘A’ include anteater, armadillo, and aardvark.\n";
                break;

            case 'C':
            case 'c':
                cout << "Animals beginning with the letter ‘C’ include caribou, Chihuahua, and Clydesdale.\n";
                break;

            case 'H':
            case 'h':
                cout << "Animals beginning with the letter ‘H’ include Hanoverian, hippopotamus, and hyena.\n";
                break;

            case 'M':
            case 'm':
                cout << "Animals beginning with the letter ‘M’ include manatee, marmot, and mongoose.\n";
                break;

            case 'P':
            case 'p':
                cout << "Animals beginning with the letter ‘P’ include panda, platypus, and porcupine.\n";
                break;

            case 'W':
            case 'w':
                cout << "Animals beginning with the letter ‘W’ include walrus, warthog, and whippet.\n";
                break;

            default:
                cout << "We don't have any animals in our database starting with that letter, please try again :).\n";
        }

        cout << "\n" << nm << ", thank you for using " << cn << "!" << endl;;
    }
};

int main() {
    int question;

    // Ask the user to choose a question
    cout << "Which question would you like to choose ?" << endl;
    cin >> question;

    if (question == 1) {
        question1 myObj;
        myObj.myMethod();
    } else {
        cout << "Invalid question selected" << endl;
    }

    return 0;
}
