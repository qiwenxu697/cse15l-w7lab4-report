# Week 7 Lab Report 4 - Vim 
## Part 1 - Bugs
Step 4: \
Keys pressed: `ssh <space> qix007@ieng6-201.ucsd.edu <enter>` \
First log into **ieng6** using `ssh <space> qix007@ieng6-201.ucsd.edu`. \
<img width="471" alt="截屏2024-02-24 下午4 08 45" src="https://github.com/qiwenxu697/cse15l-w7lab4-report/assets/147675962/51e3dfed-c4ab-4f80-8ba7-c1f5494f175d">\

Step 5: \
Keys pressed: `git <space> clone <space> <command> v <enter>`\
Then I clone my fork of the repository from my Github account by copying the SSH clone URLs link git@github.com:qiwenxu697/lab7.git from GitHub. \
<img width="479" alt="截屏2024-02-24 下午4 09 26" src="https://github.com/qiwenxu697/cse15l-w7lab4-report/assets/147675962/65fe565d-9a0a-4b23-817f-4b1df22e22b8">\


Step 6: \
Keys pressed: `bash test.sh <enter>`\
I run the test.
Then I clone my fork of the repository from my Github account by copying the SSH clone URLs link git@github.com:qiwenxu697/lab7.git from GitHub. \
<img width="481" alt="截屏2024-02-24 下午4 10 24" src="https://github.com/qiwenxu697/cse15l-w7lab4-report/assets/147675962/f5c7e775-e03d-4212-add8-75b7261a095c">\

Step 7: \
Keys pressed: `vim <space> L<tab> .java <enter>` \
When I type `L` and `<tab>`.`<tab>` autocompletes commands. Since there are a `ListExamples.java` and a `ListExamplesTests.java`. It autocompletes `ListExamples`. I type '.java <enter>' to open vim mode. \
<img width="475" alt="截屏2024-02-24 下午4 12 31" src="https://github.com/qiwenxu697/cse15l-w7lab4-report/assets/147675962/ae18a20b-ba17-41d3-8146-f2cff7eedf53">\

Keys pressed: `j j`...(until I get to the line I need to fix) `e  i  l <delete> 2 <esc> <shift>; w q <enter>` \
I type `j` to move down to the code line that need to fix. I reach the line `index1+=1;`. I type `e` to move the cursor to the end of the first word forward. I change `i` to change to insert mode. `l` to move right. `<delete>` `1` ande type `2`. It change `index1+=1;` to `index2+=1;`. `<esc>` change to normal mode. `<shift>; w q <enter>` saves the file change and quit vim. \
<img width="477" alt="截屏2024-02-24 下午4 14 35" src="https://github.com/qiwenxu697/cse15l-w7lab4-report/assets/147675962/bc4d6d3b-c8a1-4345-bb11-5c9403192857"> \

Step 8: \
Keys pressed: `<up> <enter>` \
`<up>` can go to the previous command I enter, which is `bash test.sh`.\


Step 9: \
Keys pressed: `git <space> add L <tab> <enter>` \
Like the previous step, I use `<tab>` to autocomplete commands. Since I change `ListExamples.java`, `<tab>` autocompletes `ListExamples.java`. The `git add` command adds a change.\
Keys pressed: `git <space> commit <space> -m <space> "fix java file"`\
The `git commit` commits the change. `"fix java file"` is a message.\
Keys pressed: `git <space> push <space> origin <space> main`\
The `git push` command take commit and save it somewhere. `main` is the branch that get save.\
