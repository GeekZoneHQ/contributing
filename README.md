# Contributing

## Generally

Broadly, we follow the [Open Source Guide](https://opensource.guide/how-to-contribute/).

We try to keep things super informal and simple at Geek.Zone. We have no "boss" and we encourage experimentation. We
believe that there is no such thing as a mistake, there are only learning opportunities. We have no restrictions on time
or geography.

We do ask that you follow our [Code of Conduct](https://geek.zone/code-of-conduct/).

## Workflow
1. Assign yourself to an issue by commenting `/mine` on the issue you want to work on - no need to ask for permission.
2. If the issue has the "epic" label, split it into specific tasks that you can complete in one sitting.
    1. Log a new issue
    2. Include "relates to epic issue #*x*" in the issue body
    3. Assign yourself to the issue you just created using `/mine` as above.
3. Start working on the issue using [Test Driven Development](https://youtu.be/llaUBH5oayw).
   1. Write tests ***first*** - vital
   2. Write code
4. When you are done, create a pull request.

## How we do
- [PEP8](https://www.python.org/dev/peps/pep-0008/#tabs-or-spaces)
    <br>We use [spaces](https://www.youtube.com/watch?v=SsoOG6ZeyUI).
- [Test Driven Development](https://youtu.be/llaUBH5oayw) is vital
    <br>You must not write any code unless it is to make a failing test pass. [Obey the Testing Goat!](https://www.obeythetestinggoat.com/pages/book.html#toc)
- New repos
    <br>We have a [repo template](https://github.com/GeekZoneHQ/template) that you should use to start a new Geek.Zone repo.
- Merging
  <br>We prefer the rebase and merge workflow.
- [Eisenhower Method](https://en.wikipedia.org/wiki/Time_management#The_Eisenhower_Method)
  <br>Issues are prioritised according to their importance and priority.
- Keep PRs small.
  <br>This helps reviewers to approve them quickly.
- [async first](https://about.gitlab.com/company/culture/all-remote/asynchronous/).
  <br>We prefer to work asynchronously as much as possible.
- Placeless
  <br>We work without regard to geography.

## Communication
It is important to asynchronously communicate with other people on the project.

- Old ≠ bad
  <br>We do not close issues until they are complete. All ideas are welcome and will be developed as soon as possible.
- Frequent comments
  <br>Please share your progress in a comment on each issue that you are assigned to at least once per month.
- Inactive issues
  <br>If an issue receives no activity for 12 weeks, it will be unassigned to communicate to others that they can have a go.

## Naming

- Issue titles should be descriptive 
- PR titles must be descriptive so that you do not have to look up an issue to know what it does.
- Branch names must
  - be lower-case 
  - use the format<br />
    `[type]-[issue number]-[issue_title]`
  - replace [illegal branch characters](https://git-scm.com/docs/git-check-ref-format) with `_`. 
  - For example,<br />
   `feat-42-min_password_length`
- Commit messages must follow [Conventional Commits](https://conventionalcommits.org/).

Your IDE can probably do most of this for you.

Branch type names are,

| type   | Description                                                             |
|--------|-------------------------------------------------------------------------|
| `feat` | Feature I'm adding or expanding                                         | 
| `fix`  | Bug fix. Rectifying a fault in existing functionality.                  |
| `junk` | Throwaway branch created to experiment. Will not be merged.             |
| `doc`  | Only changes documentation; no code is altered. Will not trigger CI/CD. |


## License

As a member of the [Open Source Initiative](https://opensource.org/osi-affiliate-membership), all Geek.Zone code and software is published under GPLv3. You can find the full text of this in our `LICENSE` files. Any
contributions you make will be published under these provisions.

_Side note: Even though the correct spelling is "licence", we use the USA spelling of `LICENSE` as this has become the
[defacto standard](https://xkcd.com/927/) in tech._

## ...and Finally...

- Help!
  <br>If you need a hand, please just create an issue and we will be more than happy to assist.
- Attributions
  <br>You are encouraged to add yourself to `humans.txt` during your first issue, if you want to.
- Discord
  <br>Join our [Discord](http://geek.zone/discord) and chat with us in the #dev channel.  
- Members get trunk
  <br>Geek.Zone members are invited to the Geek.Zone org on GitHub so that they can contribute directly. Members are also part of a fantastic community of like-minded geeks. Membership only costs £1+donation each year so start by taking the [Geek.Zone/DevInduction](https://geek.zone/devinduction) now!