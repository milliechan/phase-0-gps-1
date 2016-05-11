# phase-0-gps-1


  568  git clone https://github.com/milliechan/phase-0-gps-1.git
  * Pulls repo from URL that was given onto local machine 
  569  ls
  * List files in current directory 
  570  cd phase-0-gps-1/
  * Changes directory to listed folder 
  571  touch awesome_page.md
  * Creates new file with given name 
  572  git status
  * Gives summary of current state of repository and any modified files 
  573  git add awesome_page.md
  * Adds file to staging for commit 
  574  git commit -m "Initial Commit"
  * Takes all staged files and creates a save point that is ready to be pushed to GitHub 
  575  git push origin master
  * Uploads files back onto repo to specified branch  
  576  git branch
  * Lists current branches and also shows which one you are working in 
  577  git checkout -b add-command-log
  * Creates new feature branch and also changes directory to that branch 
  579  git checkout --help
  * Launches help function for any git command 
  580  subl README.md 
  * Opens specified file in the text editor Sublime