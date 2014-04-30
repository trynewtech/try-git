My Movie Script
===============

Congratulations! You made it!

Let's now use git to write a movie script.


## Challenge #6: Experiment

Now that we're on a fresh, new branch, let's create an experiment.

Create a new branch named movie-script-experiment

[Solution][solution-06]


## Challenge #7: Commit an experiment

You should now be on the `movie-script-experiment` branch. It's a safe place to commit
some crazy code without affecting the rest of your project.

For this experiment, let's create another file, named `movie-script.txt` and fill it with [Lorum Ipsum][ipsum].

1. Create `movie-script.txt` and fill it with content

2. Commit it


## Challenge #8: Give it a name

Now that you have a movie script ready to go, let's give it a name.

1. Open `movie-script.txt`

2. Put **LORUM-ZILLA** at the top of the file

3. Commit


## Challenge #9: Scrap it

But wait! You have an even better idea for a movie!
Let's leave this branch alone and go back to `movie-script`.

[Solution][solution-09]


## Challenge #10: Sanity check

Take a look. Even though your file is gone from the working directory,
the work still exists. Type the following to see your branch.

```bash
$ git branch
```

Notice that the branch you were just working on still exists. You can return to it at any time.


## Challenge #11: A better idea

Let's see if you can put it all together. Remember, to ask a mentor for help if
you need some assistance.

1. Create and switch to a new branch named `dog-movie`

2. Create a file called `dog-movie.txt`

3. Add "The lazy dog took a nap." to the story.

4. Commit your work

[Solution][solution-11]


## Challenge #12: Elaborate on your idea

1. Create a new branch named `dog-movie-experiment`

2. Rewrite `dog-movie.txt` to **The quick brown fox jumps over the lazy dog**

3. Commit

[Solution][solution-12]


## Challenge #13: Keep your experiment

Wow! That story is genius. It's going to be everywhere!

Let's add these change back down to `dog-movie`.
To do this, we're going to merge.

Read more about [merging here][merge].

When you're ready, try merging this awesome story back down to `dog-movie`

[Solution][solution-13]


## Challenge #14: See your work history

Now that you've made it this far, it can be useful to see the
history of a branch. Use [git log][log] to do that.

Take a moment to run `git log` with the various options to see your work.

Note the commit hashes. You can use `git checkout` to put the state of the
working directory back to a particular commit.


## What's next?

Now that you have a grasp on the absolute basics of git, let's build off of
what you know by collaborating on a repository with your peers.

#### Navigate to [Try Writing a Story][story].

We'll be around to help you with particular tasks. There's nothing better
than getting some hands-on experience.

Try to help or get help from the people next to you. If you more help, raise your hand.

We haven't covered merge conflicts or rebasing yet. After you get familiar
with [Try Writing a Story][story], we can help you explore these concepts.

Thanks again for participating!


[ipsum]: http://en.wikipedia.org/wiki/Lorem_ipsum
[merge]: http://git-scm.com/docs/git-merge
[log]: http://git-scm.com/docs/git-log
[solution-06]: https://github.com/trynewtech/try-git/wiki/Challenge-%236
[solution-09]: https://github.com/trynewtech/try-git/wiki/Challenge-%239
[solution-11]: https://github.com/trynewtech/try-git/wiki/Challenge-%2311
[solution-12]: https://github.com/trynewtech/try-git/wiki/Challenge-%2312
[solution-13]: https://github.com/trynewtech/try-git/wiki/Challenge-%2313
[story]: https://github.com/trynewtech/try-writing-a-story
