# A Software Development Manifesto

## Why?

After building software for many years,
I've come to develop some beliefs
about how to do so effectively,
efficiently,
and with the happiest team.

All opinions are my own,
although most are based on
solid ideas from other smart people.
Those smarties are attributed
when I can remember to do so.

### Managing the Software Development Process

* The only measure of progress is shipped working software in production. (from
  [The Agile Manifesto]) This means no velocity, no burndown charts, no story
  counting.
* The people who are actually building the software are in the best position to
  design and alter the tools, communication flows, and project management
  philosophy.
* Software is best built with at least one other person.
  It's not impossible to do by yourself, but it won't come out as well
  and certainly won't be as much fun.
* The best project management tools, in order, are Trello, Stickie Notes,
  and Nothing. If you need more than this, you are likely planning too far ahead
  into the future or too far down in the implementation details, or both.
* Every Monday Morning, have a Planning Meeting. The purpose is to list all the
  user stories worth working on that week and prioritize them. That's it.
* Every user story should be validated somehow with actual or potential users.
  You can do so via prototyping, A/B testing, False Doors, etc. but if it's just
  someone's idea, you are throwing money away and wasting everyone's time.
* Estimating how long something will take to build is, at best, a worthless
  activity and at worst, damaging to the team's trust and dynamic. Estimates are
  never correct, or even close to accurate. They do not help product owners
  "decide what to buy" because the cost is always unknown. Measuring "how much
  we got done this week" only decreases development efficiency, because it makes
  people feel badly.
* Every Friday afternoon, the team should demo the product to whoever pays for
  it. That's the best way of being accountable.
* The term "Backlog" is extremely discouraging and should be avoided. Think
  about having a "backlog" on day 1 of the project: You haven't even started and
  you're already behind!
* Marking time in "sprints" clearly tells the developers to
  "work at an unhealthy pace until you can't go on anymore".
  Language is important.
* The product should ship to real users as soon as possible, ideally within a
  few weeks. Further features should only be based on user feedback,
  not someone's fever dreams. You are not Steve Jobs.

[The Agile Manifesto]: http://www.agilemanifesto.org

### Writing and Maintaining Healthy Code

* Software is most cheaply and safely written with 100% test coverage.
* The tests should be written first. There are no exceptions. Spikes are helpful
  research, but should be deleted.
* RSpec is the best tool for testing Ruby code. It is well-maintained and
  evolves with the community.
* Every Monday morning, [update your dependencies].
* Pull requests should be small and take no longer than a day to write. If need
  be, create pull requests into non-master branches or feature-flag your work.
* Deploying the code to staging or production should be a one-line command.
  It should not take longer than 5 minutes in total. If it does, your project
  will slow down dramatically. Heroku is best for this. There is a massive
  implied cost in running your own infrastructure or doing custom deploys. It is
  not even close to outweighed by paying Heroku a little more for servers.

[update your dependencies]: http://adarsh.io/save-money-and-be-happier-by-updating-your-gems-every-monday-morning/

### Communication

### Tool Choice

### On App Ideas

* Worthless. The value comes only in shipping software, talking to users, and
  iterating based on that feedback as quickly and intelligently as possible.

## Acknowledgements

## License

This work is Copyright ©2016
Adarsh Pandit.
It may not be redistributed
without express written consent
of the author.
