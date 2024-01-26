# Initial Commit

Until the initial commit I did:

	git init 
	git add README.md
	git commit -m "Initial Commit" -m "Just Add README.md file"
	git branch -M main # Change master to main
	git remote add origin git@git...# you know
	git push -u oringin main

# Second Commit

Now, I used:
	
	git checkout -b my-new-branch
	# Changes in README.md
	git add README.md # git needs to track README.md
	git commit -m "msg1" -m "msg2"
	git push -u origin my-new-branch

Afterwads, I changed README.md content but I did not deleted my-new-branch

	git checkout main # It did not work because I had to commit changes before checkout 
	git checkout -f main # It worked because flag -f forces it.

# Third Commit

Now I will delete Branches I have already merged:
	
	git branch -d my-new-branch # If changes, you can force it using -f
	git branch -d second-branch 
	
# END

How many times can I commit in a single branch without making any commit? 

	this is no end...
