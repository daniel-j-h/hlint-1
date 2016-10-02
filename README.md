# hlint

  - [Overview](#overview)
  - [Who Can Attend?](#who-can-attend)
  - [Location and Times](#location-and-times)
  - [Goals](#goals)
  - [Volunteer as a Mentor](#volunteer-as-a-mentor)
  - [Getting Started](#getting-started)
  - [Finding a Task](#finding-a-task)
  - [Tips][#tips]
  - [Code of Conduct](#code-of-conduct)
  - [Thanks](#thanks)

### Overview
A Haskell themed event centred around improving [Hlint]! Hlint is a tool for
suggesting stylistic improvements to your Haskell code and was created by [Neil
Mitchell]. The event is a collaborative affair in which Haskellers from varying
different skill levels and backgrounds will come together to learn and
contribute to Hlint. If that sounds like fun, please do attend.

[Hlint]: https://github.com/ndmitchell/hlint
[Neil Mitchell]: http://ndmitchell.com/

### Location and Times
  - [Berlin. 2nd of October, 2016]

[Berlin. 2nd of October, 2016]: http://www.meetup.com/berlinhug/events/234415953/

### Who Can Attend?
The event is free and open for anyone interested in Haskell programming.

### Goals
The goal of this event is to bring together people interested in the Haskell
programming language. The event is not competitive but cooperative. There is no
pressure to actually produce results but rather start a conversation between
yourself and the contributors of Hlint. We want to improve the Hlint tool in
any way possible and foster a culture of contribution. This could mean writing
a piece of documentation or reporting a bug, it could be writing a new feature
or even just suggesting one.

### Volunteer as a Mentor
This event will need a number of volunteers to offer some of their time in
helping other participants with their problems. Volunteers will typically be
familiar with Git, how to use Github, Stack and how to write Haskell in
general. Please [submit a pull request] and add yourself to the list below if
you feel like helping.

[submit a pull request]: https://github.com/haskellpeople/hlint/pulls

Current volunteers:

  - [Luke Murphy]

[Luke Murphy]: https://github.com/lwm

### Getting Started
Here's what you need to do to get a development copy of Hlint on your
machine:

  - 1) [Install Stack]
  - 2) [Fork Hlint on Github]
  - 3) [Clone your Hlint fork]
  - 4) Run the following Stack commands in your Hlint directory:
    - Initialise a Stack configuration with `stack init`
    - Build the project and dependencies with `stack install`
    - Run the tests with `hlint test` (requires `~/.local/bin/` on `$PATH`)

[Install stack]: https://docs.haskellstack.org/en/stable/install_and_upgrade/
[Fork Hlint on Github]: https://github.com/ndmitchell/hlint#fork-destination-box
[Clone your Hlint fork]: https://help.github.com/articles/cloning-a-repository/

Once the tests pass you can be sure that you are ready to start. You can then
follow the usual [Github flow].

[Github flow]: https://guides.github.com/introduction/flow/

### Finding a Task
We'll be using Github issues to coordinate our work. Please review
the current [issues here].

[issues here]: https://github.com/haskellpeople/hlint/issues

Each issue could have one of the following labels:

  - `documentation`: Documentation is missing or can be improved.
  - `new-hint`: A hint is missing.
  - `existing-hint`: An existing hint could be improved.
  - `command-line-interface`: The command line interface needs work.
  - `configuration`: Hlint configuration via the command line.
  - `testing`: Hlint could use some help with testing.
  - `maintainer-request`: A maintainer has requested this contribution.

If you need some help to move forward, log into the [HLint Gitter chat]. Neil
has mentioned that he might be able to spare some cycles to help with
questions.

[HLint Gitter chat]: https://gitter.im/hlint/Lobby

Please feel free to choose one of the issues. Once you're ready to start
working, assign it to yourself. If you're not sure what to work on, please ask
a mentor!

Please also feel free to choose your own issue to work on. It's quite likely
you also found something that can be improved! Please create your issue on the
issues page. Once you've submitted a pull request to the Hlint repository,
please close the relevant issue with a link to your contribution.

### Tips

  - [Making ghci fast]
  - [HLint manual]

[Making ghci fast]: http://chrisdone.com/posts/making-ghci-fast
[HLint manual]: http://community.haskell.org/~ndm/darcs/hlint/hlint.htm

### Code of Conduct
We want everyone to feel welcome. Let's behave nicely to each other.

> Our event is dedicated to providing a harassment-free experience for
> everyone, regardless of gender, gender identity and expression, age, sexual
> orientation, disability, physical appearance, body size, race, ethnicity,
> nationality, religion, previous event attendance or computing experience
> (or lack of any of the aforementioned). We do not tolerate harassment of
> event participants in any form. Sexual language and imagery is not
> appropriate at any event venue, including hacks, talks, workshops,
> parties, social media and other online media. Event participants
> violating these rules may be sanctioned or expelled from the event
> without a refund (if applicable) at the discretion of the event
> organisers.

Adapted from [hackcodeofconduct].

[hackcodeofconduct]: http://hackcodeofconduct.org/

### Thanks
  - [co.up Coworking Space]
  - [HUG Berlin]

[co.up Coworking space]: http://co-up.de/
[HUG Berlin]: https://www.meetup.com/berlinhug/
