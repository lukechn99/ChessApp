Object oriented approach to chess

Final goal is to develop Android app for chess available in the Google Play Store. Its functionalities will include:
 - Play across multiple devices using the Android Bluetooth APIs
 - Allow multiple modes of play including four interconnected devices for bughouse chess
 - Fill in any other functionality that most chess apps don't currently deliver
 - A computer
 - Benefits provided: no need to hand device back and forth, more modes of play, no WiFi connection needed (Chess.com)
 
Current development status:
 - The piece classes have been created
 - The main class which creates the board and facilitates turns has been created
 - The code right now can be played like a regular board of chess on command line, but legal moves have not been programmed in

Next steps:
 - Create GUI through Android Studio and XML
 - Complete boolean "move" method for each piece to determine the legality of the attempted move
 - Find APIs that fill in for other normal chess app functionalities (opening database, analytics, ratings)
