# SettlersGame_Server
Final server for the Settlers

{\rtf1\ansi\ansicpg1252\deff0{\fonttbl{\f0\fnil\fcharset0 Calibri;}}
{\*\generator Msftedit 5.41.21.2510;}\viewkind4\uc1\pard\sa200\sl276\slmult1\lang6\f0\fs22 In case everything goes tits-up, this is the Read-Me in order to install this project into your working IDE.\par
\par
Repositories to be extracted from \b GitHub\b0 :\par
The repositories needed for the project to work are "Settler-s_v42" and "NewServerClient".\par
\par
If you are using \b Intelli-J IDEA\b0 :\par
1. Open Intelli-J IDEA\par
2. Go to (In the top-left corner) File -> Open -> Find the location to where you downloaded this project, and open it.\par
3. Before running anything, we need to import the used libraries and set up the projects SDK. Do this by firstly going to: File -> Project Structure -> Find the "Libraries" tab -> Press the "+" button, find the location of the Kryonet Jar, which is located inside the project folder "Settlers/jars/kryonet-2.21-all.jar"\par
4. Now set up the Project SDK by still being inside the Project Structure window -> Go to the "Project" tab -> Under the title "Project SDK" assign the right JDK, which is "1.8".\par
5. Press OK.\par
6. DONE!\par
After this, it is possible to run both the server and the client version.\par
\par
If you are using \b Eclipse\b0 :\par
\par
\b For running the server and the client:\par
\b0 1. Firstly, you need to run the server, via the ServerProgramClass. Once you get the command in your IDE, you can then run the client version:\par
"Creating the server!\par
00:00  INFO: [kryonet] Server opened.\par
Server is operational!\par
2. The client versions is run from the main, and as we did in step 1, after the server is initialized and operating, we can create the players by running the main. It might take some time in order for the game client to appear.\par
For running the \b executables\b0 :\par
1. Run the executable.\par
\par
When playing the \b game\b0 :\par
\b Rules:\par
\b0 Each player is given a number of resources corresponding to the values below. These resources are what is used in order to buy and progress in the game. The resources are, wood, wheat, sheep stone and brick.\par
The two first buildings you create can be placed anywhere on the map as you desire. However, afterwards, the buildings will have to be connected to roads, leading to other buildings.\par
To gain more victory points, you must build new roads and settlements and upgrade your settlements to cities. Each city is worth 2 victory points. To build or upgrade, you need to acquire resources.\par
Every player is assigned a victory point for placing a building, once the wincondition of 10 is given, the player with that amount of points has won the game.\par
Each turn, the dies are rolled in order to determine which terrain hexes produce resources. Each terrain hex is marked with a round number token. If, for example, a "10" is rolled, all terrain hexes with a "10" number token produce resources.\par
You will only be able to collect resources if your settlements are bordering these terrain hexes.\par
}
 
