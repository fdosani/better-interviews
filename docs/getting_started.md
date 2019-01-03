# Getting started

This framework will help provide guidelines on how technical interviews can be
conducted in a fair manner (to both candidates and companies). The goal isn't
to force certain practices on people, but to help highlight the pros and cons
while providing better alternatives to just pain old white boarding or take home
exams.

These types of technical interviews lead to a lot of *false positives* and
penalizes people of certain backgrounds. Not everything here might be relevant to your organization, or maybe it might be all relevant. Pick and choose what works and
what doesn't. Transparency and fairness are key.


## What we trying to optimize for?

It is important to take a step back and ask: *What are we trying to optimize for?*

Most companies are looking for the best and brightest minds in terms of:

- technical
- project and time management
- communication, collaboration, and team work?

Out of the few things in this list, some skills might be more important than
others right? From personal experience there is a lot of emphasis on coding
skills which leads to many pre screening techniques where a candidate is subject
to a battery of tests to make sure they are up to snuff. If they don't *pass*
this portion they typically don't continue on in the process.


## Coding challenges

Coding challenges consist of algorithmic/puzzles/riddles to test how "smart"
someone is. Here is a simple example from a bunch of popular websites

```
A non-empty array A consisting of N integers is given. A permutation is a
sequence containing each element from 1 to N once, and only once.
For example, array A such that:
    A[0] = 4
    A[1] = 1
    A[2] = 3
    A[3] = 2

is a permutation, but array A such that:
    A[0] = 4
    A[1] = 1
    A[2] = 3

is not a permutation, because value 2 is missing.

The goal is to check whether array A is a permutation.

Write a function that, given an array A, returns 1 if array A is a permutation
and 0 if it is not. For example, given array A such that:
    A[0] = 4
    A[1] = 1
    A[2] = 3
    A[3] = 2

the function should return 1.
```

A solution might look something like the following with some test cases included

```python
def permutation(A):
    lenA = len(A)
    distinctA = set(A)
    # if there are dups
    if len(distinctA) != lenA:
        return 0
    #if there are missing sequence
    if max(A) != lenA:
        return 0
    return 1


assert permutation([1, 2, 3, 4]) == 1
assert permutation([1, 2, 3, 4, 4, 1, 2, 3]) == 0
assert permutation([1, 1]) == 0
assert permutation([1]) == 1
assert permutation([1, 2, 4]) == 0
```

The goal is to getting the "optimal" answer in the shortest amount of time while
writing on a white board or live coding editor.

## What coding challenges are (not) optimizing for

With enough practice of these types of coding challenges a candidate can get
fairly good at pattern recognition and memorization on how to go about solving
questions like this.

What they don't really tell you is how a person really thinks about a problem in
real life. Most real life situations don't have a arbitrary time limit or
pressure of someone watching you. Real life also doesn't preclude you from
searching the internet for syntax, possible solution, or researching the topic
before hand.

More importantly it tells you nothing about how they work in a team setting,
prioritize their work, follow good coding practices, or their true technical
skill set.

Lastly many of these problems are not reflective of real world problems that
most people will face on a day to day basis. In fact the total opposite.


## Power imbalance

It is important to recognize the power imbalance in these types of situations.

Candidates are typically nervous and want to make a good impression.
Interviewers are trying to figure out if the person in front of them is right
candidate for the job, which carries its own pressure, but a different kind.

Regardless, there is a power imbalance which should be noted. The interviewer
has the answer and knowledge available to them while the candidate does not.
This is another subtle issue with white boarding type interviews which can have
a negative psychological impact where the candidate compares themselves to the
interviewer and perpetuates a feeling of impostor syndrome, worthlessness, or
self doubt.

Part of the solution in the framework is meant to help address this aspect of
the technical interview process.


## Solutions

The hope is this framework can lead to a more accurate assessment of a candidates
technical ability, with rigour that is realistic and fair. The first step is to
be aware of the pros and cons of the various options, removing as much bias as
possible, and leading to a better interview process for all parties involved.
