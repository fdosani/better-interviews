Better Interviews
-----------------

An Open source framework for conducting technical interviews.

As someone who does hiring, I find the interview process is broken. So I'm
hoping to do my part to help fix this. In this repo/site you will find an open
source framework for technical interviews which I hope anyone and everyone can
use to improve on the dreaded technical interview (white boarding / live coding).

> Note: this is not going to be a perfect solution, but it is a start which
I'm hoping will evolve overtime to be better, more inclusive, and less stressful.


### Problem
The current state of technical (white boarding) interviews is broken.
See:
- [THEY WHITEBOARDED ME](http://they.whiteboarded.me/interview_types/whiteboarding_and_live_coding.html)
- [The Mental Impact of Tech Interviews (YouTube)](https://www.youtube.com/watch?v=aIrKC41NwC0)


We need to find a better way to handle for the above problem where we minimize:
* The power imbalance between interviewer and interviewee.
* Removing bias from the interview process which can many times penalize:
  - interviewees with families (age, or gender discrimination)
  - extra family commitments (taking care of a sick family member or
    one with special needs)
  - mental health issues such as anxiety, depression, etc.
  - the list goes on...

All the while further contributing to impostor syndrome

What we should be maximizing is:

* Learning what the candidate is *good* at
* What they have accomplished as a whole
  * there are other facets other than programming skills which make up
    the job and candidate
* What is *relevant* to the actual job!

**and most importantly their technical skills in an accurate setting.**


### Potential Solution(s) and the Framework

##### Choose your path

As a initial option the thought is you allow the candidate to pick from several
options which they are comfortable with in terms of conducting their technical
interview.

> While these option may not solve for all the potential issues it helps minimize
some of the bias and allow for candidates to select a path they are most
comfortable with. Again this is a work in progress! Please consider contributing.

1. Take home exam
   - Company specific curated take home assignment which the candidate would do
     on their own time and turn in for grading


2. Complete an assignment (from a list of smallish problems):
   - Candidate would get this "homework" before their interview to complete.
   - They would submit their solution 1-2 hours before for review by the    
     interviewee. This allows for time to review and formulate some questions
     and suggestions in response.
   - Interviewer would then asking probing questions about the solution to get
     a sense of the reasons for their design choices, thought process, and over
     all structure.
   - A final step might be to perform a small refactoring of the code to properly
     verify the knowledge of the candidate, and get a sense of their working
     style. This might be a pair-programming session.


3. Their own personal project
   - TBD


4. Live coding / white boarding (else option)
   - TBD


### Additional framework thoughts

We should also lay out some sort of best practices for the engagement between
parties.

- clear instructions and expectations of the tasks and outcomes
- fair timelines and next steps
- respecting the time of both parties
- making sure there is follow up
- tracking all this to ensure we can make data driven decisions and continue to
  improve.


### Generating this site

For now the site is being generated with [`docsify`](https://docsify.js.org). You can install / setup it via the
following:

```bash
# if you don't have node installed (macOS)
brew install node

# install docsify
npm i docsify-cli

# clone repo and serve up the pages
git clone https://github.com/fdosani/better-interviews.git
cd better-interviews
docsify serve ./docs
```

### Contributing
I need your (the community at large) help with this project. Please feel free to
submit issues, comments, PRs etc. The only way this works is through a
collaborative effort where everyone has a say.
