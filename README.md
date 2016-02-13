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

* Software is best built with at least one other person.
  It's not impossible to do by yourself, but it won't come out as well
  and certainly won't be as much fun.
* The best project management tools, in order, are Trello, Stickie Notes,
  and Nothing. If you need more than this, you are likely overplanning into the
  future or too far down in the implementation details, or both.
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
  it. That's accountability.
* The term "Backlog" is extremely discouraging and should be avoided.


### Writing and Maintaining Healthy Code

* Every Monday morning, [update your dependencies].
* Deploying the code to staging or production should be a one-line command.
  It should not take longer than 5 minutes in total. If it does, your project
  will slow down dramatically. Heroku is best for this. There is a massive
  implied cost in running your own infrastructure or doing custom deploys. It is
  not even close to outweighed by paying Heroku a little more for servers.

[update your dependencies]: http://adarsh.io/save-money-and-be-happier-by-updating-your-gems-every-monday-morning/

### Communication

### Tool Choice

## Acknowledgements

## License

This work is Copyright ©2016
Adarsh Pandit.
It may not be redistributed
without express written consent
of the author.
