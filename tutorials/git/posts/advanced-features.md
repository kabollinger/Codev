You should check your status anytime you’re confused. Git will print additional information depending on what’s currently going on in order to help you out.

**Create a new branch name:**

```
git branch
```

You can think of this like creating a local `checkpoint` (technically called a reference) and giving it a name. It’s similar to doing `File > Save as...` in a text editor; the new branch that gets created is a reference to the current state of your repo. The branch name can then be used in various other commands as you’ll soon see.

Similar to branching, more commonly you will save each checkpoint as you go along in the form of commits (see git commit below soon). 

Commits are a particular type of checkpoint called a revision. The name will be a random-looking hash of numbers and letters such as e093542. This hash can then be used in various other commands just like branch names.

✨ That’s really the core function of git: To save checkpoints (revisions) and share them with other people. Everything revolves around this   concept.

If you’ve ever created a checkpoint to something, you’ll be able to get back to it later as long as your `.git` folder is intact. It’s magical. See git reflog if you’re interested in learning more. 

Branching is a huge and complex topic. I’ll write more about it soon; for now you can read more here if you want to. 

**Check out a particular branch:**

```
git checkout
```

You can think of this like “resuming” from an existing checkpoint. All your files will be reset to whatever state they were in on that particular branch. 

⚠️ Keep in mind that any changes in your working directory will be kept around. See git stash if you’re interested in a simple way to avoid headaches. 