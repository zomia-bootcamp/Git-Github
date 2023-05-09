# Git-Github

## Overview

In continuation of our previous topic on Git Basics, we will now explore how to use GitHub for managing our project.

### Linking with GitHub

To ensure our code is backed up online and to benefit from its graphical interface and collaboration features, we will create a Github repository. This will allow us to seamlessly integrate our local repository with GitHub.

### Creating & Pushing
## Exercises

Now it's your turn to create your own Github repository:

1. Name the repository as "game-of-gits-<your name>".
2. Set the repository visibility to Public.
3. Do not select the option to initialize with a new README.

Your "Create New Repository" screen will appear as follows:
  
  
![createRepo](https://user-images.githubusercontent.com/132401198/237055369-2ea45ca8-8875-48a2-a031-978cf1422c4e.png)

  
To push your master branch to the remote repository, use the following command: `git push origin main`.

After finishing Ned Stark's story, you can start writing the beginning of another character's story. For example:

```text
  Joffrey Baratheon was the one to do Ned in, 
  but his story was only about to begin, and let me assure you 
  he will DEFINITELY NOT DIE!
```

Remember to push the changes you made. To push the changes in your main branch, use the command `git push origin main`.

To push your dream-story branch, you can use a similar command. First, make sure you are on the dream-story branch, then use `git push origin dream-story` to push the branch to the remote repository.

### Adding to Your Story

Now, I will show you how to fork and clone one of your repositories. Then, I will make an addition to the story and create a pull request to propose the changes.

### Adding to Other's Stories
## Group Activity

Follow the example above and take turns adding to each other's stories. Remember to accept each other's pull requests. Once each of you has had a turn, you can stop.
  
## Pulling: Updating Your Local

To update your local Git repository with the latest code from Git Enterprise, you can use the command `git pull origin main`. This will fetch and merge the changes from the master branch of the original repository.

### Editing on Github

On Gith, you might have noticed a pencil button at the top of a page. This button allows you to edit the text and make changes directly on Github.
  
 ![gitHub-edit](https://user-images.githubusercontent.com/132401198/237059728-c407aa5c-f182-4bcd-9f81-0fc51d6666ca.png)
  
**Don't do that!** It's important to never edit files directly on Git Enterprise, even for small changes. Always make changes on your local computer and then push them to Git Enterprise.

The reason for this is that if you edit files in the cloud, your local repository and Git Enterprise repository can get out of sync, which goes against the usual way of working.


 
