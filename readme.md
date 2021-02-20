QIDI XüMAX Motherboard Project
Starting

To download this project to your computer:

    Install GIT: https://git-scm.com/downloads
    Go into your main project directory, open commad line and run:
    git clone https://github.com/your_username/your_project.git

Using Git in Altium

    Save: Once you make any changes, save the file or project
    Commit: Right click on the file or project, then Version Control -> Commit. Add a note what changes you have done. This not will be still local until you do not push the changes. See the next step.
    Push: When you would like to upload all the changes to github, right click on the file / project -> Version Control -> Push
    Check: Go to your github to see if everything was uploaded correctly

Using Git from command line (Manually)

    Open cmd: Once you make some updates, go into your project directory, open commad line and run:
    git status #this will show you what changes you have done
    git add [path/file] #this will prepare that specific file for commit, to add all files at once, use add .
    git commit -m "Change description" #this will commit the changes with specific description
    git push origin master # this will copy your changes to Github

Download the latest changes

If you would like to download the latest files from Github, then:

    git pull origin master # this will download the latest files from Github to your local computer