testing

# phase-0-gps-1
  693  open https://github.com - open the url to github.com
  694  mkdir "Week2" - created a week2 directory
  695  cd Week2/ - moved to the week2 directory
  696  git clone https://github.com/RGHuynh/phase-0-gps-1.git - cloned phase-0-gps-1 repository from github.com
  697  open . - opened the current directory  
  698  open . - opened the current directory
 699  cd phase-0-gps-1/ - getting to the phase-0-gps-1 directory
 700  touch awesome_page.md - created an awesome_page.md file
 701  ls - checking the list of phase-0-gps-1 directory to make sure awesome_page.md file in in the folder
 702  git add awesome_page.md - it hashing awesome_page.md, adding the hash into an index file, the compressing and storing the file in object directory
 703  git commit -m "added awesome_page.md to project" - taking all the hashes and adding it to the tree graph object and then creates a commit object to references the store object in the tree graph.
 704  git push origin master - to push the origin master branch into the github master repository
 705  git checkout -b add-command-log -created a feature branch call add-command-log
 706  open README.md - opened a README.md file


Git tracks changes by have the user make an git add of the change file. Then behind the scene git will
create a hash or a key of the file string and put it into an index file. Then it will be compressed and stored into the object folder.
Afterward, "git commit" will take the hashes or keys and make a tree graph and then it creates a commit object to reference the store object in the tree graph.

The different stages git goes through from start to finish begins with the "git init", which starts the git directory. Then you'll want copy the master repository to  using the branch method. This will create a total copy of the original directory, allowing the user to make any adjustment to the copy without affecting the master directory. After the changes are made, the user can use "git add <file name>"
to create a hash or key, store it in an index file, then it's compress and stored in a object folder.
"git commit" will then take the hash or key and put it into tree graph, and create a commit object to for the user to reference the store object in the tree graph.
