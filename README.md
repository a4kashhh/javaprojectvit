Campus Course & Records Manager 

MacOS Based Run application


Open Terminal, go to project folder:
cd ~/Projects/CCRM_complete


Make compile script executable and run it:
chmod +x compile.sh
./compile.sh



Run the program:

java -cp out edu.ccrm.cli.Main



Structure
src/edu/ccrm/... Java source files

sample-data/ contains students.csv and courses.csv

.vscode/ contains launch/tasks for one click Run in VS Code

compile.sh helper script to compile all sources
