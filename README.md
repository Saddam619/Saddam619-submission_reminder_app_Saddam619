Reminder App Creation 

This is an explanation of how my reminder app  is all created. The script starts by asking for your name. When you enter your name, it creates a special folder called submission_reminder_<your_name>. This folder will hold all the important files and scripts we need.

Inside this main folder, the script makes some smaller folders. These smaller folders are named app, modules, assets, and config. Each folder has a job. The app folder has the main script that sends reminders, modules has extra helper functions, assets is for files like student submissions, and config keeps important settings.

Next, the script creates some important files. One file, called reminder.sh, checks who has turned in their work and sends reminders. Another file, functions.sh, helps read the list of students and see who hasn’t submitted their work yet. It also makes a file called submissions.txt that lists students, their assignments, and whether they have turned them in. There’s a config.env file that says what the assignment is and how many days are left to submit it. Finally, it creates a file called startup.sh that starts the reminder program.

After everything is set up, the script makes sure all the scripts can be run. At the end, it tells you that the setup is done and explains how to start the reminder program. This whole process helps keep track of assignments and reminds students when they are due!
