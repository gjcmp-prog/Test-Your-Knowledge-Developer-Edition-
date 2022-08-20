//10 Question IO console Quiz Game :)

#include <iostream>
#include <stdlib.h>
using namespace std;

int main()
{
    string favfootteam = "Pittsburgh Steelers";             
    string mycollection = "Watches";                       
    string myjusticeleague = "Superman";
    string favelang = "C++";                              
    string zodSign = "Scorpio";
    
    string myavenger = "Hulk";                    
    string retroconsole = "Magnavox Odyssey";              
    string myxmen = "Gambit";
    string mydrink = "Bourbon";
    string mytransformer = "Soundwave";
    



    int footteamguess;
    int collectionguess;
    int justiceleagueguess;
    int langguess;
    int zodSignguess;

    int avengerguess;
    int retroconsoleguess;
    int xmenguess;
    int drinkguess;
    int transformerguess;

    


    cout << "\n\n LET'S PLAY A GAME";
    cin.get(); //waits for user key press
    system("cls"); //clears console screen
    cout << "\n\n Which of the following Professional Football Teams is my favorite ? : ";
    cout << "\n\n 1. Pittsburgh Steelers, 2. Seattle Seahawks, or 3. Minnesota Vikings";
    cin >> footteamguess;
    system("cls");
    if (footteamguess == 1) {
        cin.get();
        cout << "\n\n CORRECT";
        cin.get();
        system("cls");
        cout << "\n\n Reward: + 100 pts.";
        cin.get();
        system("cls");
        cout << "\n\n SCORE: 100 POINTS";
        cin.get();
        system("cls");
        cout << "\n\n Which of these items do I enjoy collecting? :";
        cout << "\n\n 1. Coins, 2. Stamps, or 3. Watches";
        cin >> collectionguess;
        system("cls");
        if (collectionguess == 3) {
            cin.get();
            cout << "\n\n CORRECT";
            cin.get();
            system("cls");
            cout << "\n\n Reward: + 200 pts.";
            cin.get();
            system("cls");
            cout << "\n\n SCORE: 300 POINTS";
            cin.get();
            system("cls");
            cout << "\n\n Whom of the following is my favorite member of the Justice League? :";
            cout << "\n\n 1. The Flash , 2. Superman, or 3. Aquaman";
            cin >> justiceleagueguess;
            system("cls");
            if (justiceleagueguess == 2) {
                cin.get();
                cout << "\n\n CORRECT";
                cin.get();
                system("cls");
                cout << "\n\n Reward: + 300 pts.";
                cin.get();
                system("cls");
                cout << "\n\n SCORE: 600 POINTS";
                cin.get();
                system("cls");
                cout << "\n\n Which of the following is my preferred programming language?:";
                cout << "\n\n 1. Java  2. Python or 3. C++";
                cin >> langguess;
                system("cls");
                if (langguess == 3) {
                    cin.get();
                    cout << "\n\n CORRECT";
                    cin.get();
                    system("cls");
                    cout << "\n\n Reward: + 400 pts.";
                    cin.get();
                    system("cls");
                    cout << "\n\n SCORE: 1,000 POINTS";
                    cin.get();
                    system("cls");
                    cout << "\n\n Which of the following is my zodiac sign?";
                    cout << "\n\n 1. Scorpio 2. Aries or 3. Gemini?";
                    cin >> zodSignguess;
                    system("cls");
                    if (zodSignguess == 1) {
                        cin.get();
                        cout << "\n\n CORRECT";
                        cin.get();
                        system("cls");
                        cout << "\n\n Reward: + 500 pts.";
                        cin.get();
                        system("cls");
                        cout << "\n\n SCORE: 1,500 POINTS";
                        cin.get();
                        system("cls");
                        cout << "\n\n YOU ARE HALFWAY THERE!";
                        cin.get();
                        system("cls");
                        cout << "\n\n Whom is my favorite Avenger?";
                        cout << "\n\n 1. Tony Stark (Ironman) 2. Steve Rogers (Cap') 3. Bruce Banner (Hulk)";
                        cin >> avengerguess;
                        system("cls");
                        if (avengerguess == 3) {
                            cin.get();
                            cout << "\n\n CORRECT";
                            cin.get();
                            system("cls");
                            cout << "\n\n Nuclear Physics is the bomb...Get it ?";
                            cin.get();
                            cout << "\n\n Please say you got that.";
                            cin.get();
                            system("cls");
                            cout << "\n\n Reward: + 600 pts.";
                            cin.get();
                            system("cls");
                            cout << "\n\n SCORE: 2,100 POINTS";
                            cin.get();
                            system("cls");
                            cout << "\n\n Which Retro Gaming Console do I want to try out?";
                            cout << "\n\n 1. Atari 2600 2. Magnavox Odyssey 3. ColecoVision";
                            cin >> retroconsoleguess;
                            system("cls");
                            if (retroconsoleguess == 2) {
                                cin.get();
                                cout << "\n\n CORRECT";
                                cin.get();
                                system("cls");
                                cout << "\n\n Reward: + 700 pts.";
                                cin.get();
                                system("cls");
                                cout << "\n\n SCORE: 2,800 POINTS";
                                cin.get();
                                system("cls");
                                cout << "\n\n Whom of the following is my favorite member of the X-men?";
                                cout << "\n\n 1. Remy LeBeau (Gambit) 2. James Logan Howlette (Wolverine) 3. Scott Summers (Cyclops)";
                                cin >> xmenguess;
                                system("cls");
                                if (xmenguess == 1) {
                                    cin.get();
                                    cout << "\n\n CORRECT";
                                    cin.get();
                                    system("cls");
                                    cout << "\n\n Reward: + 800 pts.";
                                    cin.get();
                                    system("cls");
                                    cout << "\n\n SCORE: 3,600 POINTS";
                                    cin.get();
                                    system("cls");
                                    cout << "\n\n Which of the following is my favorite drink?";
                                    cout << "\n\n 1. Vodka 2. Gin 3. Bourbon";
                                    cin >> drinkguess;
                                    system("cls");
                                    if (drinkguess == 2) {
                                        cin.get();
                                        cout << "\n\n CORRECT";
                                        cin.get();
                                        system("cls");
                                        cout << "\n\n Reward: + 900 pts.";
                                        cin.get();
                                        system("cls");
                                        cout << "\n\n SCORE: 4,500 POINTS";
                                        cin.get();
                                        system("cls");
                                        cout << "\n\n FINAL QUESTION";
                                        cin.get();
                                        system("cls");
                                        cout << "\n\n Whom of the Transformers robots do I like the best?";
                                        cout << "\n\n 1. Soundwave 2. Optimus Prime 3. Megatron";
                                        cin >> transformerguess;
                                        system("cls");
                                        if (transformerguess == 1) {
                                            cin.get();
                                            cout << "\n\n CORRECT";
                                            cin.get();
                                            system("cls");
                                            cout << "\n\n Reward: + 1,000 pts.";
                                            cin.get();
                                            system("cls");
                                            cout << "\n\n FINAL SCORE: 5,500 POINTS";
                                            cin.get();
                                            system("cls");
                                            cout << "\n\n CONGRATULATIONS! You Have Won the Game.";
                                            cin.get();
                                            system("cls");
                                        }
                                        else {
                                            cin.get();
                                            cout << "\n\n INCORRECT";
                                            cin.get();
                                            system("cls");
                                            cout << "\n\n Penalty: -4,500 pts.";
                                            cin.get();
                                            system("cls");
                                            cout << "\n\n SCORE: 0 POINTS";
                                            cin.get();
                                            system("cls");
                                            cout << "\n\n GAME OVER";

                                        }

                                    }
                                    else {
                                        cin.get();
                                        cout << "\n\n INCORRECT";
                                        cin.get();
                                        system("cls");
                                        cout << "\n\n Penalty: -3,600 pts.";
                                        cin.get();
                                        system("cls");
                                        cout << "\n\n SCORE: 0 POINTS";
                                        cin.get();
                                        system("cls");
                                        cout << "\n\n GAME OVER";
                                    }
                                    
                                }
                                else {
                                    cin.get();
                                    cout << "\n\n INCORRECT";
                                    cin.get();
                                    system("cls");
                                    cout << "\n\n Penalty: -2,800 pts.";
                                    cin.get();
                                    system("cls");
                                    cout << "\n\n SCORE: 0 POINTS";
                                    cin.get();
                                    system("cls");
                                    cout << "\n\n GAME OVER";

                                }

                            }
                            else {
                                cin.get();
                                cout << "\n\n INCORRECT";
                                cin.get();
                                system("cls");
                                cout << "\n\n Penalty: -2,100 pts.";
                                cin.get();
                                system("cls");
                                cout << "\n\n SCORE: 0 POINTS";
                                cin.get();
                                system("cls");
                                cout << "\n\n GAME OVER";

                            }
                        }
                        else {
                            cin.get();
                            cout << "\n\n INCORRECT";
                            cin.get();
                            system("cls");
                            cout << "\n\n Penalty: -1,500 pts.";
                            cin.get();
                            system("cls");
                            cout << "\n\n SCORE: 0 POINTS";
                            cin.get();
                            system("cls");
                            cout << "\n\n GAME OVER";
                        }
                    }
                    else {
                        cin.get();
                        cout << "\n\n INCORRECT";
                        cin.get();
                        system("cls");
                        cout << "\n\n Penalty: -1,000 pts.";
                        cin.get();
                        system("cls");
                        cout << "\n\n SCORE: 0 POINTS";
                        cin.get();
                        system("cls");
                        cout << "\n\n GAME OVER";
                    }
                }
                else {
                    cin.get();
                    cout << "\n\n INCORRECT";
                    cin.get();
                    system("cls");
                    cout << "\n\n Penalty: -600 pts.";
                    cin.get();
                    system("cls");
                    cout << "\n\n SCORE: 0 POINTS";
                    cin.get();
                    system("cls");
                    cout << "\n\n GAME OVER";

                }
            }
            else {
                cin.get();
                cout << "\n\n INCORRECT";
                cin.get();
                system("cls");
                cout << "\n\n Penalty: -300 pts.";
                cin.get();
                system("cls");
                cout << "\n\n SCORE: 0 POINTS";
                cin.get();
                system("cls");
                cout << "\n\n GAME OVER";
            }
        }
        else {
            cin.get();
            cout << "\n\n INCORRECT";
            cin.get();
            system("cls");
            cout << "\n\n Penalty: -100 pts.";
            cin.get();
            system("cls");
            cout << "\n\n SCORE: 0 POINTS";
            cin.get();
            system("cls");
            cout << "\n\n GAME OVER";
        }
    }
    
    else {
        cin.get();
        cout << "\n\n INCORRECT";
        cin.get();
        system("cls");
        cout << " \n\n The first question ? ...Really ?";
        cin.get();
        system("cls");
        cout << "\n\n SCORE: 0 POINTS";
        cin.get();
        system("cls");
        cout << "\n\n GAME OVER";

       
    }




    
    system("pause>0"); //omits garbage text from bottom of console
    


    return 0;

}
