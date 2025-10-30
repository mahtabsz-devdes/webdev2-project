<!-- READ THIS FIRST -->

    ********** Get Started with GitHub: **********

    !!! IMPORTANT: Once your setup, each time you come here to play around you MUST pull the latest changes from GitHub. Your classmates will slowly make changes that you'll want to pull to your main. 
    
    It's easy, switch to the main branch and type: 
    
        git pull origin main 


    HOW TO USE GitHub:

    1. Clone my GitHub Repo (if you're here you already did this, but here's how you clone a repo in terminal)
        
       my repo: git clone https://github.com/miket604/fwdp-playground.git

       default structure: git clone https://github.com/USERNAME/REPOSITORY.git

    
    2. Create a BRANCH using GitHub & Name it after yourself (use your first name for simplicity). 
    
        git checkout -b your-branch-name

        Tip: this creates a new branch and switches to it automatically. ALL changes to the code should be made on YOUR branch.

    3. Push the New Branch to Github (Optional... but Recommended for backup & collaboration)

        git push -u origin your-branch-name

        Tip: -u sets the upstream branch so that future push & pull commands for your branch will automatically interact with the 'remote' branch you just created.

    4. Check which Git Branch you're on (anytime in terminal)

        git branch

        Tip: If you notice you're on the wrong branch see the next step.

    5. Switching Branches (two methods, same result)

        git checkout branch-name

        git switch branch-name
    
    6. Changes you make in YOUR branch will not affect the MAIN branch. Switch back & forth between branches to see. Again, always make changes in YOUR branch.

    7. PUSH your changes to GitHub for review & merging (i'll review them before merging), these are the steps:

        git add .
        git commit -m "explain what you did"
        git push -u origin your-branch-name

        that's it.

    8. At this point, I'll need to review & merge the changes. DM me and let me know. Once I confirm the changes, you should get a message on GitHub, or I'll let you know. At that point open your folder in VScode, open terminal, and pull the changes to your main branch.

        git pull origin main

        Tip: make sure your on the main branch when you do this.
    
    Now, you should see your updated changes inside the main branch files.

  

 ********** Get Started HTML & CSS (Practicing Collaborative Code) **********
     
    1. Create a DIV with your name as the class (see mine below)

    2. Use your NAME in all classes... avoid applying styles

    3. You won't see anyone elses code until I merge the files.

    4. This is just for practicing GitHub.
  
    5. It doesn't matter if you make a mistake, but please mention it so we can get you on track.

    6. Might make more sense to give everyone their own HTML/CSS files but for now let's just practice Git.
