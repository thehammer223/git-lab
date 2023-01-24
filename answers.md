Answer 1: git version 2.17.1
Answer 2: user.name=Joshua Moffett
          user.email=jm340221@ohio.edu
Answer 3: The terminal opens up the Git Manual.
Answer 4: On branch master
	
	  No commits yet

	  Untracked files:
		README.md
		answers.md
Answer 5: On branch master
	
	  No commits yet
	
	  Changes to be committed:
		new file:   README.md

	  Untracked files:
		answers.md
Answer 6: On branch master
	
	  No commits yet
	
	  Changes to be committed:
		new file:   README.md
		new file:   answers.md

	  Untracked files:
		answers.md
Answer 7: On branch master
	
	  nothing to commit, working tree clean
Answer 8: commit 038f267b9389a76997971c178e88e54e93973e (HEAD ->master)
	  Author Joshua Moffett <jm340221@ohio.edu>
	  Date  Tue Jan 24 10:35:55 2023 -0500
		Initial commit
Answer 9: On branch main
	  Your branch is up to date with 'origin/main'.

	  Changes not staged for commit:
	     (use "git add <file>..." to update what will be committed)
	     (use "git checkout -- <file>..." to discard changes in working directory)

		   modified:   answers.md

	   no changes added to commit (use "git add" and/or "git commit -a")
Answer 10: No, it did not update/
Answer 11: ! [rejected]        main -> main (fetch first)
	   error: failed to push some refs to 'https://github.com/thehammer223/git-lab.git'
	   hint: Updates were rejected because the remote contains work that you do
	   hint: not have locally. This is usually caused by another repository pushing
	   hint: to the same ref. You may want to first integrate the remote changes
	   hint: (e.g., 'git pull ...') before pushing again.
	   hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Answer 12: Yes, the changes were made.
Answer 13: .  ..  git-lab-2 
Answer 14:
/*
 *        File: git-lab-program.cc
 *      Author: Joshua Moffett
 *        Date: January 24, 2023
 * Description: git-lab-program.cc
 */

#include <iostream>
#include <iomanip>
#include <cstdlib>
using namespace std;


int main(int argc, char const *argv[]) {

    cout << "Hello Git!!" << endl;
    return 0;
}// main
	  jmoffett@odd35:~$ cd 2400
	  jmoffett@odd35:~/2400$ g++ -Wall git-lab-program.cc
	  jmoffett@odd35:~/2400$ ./a.out
	  Hello Git!!
