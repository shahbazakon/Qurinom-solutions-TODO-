# Qurinom Solutions DoneIt 📝



[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](/https://github.com/shubham-chhimpa/done_it/LICENSE.md)
![Github Followers](https://img.shields.io/github/followers/shubham-chhimpa?label=Follow&style=social)
![GitHub stars](https://img.shields.io/github/stars/shubham-chhimpa/done_it?style=social)
![GitHub forks](https://img.shields.io/github/forks/shubham-chhimpa/done_it?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/shubham-chhimpa/done_it?style=social)
![Twitter Follow](https://img.shields.io/twitter/follow/shubham_chhimpa?label=Follow&style=social)


## About

It simply loads **Notes** data from in memory database. Notes will be always loaded from in memor database.

- This makes it offline capable 😃.
- Clean and Simple Material UI.
- It supports dark theme too 🌗.

## Directory Structure

    .
    ├── core                       # For all common and core files.
    │   ├── error                  # contains all Exceptions and Failures classes
    │   ├── presentation           # common presentation files
    |   │   └── blocs              # common blocs
    |   │   └── pages              # core pages
    |   │   └── widgets            # common widgets
    │   └── route                  # Routes for navigation
    │   └── theme                  # Theme data
    │   └── usecases               # common usecases
    |
    ├── feature                    # all features
        ├── feature1               # Feature 1 (for exp : Todo Feature)
            ├── data               # Data Files of Feature 1
            ├   └── datasources    # DataSources Abstract Files and Implementations
            ├   └── models         # Models for data
            ├   └── repositories   # Repositories Implementation Classes
            └── domain             # Domain
            ├   └── entities       # Entities For Feature 1
            ├   └── usecases       # Usecases of Feature 1
            ├   └── repositories   #   Repositories Abstract Classes
            ├── presentation       # Feature 1 presentation files
            │   └── blocs          # Feature 1 blocs
            │   └── pages          # Feature 1 pages
            │   └── widgets        # Feature 1 widgets

