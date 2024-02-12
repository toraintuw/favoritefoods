# Exercise 1
In this exercise you'll practice using git to clone and edit repositories, as will be required for later exercises.

If you haven't already, configure your name and email address for your GitHub account using the terminal.

	
	# enter your full name (without the dashes)
	git config --global user.name "your-full-name"

	# enter your email address (the one associated with your GitHub account)
	git config --global user.email "your-email-address"


Using the terminal, clone **your repository** to your machine (make sure you're in the desired directory on your terminal).


	# Enter a desired directory
	cd ~/Documents

	# Get the URL by clicking the "Clone or Download" button on GitHub, then clicking the clipboard icon

	# Clone the repository
	git clone https://github.com/info-201b-au21/Week1-Exercises-melaniewalsh.git


1. On your machine, open up this file (`favorite_foods.txt`) in a text editor of your choice.



2. In the `favorite_foods.txt` file, make a list of your favorite foods
```
Favorite Foods
- Mochi ice cream
- Scallops
- Brussel sprouts
```

3. Using your terminal, add and commit the changes you've made to your repository
```
# Add changes from all files in the repository
git add .

# Commit changes making sure to include a descriptive message
git commit -m "Adds fav foods"
```

4. Push changes up to GitHub, and view them in your web browser.

```
# Push changes
git push
```


# Exercise 2
In this exercise you'll practice collaboratively editing files with another person.

1. Add a fellow student as a collobator on this repository (or have them add you on theirs). It should be in Settings -> Collaborators and Teams

2. Take turns modifying the favorite_foods.txt file:
   - getting the latest version of the files from github (`git pull`)
   - push changes to github: (`git add .` `git commit -m "change description"`, `git push`).
  
3. Try making changes at the same time to get a merge conflict and try resolving it.
