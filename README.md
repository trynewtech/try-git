Try Git
=======

Welcome! Thanks for coming.


## How to participate

[Install git][git] if you haven't already.

The first wave of challenges will be interacting with this repository.
**Complete the challenges below** in the order they appear.

Don't worry about making a mistake. **All edits will be local**,
so they won't affect anyone else. Remember, git is distributed :wink:

If you get stuck, **raise your hand** and a mentor will be over to help.

Let's begin!


## Challenge #1: Clone, modify, commit

For the first challenge, let's review the basics.

1. Open up the **terminal** and type the following
   ([on Windows?](http://i.imgur.com/qknw9D8.png)):

    ```bash
    $ git clone https://github.com/trynewtech/try-git.git
    ```

2. In the newly cloned repository, open **CHANGE-ME.txt**
   and replace the `.` with a `D`. You'll see.

3. Commit your change

    ```
    Tip: Remember to tell git to include CHANGE-ME.txt in the commit by first adding it to the index.
    ```

    Give up? [Here's the answer][solution-01] with some additional notes.


#### What's with that Index anyway?

When programming, you'll often fix multiple things at once because you've entered flow.
Committing all your work into a single commit can make it difficult to see your intention. Git
recognizes this and allows you to commit changed files individually. The index lets you do
this safely.


## Challenge #2: Finish the alphabet

1. Open **CHANGE-ME.txt** again and complete the alphabet.

2. Commit your change

    [Solution][solution-02]


## Challenge #3: Add some numbers

Let's spice it up a bit and create a new file instead of editing an existing one.

1. Make a new file called **SUPER-SECRET.txt**

2. Add your favorite number

3. Commit your change

   ```bash
   Hint: "git commit -a" won't help you here.
   ```

    [Solution][solution-03]


[git]: http://git-scm.com/downloads
[solution-01]: https://github.com/trynewtech/try-git/wiki/Challenge-%231
[solution-02]: https://github.com/trynewtech/try-git/wiki/Challenge-%232
[solution-03]: https://github.com/trynewtech/try-git/wiki/Challenge-%233
