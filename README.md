# Hidden Markov Model Group Project
### If you have any issues or questions about Git or GitHub, ask Ellieanna - feel free to text or email, I'm always happy to help :)



## Getting Started

1. You need to clone the repository
   - open your command line & navigate to where you want to keep the project
   - ``` git clone https://github.com/ellieannar/hiddenMarkovModelGroupProject.git ```
   - ``` cd hiddenMarkovModelGroupProject ```

2. You need to create your own branch - don't work on 'main'. Your branch will keep the code clean and make sure we don't experience merge conflits
   - ``` git branch creative_branch_name ```
   - ``` git checkout creative_branch_name ```
   - Now you're in your own branch! We can't see what changes you make to your code until you commit & push :)
  
3. After coding for a while, you need to commit your changes. This is basically how you save it, think of this as versions or checkpoints of what you're working on. You can do all your coding at once and have a single commit, or make several commits throughout whatever you're working on 
   - ``` git commit -a -m "short description of what you've changed" ```
   - ``` git push ``` - This makes sure it's stored in github where we can see it

 4. When you're ready for the code to join back into the main branch for everyone to use, you need to make a pull request
    - In GitHub, navigate to your branch and click ``` Create Pull Request ```
    - Make a simple description of what all your code changes did
    - Ellieanna will review it and then request changes or merge it into the main branch


## Working on the project later (after other people have made changes)

  1. You need to switch back to the main branch
     - ``` git checkout main ``` (it could be origin or master rather than main, I'll update this when I know)
  3. You need to catch up to what is happening on the main branch
     - ``` git pull ```
   4. To start working on something new after doing this, do the following to create a new branch off of this updated main:
      - ``` git branch creative_branch_name ```
      - ``` git checkout creative_branch_name ```

## Running the Project
   1. Compile the program
      - ``` g++ -o hiddenMarkovModelGroupProject demo.cpp models.cpp ``` (in the terminal)
   2. Run the executable
      - ``` ./hiddenMarkovModelGroupProject ``` (in the terminal)
