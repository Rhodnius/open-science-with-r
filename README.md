# Open Science with R

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-4-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[![Create a Slack Account with us](https://img.shields.io/badge/Create_Slack_Account-The_Carpentries-071159.svg)](https://swc-slack-invite.herokuapp.com/)

This repository generates the corresponding lesson website from [The Carpentries](https://carpentries.org/) repertoire of lessons. 

This lesson teaches modern R scripting using the `tidyverse` collection of packages, version control and collaboration using `git` and GitHub. Altogether, this provides a foundation for a more Open Science by offering practical ways of analysing data and building workflows and figures in a transparent and efficient manner.   

# Local preview of the website

To visualise the website before comming your changes and pushing them to GitHub, several options are available. 

## Ruby rbenv
`rbenv` is a way to manage different Ruby version on your machine. The GitHub page is here: [https://github.com/rbenv/rbenv](https://github.com/rbenv/rbenv). 

1. Install `rbenv` by following the instructions. 
2. Install your Ruby version with `rbenv install 2.7.3`
3. Install the required Gems (see the [Gemfile](./Gemfile) for the dependency list with `bundle install`
4. Preview the website locally with `bundle exec jekyll serve`. This will read the `_config.yml` file by default. 
5. Preview the website locally at http://127.0.0.1:4000


# Contributing and authors

We welcome all contributions to improve the lesson! Maintainers will do their best to help you if you have any questions, concerns, or experience any difficulties along the way.

We'd like to ask you to familiarize yourself with our [Contribution Guide](CONTRIBUTING.md) and have a look at
the [more detailed guidelines][lesson-example] on proper formatting, ways to render the lesson locally, and even
how to write new episodes.

Please see the current list of [issues][FIXME] for ideas for contributing to this
repository. For making your contribution, we use the GitHub flow, which is
nicely explained in the chapter [Contributing to a Project](http://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project) in Pro Git
by Scott Chacon.
Look for the tag ![good_first_issue](https://img.shields.io/badge/-good%20first%20issue-gold.svg). This indicates that the mantainers will welcome a pull request fixing this issue.  

## Maintainer(s)

Current maintainers of this lesson are 

* Marc Galland @mgalland


## Authors

A list of contributors to the lesson can be found in [AUTHORS](AUTHORS)

## Citation

To cite this lesson, please consult with [CITATION](CITATION)

[lesson-example]: https://carpentries.github.io/lesson-example

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/stijnvanhoey"><img src="https://avatars1.githubusercontent.com/u/754862?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Stijn Van Hoey</b></sub></a><br /><a href="https://github.com/carpentries-incubator/open-science-with-r/pulls?q=is%3Apr+reviewed-by%3Astijnvanhoey" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/rtherezan"><img src="https://avatars.githubusercontent.com/u/60100308?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Rodrigo</b></sub></a><br /><a href="https://github.com/carpentries-incubator/open-science-with-r/pulls?q=is%3Apr+reviewed-by%3Artherezan" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/azancarini"><img src="https://avatars.githubusercontent.com/u/22880040?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Anouk Zancarini</b></sub></a><br /><a href="https://github.com/carpentries-incubator/open-science-with-r/pulls?q=is%3Apr+reviewed-by%3Aazancarini" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/tijsbliek"><img src="https://avatars.githubusercontent.com/u/29064949?v=4?s=100" width="100px;" alt=""/><br /><sub><b>tijs bliek</b></sub></a><br /><a href="https://github.com/carpentries-incubator/open-science-with-r/pulls?q=is%3Apr+reviewed-by%3Atijsbliek" title="Reviewed Pull Requests">👀</a> <a href="https://github.com/carpentries-incubator/open-science-with-r/commits?author=tijsbliek" title="Tests">⚠️</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
