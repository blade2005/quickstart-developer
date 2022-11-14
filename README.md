# Quick Start - Developer

A repository for helping new developers/engineers to quickly start up improving their skills.

## Troubleshooting

Your systematic approach to troubleshooting should involve five basic steps;

- Information Gathering
- Analysis and Planning
- Implementation of a solution
- Assessment of the effectiveness of the solution
- Documentation of the incident

Below we will address these steps individually.

**Information Gathering**  Before we can determine how to address a problem--or even assess what the problem is--we must gather information. Gathering information can be particularly challenging when the problem manifests itself at the client side. You might have to formulate your questions carefully in order to get meaningful information. Log files contain great information you should consult during the data-gathering stage. Try to avoid assumptions. If you reach the end of analysis and can not find the issue re-visit the information you have and look for where an assumption has been made. This is a great opportunity to slow down and carefully read documentation and logs, do not skim them.

**Analysis** Once we have gathered the data (including attempting to reproduce the problem), it's time to analyze the data.  The primary task in this phase is to look for patterns. An important part of the analysis phase involves prioritizing. This includes prioritizing the problems, if there are multiple problems. Performance problems are generally less urgent than access problems.

**Solution Implementation** Although there could be several possible solutions to a problem, you should always implement one change at a time. Assess the results of that change before trying something else. This will save you time in the long run. Start with the most obvious or most impactful change first, if they are all not obvious or may not be impactful, go with the easiest to validate.

**Assessment**  It is vital that you assess the results of your actions and determine whether the "fix" worked, whether it was a temporary work around, or whether it caused additional problems.

**Documentation** After completing your assessment, you should develop a summarization of the problem, which should include the reported and observed symptoms, the corrective actions taken, and the results of those actions.

*Adapted from [The Five Steps of Troubleshooting](https://www.aimetis.com/webhelp/aira/v5/en/troubleshooting/Troubleshooting_Guidelines/The_Five_Steps_of_Troubleshooting.htm)*

## Shells

### Bash

- [Bash 101: Working at the CLI](https://www.linux.com/training-tutorials/bash-101-working-cli/)

### Zsh

- [Terminal 101 — The Setup Guide that will Boost your Workflow](https://itnext.io/terminal-101-the-setup-guide-that-will-boost-your-workflow-12df2570052)
- [Getting started with oh-my-zsh](https://dienbui.medium.com/using-oh-my-zsh-f65be6460d3f)

### Shell Tools

- [Sed](https://www.grymoire.com/Unix/Sed.html)
- [jq](https://lzone.de/cheat-sheet/jq)
- [grep](https://www.eriwen.com/tools/grep-is-a-beautiful-tool/)
  - [Regex primer](http://marvin.cs.uidaho.edu/~heckendo/Handouts/regex.html)
- [find](https://www.eriwen.com/productivity/find-is-a-beautiful-tool/)
- [man](https://phoenixnap.com/kb/linux-man)
- [vim](https://www.linuxfoundation.org/blog/blog/classic-sysadmin-vim-101-a-beginners-guide-to-vim)
  - Yes there's a lot more to vim, start slow.
- [awk](https://www.thegeekstuff.com/2010/01/awk-introduction-tutorial-7-awk-print-examples/)
- [GNU Tools](https://www.gnu.org/software/software.html)

## Git

- [Writing Git Commit Messages](https://cbea.ms/git-commit/)
- [How to Write Better Git Commit Messages – A Step-By-Step Guide](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)
- [Art of writing a good commit message](https://dev.to/wordssaysalot/art-of-writing-a-good-commit-message-56o7)
- [git - the simple guide](https://rogerdudler.github.io/git-guide/)
- [Git 101 — Introduction to Git for Newbies](https://medium.com/@itswisdomagain/git-101-introduction-to-git-for-newbies-bb14f6f9fc1)
- [Getting Git Right](https://www.atlassian.com/git)
- [Git Documentation](https://git-scm.com/doc)

## Learning Python

- [Automate the Boring Stuff with Python by Al Sweigart](https://automatetheboringstuff.com/)
- [Al Sweigart Twitch](https://www.twitch.tv/alsweigart)
- [Learn Python Reddit](https://www.reddit.com/r/learnpython/)
  - [Wiki](https://www.reddit.com/r/learnpython/wiki/index/)
- [Python Reddit](https://www.reddit.com/r/python/)
- [r/python discord](https://discord.gg/python)
- [Introduction to Python](http://introtopython.org/)
- [Koans Part 1](https://github.com/arachnegl/python-koans)
- [Koans Part 2](https://github.com/gregmalcolm/python_koans)

## Learning Javascript/Typescript

- [The Modern JavaScript Tutorial](https://javascript.info/)
- [The TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [JavaScript Algorithms and Data Structures](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/)
- [JavaScript Naming Conventions](https://www.robinwieruch.de/javascript-naming-conventions/)
- [Better Jasmine Tests With this](https://gist.github.com/traviskaufman/11131303)
- [Koans](https://github.com/paytonrules/typescript.koans)

## Learning Ruby

- [Koans](http://rubykoans.com/)

## Testing

- [What Is Software Testing](https://www.softwaretestingmaterial.com/software-testing/)
- [The different types of software testing](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)

## Advanced Programming

- [Refactoring.Guru](https://refactoring.guru/)
- [The Pragmatic Programmer: your journey to mastery](https://www.amazon.com/dp/B07VRS84D1)

## Video Discussions on Software Development

- [Full Stack Fest 2015: Nothing is Something, by Sandi Metz](https://www.youtube.com/watch?v=9mLK_8hKii8)
- [Talk Session: Polly Want a Message](https://www.youtube.com/watch?v=YtROlyWWhV0)
- [SOLID Object-Oriented Design by Sandi Metz](https://www.youtube.com/watch?v=v-2yFMzxqwU)
- [The Magic Tricks of Testing by Sandi Metz](https://www.youtube.com/watch?v=URSWYvyc42M)
- [Sandi Metz: "Go Ahead, Make a Mess"](https://www.youtube.com/watch?v=mpA2F1In41w)
- [Clean Code Playlist](https://youtube.com/playlist?list=PLUxszVpqZTNShoypLQW9a4dEcffsoZT4k)
- [UncleBob Expecting Professionalism](https://www.youtube.com/watch?v=BSaAMQVq01E)

## Frontend

- [Learn React](https://scrimba.com/learn/learnreact)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Testing React Apps](https://jestjs.io/docs/tutorial-react)

## Terraform

- [Terraform Best Practices](https://www.terraform-best-practices.com/code-structure)
- [Google Terraform Best Practices](https://cloud.google.com/docs/terraform/best-practices-for-terraform)
- [Terraform Best Practices by Ashish Patel](https://medium.com/devops-mojo/terraform-best-practices-top-best-practices-for-terraform-configuration-style-formatting-structure-66b8d938f00c)
