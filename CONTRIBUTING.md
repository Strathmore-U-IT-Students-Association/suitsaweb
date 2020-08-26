# Introduction

### Welcome to suitsaweb's contribution guide🎉!

First off, thank you for considering contributing to suitsaweb. It's people like you that make suitsa a great club to thrive in.

SUITSA is a strathmore IT club that help memebers thrive by involving them in its daily activities. The suitsa web align in that goal of inclusivity, and it's
a platform for suitsa memeber to showcase their work.

### Why you should read the guidelines.

Following these guidelines helps to communicate that you respect the time of the developers managing and developing this project. In return, 
they should reciprocate that respect in addressing your issue, assessing changes, and helping you finalize your pull requests.

### Contributions.

Keep an open mind! There are countless ways you can contribute to suitsaweb. Here are some examples
* Feature suggestions
* bug reporting
* new functionality
* bug fixes
* UI improvement
* etc.

# Ground Rules
This includes not just how to communicate with others (being respectful, considerate, etc) but also technical responsibilities (importance of testing, project dependencies, etc).

**Responsibilities**
* Ensure that you meet the deadlines (accountability)
* Ensure that code that has been pushed has been thouroghly tested
* Create issues for any major changes and enhancements that you wish to make. Discuss things transparently and get community feedback.
* Keep feature versions as small as possible, preferably one new feature per version.
* Be welcoming to newcomers and encourage diverse new contributors from all backgrounds.
* Be collaborative
* If you are unsure, ask for help
* Follow the PR template when creating a pull request.
* Under no circumstances you are allowed to push directly to the master branch

# Your First Contribution
First time to contribute to suitsaweb? Unsure where to begin contributing? checkout [the issues' tab](https://github.com/mboyamike/suitsaweb/issues) or visit [the projects](https://github.com/mboyamike/suitsaweb/projects)
to learn about the development flow.

# Getting started

* Tests are required for contributions, [visit](https://codeigniter.com/user_guide/testing/index.html) codeigniter's testing docs for more info

For something that is bigger than a one or two line fix:

1. Create your own fork of the code
2. Create a new branch following the guide lines defined [here](https://github.com/mboyamike/suitsaweb/tree/master/.github/BRANCH_NAMING.md)
3. Do the changes in your fork
3. If you like the change and think the project could use it:
    * Be sure you have followed the code style for the project.
    * create a pull request following this [style](https://github.com/mboyamike/suitsaweb/tree/master/.github/PR_TEMPLATE.md)

### Small or "obvious" fixes.

> Small contributions such as fixing spelling errors, where the content is small enough to not be considered intellectual property, can be submitted by a contributor without tests.

> As a rule of thumb, changes are obvious fixes if they do not introduce any new functionality or creative thinking. As long as the change does not affect functionality, some likely examples include the following:
* Spelling / grammar fixes
* Typo correction, white space and formatting changes
* Comment clean up
* Bug fixes that change default return values or error codes stored in constants
* Adding logging messages or debugging output
* Changes to ‘metadata’ files like Gemfile, .gitignore, build scripts, etc.
* Moving source files from one directory or package to another

# How to report a bug

If you find a security vulnerability, do NOT open an issue. Email security.suitsa@gmail.com instead.

Any security issues should be submitted directly to security.suitsa@gmail.com
In order to determine whether you are dealing with a security issue, ask yourself these two questions:
* Can I access something that's not mine, or something I shouldn't have access to?
* Can I disable something for other people?

If the answer to either of those two questions are "yes", then you're probably dealing with a security issue. Note that even if you answer "no" to both questions, 
you may still be dealing with a security issue, so if you're unsure, just email us at security.suitsa@gmail.com.

### How to file a bug report.
You can even include a template so people can just copy-paste (again, less work for you).

> When filing an issue, make sure to answer these five questions:

1. What version of Codeigniter are you using?
2. What operating system and processor architecture are you using?
3. What did you do?
4. What did you expect to see?
5. What did you see instead?

# How to suggest a feature or enhancement
If there is back-and-forth or signoff required, say so. Ask them to scope the feature, thinking through why it’s needed and how it might work.

> If you find yourself wishing for a feature that doesn't exist in suitsaweb, you are probably not alone. There are bound to be others out there with similar needs. 
Many of the features that suitsaweb has today have been added because our users saw the need. Open an issue on our issues list on GitHub which describes the feature 
you would like to see, why you need it, and how it should work.

# Code review process
Who reviews it?
Anyone can review a pull request.

Who needs to sign off before it’s accepted?
Only @tadomikikuto-bit, @mobyamike are allowed to merge the pull request.

When should a contributor expect to hear from you?
As soon as possible.

> The core team looks at Pull Requests on a regular basis in a weekly triage meeting that we hold in a public Google Hangout.
> After feedback has been given we expect responses in a weeks.

### Coding style.

The naming convention of functions and classes follow the camelCase and the PascalCase conentions respectively.
public function sumTwoNumbers() {}, class UserProfile {}. The variable names, must reflect the data they hold. $userInformation.
