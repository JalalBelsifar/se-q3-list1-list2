<img height="120px" src="img/TwoLists.jpg" />

# List1 and List2
For this assignment, you'll be coding some list manipulation functions within the `list1.py` and `list2.py` files.

There is some light dependency on knowing how
[functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)
work in python in terms of argument passing and return values, but you should
be able to figure it out as you go.

## Instructions
Complete all of the functions in `list1.py` and `list2.py` based on your knowledge of Python lists, indexing, slicing, and methods. Make sure all the included tests are passing before submitting your work.

Run the programs from the command line like this:
```console
$ python list1.py
```
 
Here is a sample output. You can see that for the `match_ends()` function, some tests are passing, others are failing.
```
$ python list1.py
match_ends
 OK  got: 3     expected: 3
  X  got: None     expected: 2
 OK  got: 1     expected: 1

front_x
  X  got: None     expected: ['xaa', 'xzz', 'axx', 'bbb', 'ccc']
  X  got: None     expected: ['xaa', 'xcc', 'aaa', 'bbb', 'ccc']
  X  got: None     expected: ['xanadu', 'xyz', 'aardvark', 'apple', 'mix']

sort_last
  X  got: None     expected: [(2, 1), (3, 2), (1, 3)]
  X  got: None     expected: [(3, 1), (1, 2), (2, 3)]
  X  got: None     expected: [(2, 2), (1, 3), (3, 9, 4), (1, 7)]
```

## Testing with Unittest
This assignment also has separate unit tests to help you during development. The unit tests are located in the `tests` folder; you should not modify these.  Make sure all unit tests are passing before you submit your solution. You can invoke the unit tests from the command line at the root of your project folder:
```console
$ python -m unittest discover tests
```
You can also run these same tests using the `Test Explorer` extension built in to the VSCode editor, by enabling automatic test discovery.  This is a really useful tool and we highly recommend to learn it.

https://code.visualstudio.com/docs/python/testing#_test-discovery

- Test framework is `unittest`
- Test folder pattern is `tests`
- Test name pattern is `test*`

## Submitting your work
To submit your solution for grading, you will need to create a github [Pull Request (PR)](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).  Refer to the `PR Workflow` article in your course content for details.
