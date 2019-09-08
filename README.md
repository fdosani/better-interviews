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

It is important to allow candidates to "choose their own path," because
different personalities will shine best in different scenarios. You want the
candidate to be as comfortable as possible during their coding interview. While these option may not solve for all the potential issues it helps minimize
some of the bias.

> This is a work in progress. If you have additional ideas/formats, please
consider contributing.

1. **Timed take home exam or exercise**, from a small list of problems. This is
a company specific curated take home assignment which the candidate would do
on their own time and turn in for grading/evaluation.
  - Pros:
    - It allows candidates to do the evaluation on their own time.
    - If timed, if better puts candidates on equal footing.
    - Interviewee can pre-formulate questions and suggestions in response to
      what the candidate turned in.
  - Cons:
    - Candidates that are care takers (individuals with kids or those taking care
      of parents or the like) or individuals that are commited to
      extracurriculars, such as community sports, religion, or volunteerism are
      at a disadvantage, because they have less time after hours focus to be
      able to complete the exam.
    - As an untimed test, this puts the previous category at a bigger
      disadvantage. You can say, "this only takes two hours," but in reality
      those with extra time after hours will put in more time and those who
      can't won't be able to.

2. **On-site coding test**.


3. **Present personal project**
   - TBD


4. **Live coding / white boarding**
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
