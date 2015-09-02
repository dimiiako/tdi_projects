Miniprojects
==========
Hello and welcome to The Data Incubator!

# First Assignment

This first assignment functions as a sanity check, to ensure you
understand the basic flow of completing these miniprojects. Once you've
completed this, you'll be ready to try your hand at the more substantive
miniprojects. (Though you'll probably want to go through some of the
lessons, first!)

1. Open up `assignment1/README.md`. Read the instructions, and then edit
   `assignment1/__init__.py`

   Each module lives in its own directory with a `README.md` (with
   instructions) and an `__init__.py` file (where your solutions go).
   All code used to generate solutions should live in the respective
   module's directory (possibly in a `src` sub-directory).

2. In `assignment1/__init__.py`, you'll see a function `add`, along with
   some decorators up top.  Make that function add the two numbers up.
   *Do not modify the decorators*.

3. Each question has some a decorator specifying the return type, along
   with some test cases. Make sure that your function works correctly on
   the test cases and always returns the right type. You can run
   `validate.py` to do this for you.

4. Go ahead and implement the `add` function, and then run `validate.py`
   to make sure you return the right output format.

5. Finally, `git add` and `git commit` your solution, then run
   `git push grader master` to submit your answer. You should get a
   bunch of output from the grader, along with your grade. You should
   also login to your dashboard - check the gradebook linked there to
   confirm that your grade is being recorded correctly.

That's it! Good luck with the course!

# Useful Notes

- If you're having problems with Python imports, you can run 
  `python fellow.py` to test that you get no `ImportError`s
- Make sure to run `validate.py` 
- There's an `environment.yml`, which specifies the packages that the
  grader installs before running your code. If you need to add
  packages, make sure to edit the file. You can update it
  automatically via:

  ```bash
  $ conda env export --name root > environment.yml
  ```

  Just be careful --- if you install lots of packages, grading might
  take longer!
