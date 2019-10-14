# BOWLING KATA [CLEAN SLATE]

This repository is a dead simple clean slate to start the bowling kata using pytest. One of the famous kata suggested by Uncle Bob.
http://butunclebob.com/ArticleS.UncleBob.TheProgrammingDojo
I have set this up for educationnal purpose in order to help peers getting their feet wet with the TDD discipline. This is a clean slate, so, yeah there is almost nothing there.

## Goal

Train your mind to respect fully the RED-GREEN-REFACTOR cycle.

**First Goal**: Get RED. Do not write a single line of code in `bowling.py`. Code your test instead. Once you have a test, run it to ensure it really fails. Hurray you enter the red state.

**Secong Goal**: Get GREEN. Your test does not pass. Write the most straightforward code (can be dirty) that makes all your tests pass. Run your tests continuously in paralell. Failing messages points you into what you have to do next. Your test pass. Hurray, you enter the green state

**Third Goal** : Get GOLDEN. This is called the refactor step, but GOLDEN is a nice name for this step, as what you truly want is a bright and shiny codebase. Indeed, having your test passing does not mean having clean code. But now that you are in the green state, you can afford messing up with your code to clean it up. Brutal refactoring is OK, because the tests have your back. Continue to launch your tests in paralell to ensure you do not break anything doing so. This is also the moment where you can refactor your tests themselves.

Now, commit your progression to your VCS. Continue the cycle and get RED again.

## Rules of the bowling game

There or elsewhere: https://www.playerssports.net/page/bowling-rules

## Installs

Install pytest in your local virtualenv using the method of your choice.
Run `pytest` to run your tests.
Don't forget to name your test functions starting with `test`, such as `test_this_thing()` so that pytest know that it's a test function. Of course you can avoid pytest for doing this kata, but pytest is hugely popular and without much boilerplate (simple assert statements do work).


