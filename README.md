# Setting up your readme
This is a default repository with instructions on how to format your repository.

It is very important to create a good and accurate readme. It will people understand what is your code about, and help them get started running it.

Readme files are written in MarkDown text. You edit your code by inserting characters to represent different text styles. See the [MarkDown Cheatlist](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for reference. Use [this link](https://www.makeareadme.com/) to see how it works. This link can also help you edit your readme file more friendly.

Our readmes will follow the [official Github recomendations](https://guides.github.com/features/wikis/), so it must contain:

- **Project name:** Your project’s name is the first thing people will see upon scrolling down to your readme and is included upon the creation of your readme file.

- **Description:** A description of your project follows. A good description is clear, short, and to the point. Describe the importance of your project, and what it does.

- **Installation:** Installation is the next section in an effective README. Tell other users how to install your project locally. Optionally, include a gif to make the process even more clear for other people. Here is where you include all the dependencies and everything required so people can get the code running.

- **Usage:** The next section is usage, in which you instruct other people on how to use your project after they’ve installed it. This would also be a good place to include screenshots of your project in action.

- **Contributing:** We will have a small text just letting people know they can fork and contribute to it if they want to.

- **Credits:** Currently, this section will be omitted. At this beginning, the credits will be associated with the people who contributed to the repo. In the future, we will have a specific section for credits and a piece of latex code for citation.

- **License:** We will usualy use [MIT](https://opensource.org/licenses/MIT). 

Below, you will find a template that we will use as a readme.

---
# Project Name

Description of the project.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update the tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

---

Alright, you got everything you need to get your readme done!

Remember, you can use images and youtube videos. Be creative! But be simple and accurate. 


### Push your project to Github
Now that you have your repository and readme done, you have to push your project content to the repository. 
First, make sure you have git installed. To install, run the following command on your terminal:

```bash
conda install -c anaconda git
```

### If the repository already exists:
If you are editing a new project from a existing repository, follow this steps.
First, you will have to clone your repository to your computer. Open a terminal, go to the path you would like to clone your repository and type:

```bash
git clone <link to your repository>
```
A new folder will be created on your computer with the same name of the repository.
Copy your project files to this repository and push it. 

But wait, before you push it, you might want to see ['what is a gitignore file' and 'what it is for'](https://www.pluralsight.com/guides/how-to-use-gitignore-file). It tells git what files and directories to ignore when pushing.

To push it, type these commands to your terminal:


```bash
git add -A
git commit -m "first commit"
git push
```

You will have to enter your git login and password.

Great. You have done your first commit. Now, all your project files are available on Github.



### If the repository does not exist yet

If the repository you want to push to does not exist yet. Follow [this steps](https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line).


Now that you have your new repository settle up, you will have to get used to the git commands such as pull, add, commit, push, etc... there are many of then, but just a few will serve you in this beginning. You can learn more about Github Basics [here](https://guides.github.com/activities/hello-world/) and in many other online resources. There are plenty of them.


bye,

Sergio.
