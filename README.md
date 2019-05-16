# Text2Commit
> Write a text on your Github profile, with your commits history.

`text2commit.py` is a tool I wrote to decorate your Github account's commit history calendar by (blatantly) abusing git's ability to accept commits _in the past_.

## Example Result
Converting "Hello" text to some commits will create something like this on Github profile:
![Hello](https://user-images.githubusercontent.com/7780269/57866862-4d6ac500-7815-11e9-9527-9784567e583f.png)

## Usage
1. Create a new Github repo to store your handiwork.
2. Install requirements:
```
	pip3 install -r requirements.txt
```
3. Run `text2commit.py` (with Python 3) and follow the prompts for username, your text, offset, and repo name.
4. Run the generated `text2commit.sh` from your home directory (or any non-git tracked dir) and watch it go to work.
5. Wait... Seriously, you'll probably need to wait a day or two for the text2commit to show in your commit graph.

## Removal:
Fortunately if you regret your text2commit in the morning, removing it is fairly easy: delete the repo you created for your text2commit (and wait).
