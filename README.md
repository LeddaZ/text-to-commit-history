# Text To Commit History
> Write a text on your Github profile, with your commits history.

"Text To Commit History" is a tool I wrote to decorate your Github account's commit history calendar by (blatantly) abusing git's ability to accept commits _in the past_.

## Example Result
Converting "Hello" text to some commits will create something like this on Github profile:
![Hello](https://user-images.githubusercontent.com/7780269/57866862-4d6ac500-7815-11e9-9527-9784567e583f.png)

## Usage
1. Create a new Github repository to store your handiwork.
2. Install requirements:
```
	pip3 install -r requirements.txt
```
3. Run `text_to_commit_history.py` (with Python 3) and follow the prompts for username, your text, offset, and repository name.
4. Run the generated `text_to_commit_history.sh` from your home directory (or any non-git tracked dir) and watch it go to work.
5. Wait... Seriously, you'll probably need to wait a day or two to show in your commit graph.

## Removal
Fortunately if you regret it then, removing it is fairly easy: delete the repository you've created (and wait).
