# LS95 Notes

Notes for [Launch School’s](https://launchschool.com) LS95 course.

## Start Here

### Welcome
* [From Bootcamp to Mastery: A Five-Year Journey](https://medium.com/launch-school/from-bootcamp-to-mastery-a-five-year-journey-8b1bce8f2cd)

### Code of Conduct
* [Student Code of Conduct](https://launchschool.com/code_of_conduct)

### What is Software Development?
* Focus of Launch School is on **web application development**
* [What is Code](https://www.bloomberg.com/graphics/2015-paul-ford-what-is-code) (Bloomerg article)

### How to launch a career as a Software Developer
* Web application developer
  * Back-end Developer
  * Front-end Developer
* Learning the topics in Launch School’s program will even assist pursuing other development roles ourside of web development
  *  For example: it’s impossible to become a great mobile developer without knowing everything taught in Launch School’s curriculum

### Our Learning Goals
* Focus on First Principles
* Proficiency vs Awareness
* Understanding Problems, not Solutions
* Circular Learning
* The Slow Path

### Mastery Based Learning
* Launch School’s core attribute is their 100% committment to Master Based Learning
  * [Mastery Based Learning](https://launchschool.com/mastery)
* Master Based Learning is the most significant influence on the school’s pedagogy
  * [Pedagogy](https://launchschool.com/pedagogy)

### Read: Mastery
* [Mastery by George Leonard](https://www.amazon.com/Mastery-Keys-Success-Long-Term-Fulfillment/dp/0452267560) (Amazon)
  * [Notes](mastery/mastery_notes.md)

### How Not To Learn
* [Learning anti-patterns](https://www.launchschool.com/blog/webinar-learning-to-code-anti-patterns)
* [Learning How to Learn](https://www.coursera.org/learn/learning-how-to-learn) (Coursera)
  * [Notes](learning_how_to_learn/learning_how_to_learn_notes.md)

### Join Our Community
* [General Forums](https://launchschool.com/forum)
* [Chat Room](https://launchschool.com/chat)

## Getting Ready to Program

### Book: Introduction to the Command Line
* [Introduction to the Command Line](https://launchschool.com/books/command_line)
* `head` print beginging of file
* `tail` print end of file
* `more` one page at a time, forward navigation only
* `less` one page at a time, forward and backward navigation
* `man` uses less, allowing forward and backward navigation
* `ls` `-h` option when used with `-l` will add unit suffixes
* `which` locate an executable in the user’s path
* `source ~/.zshrc`
* `COMMAND="echo"` variable can be used as command
* `export PATH="/path/to/my/executables-directory:$PATH"`
* **Read-Eval-Print-Loop (REPL)** are interactive scripting consoles

### Set Your Editor Indentation
* Ruby developers are often adamant about spacing: 2 spaces for indentation
* JavaScript programmers tend to be a little more flexible but most use 2 or 4 spaces
* Recommend two spaces for indentation in all Launch School work, regardless of Ruby or JavaScript code

### Book: Git and Github
* [Git and Github](https://launchschool.com/books/git)
* Config files
  * `/etc/gitconfig` system
  * `~/.gitconfig` global
  * `<repo>/.git/config` local
* `git log` commit history
  * `git show` commit history with details
* `git remote add origin <url_to_remote_git_repo>`
* `git push -u origin main`
  * `-u` sets upstream tracking branch
* `git diff origin/main main`
* `git pull --ff-only`
  * `--ff-only` best to sepcify how to reconcile branches
* `git pull` essecntially combines `git fetch` and `git merge`