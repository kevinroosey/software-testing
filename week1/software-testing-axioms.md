# Software testing axioms

### Testing axioms

Think of testing axioms as the rules of the road.

1. It's impossible to test a program completely

As a new tester, you might believe that you can approach a piece of software, fully test it, find all the bugs, and assure
that the software is perfect. Unfortunately, this isn’t possible, even with the simplest programs, due to four key reasons:
• The number of possible inputs is very large.
• The number of possible outputs is very large.
• The number of paths through the software is very large.
• The software specification is subjective and open to interpretation

2. Software testing is a risk based exercise
3. Testing can't show bugs that don't exist
4. The more bugs you find, the more bugs there are
5. The pesticide paradox
* In 1990, Boris Beizer, in his book Software Testing Techniques, coined the term pesticide paradox to describe the
phenomenon that the more you test software, the more immune it becomes to your tests. The same thing happens to
insects with pesticides. If you keep applying the same pesticide, the insects eventually build up resistance and the
pesticide no longer works.

6. Not all the bugs you find will be fixed

There are several reasons why you might choose not to fix a bug:
• There’s not enough time. In every project there are always too many software features, too few people to code and
test them, and not enough room left in the schedule to finish. If you’re working on a tax preparation program, April
15 isn’t going to move—you must have your software ready in time.
• It’s really not a bug. Maybe you’ve heard the phrase, "It’s not a bug, it’s a feature!" It’s not uncommon for
misunderstandings, test errors, or spec changes to result in would-be bugs being dismissed as features.
• It’s too risky to fix. Unfortunately, this is all too often true. Software can be fragile, intertwined, and sometimes like
spaghetti. You might make a bug fix that causes other bugs to appear. Under the pressure to release a product under
a tight schedule, it might be too risky to change the software. It may be better to leave in the known bug to avoid the
risk of creating new, unknown ones.
• It’s just not worth it. This may sound harsh, but it’s reality. Bugs that would occur infrequently or bugs that appear in
little-used features may be dismissed. Bugs that have work-arounds, ways that a user can prevent or avoid the bug,
are often not fixed. It all comes down to a business decision based on risk.

7. When a Bug’s a Bug Is Difficult to Say
* If there’s a problem in the software but no one ever discovers it - not programmers, not testers, and not even a single customer - is it a bug?

8. Product specs are never file
* Software developers have a problem. The industry is moving so fast that last year’s cutting-edge products are obsolete
this year. At the same time, software is getting larger and gaining more features and complexity, resulting in longer and longer development schedules

9. Software Testers Aren’t the Most Popular Members of a Project Team
Remember the goal of a software tester:
The goal of a software tester is to find bugs, find them as early as possible, and make sure they get fixed.
Your job is to inspect and critique your peer’s work, find problems with it, and publicize what you’ve found. Ouch! You
won’t win a popularity contest doing this job.



