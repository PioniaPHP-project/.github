<!-- omit in toc -->
# Contributing to Pionia Framework

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
> - Star the project
> - Tweet about it
> - Refer this project in your project's readme
> - Mention the project at local meetups and tell your friends/colleagues

<!-- omit in toc -->
## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
  - [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
  - [Commit Messages](#commit-messages)
<!-- - [Join The Project Team](#join-the-project-team) -->


## Code of Conduct

This project and everyone participating in it is governed by the
[Pionia Framework Code of Conduct](https://github.com/PioniaPHP-projectblob/master/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior
to <ezrajet9@gmail.com>.


## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation](https://pionia.netlify.app).

Before you ask a question, it is best to search for existing [Issues](https://github.com/PioniaPHP-project/issues) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open an [Issue](https://github.com/PioniaPHP-project/issues/new).
- Provide as much context as you can about what you're running into.
- Provide project and platform versions (nodejs, npm, etc), depending on what seems relevant.

We will then take care of the issue as soon as possible.

<!--
You might want to create a separate issue tag for questions and include it in this description. People should then tag their issues accordingly.

Depending on how large the project is, you may want to outsource the questioning, e.g. to Stack Overflow or Gitter. You may add additional contact and information possibilities:
- IRC
- Slack
- Gitter
- Stack Overflow tag
- Blog
- FAQ
- Roadmap
- E-Mail List
- Forum
-->

## I Want To Contribute

> ### Legal Notice <!-- omit in toc -->
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project license.

### Reporting Bugs

<!-- omit in toc -->
#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version.
- Determine if your bug is really a bug and not an error on your side e.g. using incompatible environment components/versions (Make sure that you have read the [documentation](https://pionia.netlify.app). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](https://github.com/PioniaPHP-projectissues?q=label%3Abug).
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Collect information about the bug:
  - Stack trace (Traceback)
  - OS, Platform and Version (Windows, Linux, macOS, x86, ARM)
  - Version of the interpreter, compiler, SDK, runtime environment, package manager, depending on what seems relevant.
  - Possibly your input and the output
  - Can you reliably reproduce the issue? And can you also reproduce it with older versions?

<!-- omit in toc -->
#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to <ezrajet9@gmail.com>.
<!-- You may add a PGP key to allow the messages to be sent encrypted as well. -->

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue](https://github.com/PioniaPHP-project/issues/new). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- A team member will try to reproduce the issue with your provided steps. If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `needs-repro`. Bugs with the `needs-repro` tag will not be addressed until they are reproduced.
- If the team is able to reproduce the issue, it will be marked `needs-fix`, as well as possibly other tags (such as `critical`), and the issue will be left to be [implemented by someone](#your-first-code-contribution).

<!-- You might want to create an issue template for bugs and errors that can be used as a guide and that defines the structure of the information to be included. If you do so, reference it here in the description. -->


### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for Pionia Framework, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.

<!-- omit in toc -->
#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Read the [documentation](https://pionia.netlify.app) carefully and find out if the functionality is already covered, maybe by an individual configuration.
- Perform a [search](https://github.com/PioniaPHP-project/issues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.

<!-- omit in toc -->
#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://github.com/PioniaPHP-project/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- You may want to **include screenshots and animated GIFs** which help you demonstrate the steps or point out the part which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux. <!-- this should only be included if the project has a GUI -->
- **Explain why this enhancement would be useful** to most Pionia Framework users. You may also want to point out the other projects that solved it better and which could serve as inspiration.

<!-- You might want to create an issue template for enhancement suggestions that can be used as a guide and that defines the structure of the information to be included. If you do so, reference it here in the description. -->

### Your First Code Contribution
<!-- TODO
include Setup of env, IDE and typical getting started instructions?

-->
Pionia is made up of multiple projects, you need to first understand which repo you want to contribute to. 

#### Prerequisites.
1. You need PHP 8.0 or higher for all contributions, preferably the latest.
2. An IDE such as PHPStorm, IntelliJ IDEA or any editor like VS Code.
3. Git and a GitHub profile
4. Composer

#### Framework
If you want to contribute to the core framework, follow the following to Set up the environment locally on your machine.

The following steps will get you started contributing to the Core Framework.

1. Fork [this repository](https://github.com/PioniaPHP-project/Pionia.git) to your own github profile.
2. Clone the forked repository.
3. Run `composer install` to install all dependencies.
4. Start making your changes.

To make sure everything runs very fine, run the following.
```bash
cd example && php pionia serve
```
The above should start the Pionia test project in the `example` folder. 

To run tests, run the following command in the root directory.
```bash 
composer test
```

To document your changes in [the core-dev api docs](https://pioniaphp-project.github.io/Pionia/), run the following.
```bash
composer document
```

### Application
To contribute to the application boilerplate, follow the following steps to get started.

1. Fork [this repository](https://github.com/PioniaPHP-project/Application) to your own github profile.
2. Clone the forked repository.
3. Run `composer install` to install all dependencies.
4. Start making your changes or adding your new features.

### Final Steps.
When you're done making your changes on either projects, it's time to make your PR(pull request).

1. Add your changes to the commit history using `git add changed_file_here`
2. Add a clean, intuitive commit message that clearly describes what you changed. If you're resolving an issue, please define the issue you're solving using the command `git commit -m "your_message_here"`
3. Push your changes to your fork.
4. Make a pull request to the main repo attaching a clean PR message.

The core maintainers will review your codebase and advise on how to follow up.

### Improving The Documentation
<!-- TODO
Updating, improving and correcting the documentation

-->
If your changes are in the core framework, make sure to run the command `composer document` so that your changes can reflect in the api documentation.
API documentation follows and uses `phpdocumentor`. Therefore, you need to equip yourself with the [package documentation syntax](https://phpdoc.org/).

This documentation is meant for only core-developers. however, your changes need to reflect in the public official docs. 

Public docs can be contributed to directly here in github. After making your changes, make a PR. 
Netlify will provide for you a temporaly review url for your PR which you can visit to see how your changes will look like once deployed.

However, we advise you to setup the docs repo locally following the steps. 

#### Requirements
1. Git
2. Hugo - [setup Hugo here](https://gohugo.io/installation/)
3. Package manager of your choice preferably npm or yarn
4. Nodejs atleast 20+
5. IDE or editor of choice

Steps to set up the environment locally.

1. Fork the repository to your profile
2. Clone the repository locally.
3. Install dependencies by running `yarn install`
4. Add your changes in the `content` directory.
5. Add your changes to the git history, commit and push them to your fork.
6. Make a pr to the main repo, clearly defining the changes you made.

## Styleguides
All PHP repositories follow the[ PSR-12 - Extended Coding Style](https://www.php-fig.org/psr/psr-12/) to maintain a clean codebase and all contributors MUST adhere to this.

Whereas the docs use markup languag, developers are advised to maintain a coherent coding standard following the existing format.
For further guidance on the docs - [please visit the doks documentation on how to author clean content in the documentation](https://getdoks.org/docs/basics/authoring-content/)
### Commit Messages
<!-- TODO

-->
Commit messages should be fully descriptive and intuitive to guide the maintainers on exactly what was added, or updated in the incoming commit change. 

Example
```bash
git commit -m "update:- Added support for XXX in XXX.xxx that fixes #issue_number_or_problem_at_hand".
```
To come up with thoughtful commits, consider the following:

1. Why have I made these changes?
2. What effect have my changes made?
3. Why was the change needed?
4. What are the changes in reference to?

Further example on good and bad commits.
```bash
# bad commit
git commit -m "added a margin"

# good commit
git commit -m 'Add margin to nav items to prevent them from overlapping the logo'
```

You can also [read through this article](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/) to also look at creating conventional commit messages that are more standard and easy to understand by future readers.

<!-- ## Join The Project Team
<!-- TODO -->
<!-- You can join us  --> 

<!-- omit in toc
## Attribution
This guide is based on the **contributing-gen**. [Make your own](https://github.com/bttger/contributing-gen)! -->
