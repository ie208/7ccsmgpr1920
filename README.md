# 7CCSMGPR 2019-2020

*Note* that all students *must* set `git` up to use your full name and *King's
email address* e.g.:

```
$ git config --global user.name "John Smith"
$ git config --global user.email "john.smith@kcl.ac.uk"
```

How to form a group:

  1. Designate a group coordinator.

  2. Have the coordinator fork this repository. In that fork the coordinator
     should:
       1. Create a directory with the group name (in lower case, with
          underscores instead of spaces; i.e. the name "Our Group" would lead
          to a directory called `our_group`).

       2. Inside the group directory, create a file called `members.txt`. The
          coordinator should then go to the `students.txt` file, find the line
          containing their name, and then copy that whole line *unchanged*
          (including tabs, etc.) into `members.txt`.

       3. Inside the group directory, create a file called `coordinator.txt`
          which contains the coordinator's line from `students.txt` (copy the
          whole line *unchanged* as in the previous step).

       4. Inside the group directory, create a file called `repo.txt` which
          has the URL to the *public* githup repository you will be using for
          development during your project.

          [Note: if the repository changes at any point, you must make a pull
          request to update this link.]

       5. Add the files you have created, commit them, and push them to your
          fork.

  3. Once step 2 is complete, each group member must separately carry out the
     following steps:
       1. Fork the coordinator's fork of the repository (i.e. don't fork
          the original repository!).

       2. Open the `students.txt` file, find the line containing your name,
          and then copy that whole line *unchanged* (including tabs, etc.) into
          `members.txt`.

       3. Commit your changed `members.txt` file, push, and make a pull
          requst against the coordinator's fork of the repository.

  4. Once all group members have added themselves in this way to the
     coordinator's repository, the coordinator should run `python3 check.py` and
     ensure that no warnings are given about duplicated or incorect entries. If
     no warnings are printed, make a pull request against the main 7CCSMGPR
     repository. In your message, state the group name clearly.

If you get any of these details wrong, you will be asked to try again.
