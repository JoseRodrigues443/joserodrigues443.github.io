---
title: 'Your codebase should not depend on an IDE'
subtitle: 'These will save your team so mutch trouble :package:'
summary: Your codebase should not depend on an IDE :package:.
authors:
- admin
tags:
- IDE
- programing
- blog
categories:
- Tooling
date: "2023-02-28T00:00:00Z"
lastmod: "2022-02-28T00:00:00Z"
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  caption: ""
  focal_point: ""
  preview_only: false
  placement: 3

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#   projects: ["blogger-ipfs"]

---

# Introduction

A codebase should be developed to be IDE-agnostic, meaning it should not rely on or depend on features of a specific integrated development environment (IDE). While IDEs provide useful tools and shortcuts for developers, a codebase should be able to be worked on using any text editor.
Developing an IDE-agnostic codebase provides more flexibility, control, and freedom for you and other developers. However, it requires forethought and discipline to avoid locking yourself into a particular IDE. Here are some tips for keeping your codebase portable across IDEs and text editors.

# Use plain text files

Store your code in simple, human-readable plain text files, not proprietary formats tied to an IDE. Using standard text files in formats like .txt, .java, .py, etc. allows the code to be opened and edited in any text editor and prevents lock-in to a particular IDE.

# Avoid IDE-specific features

Do not use special features that are specific to a particular IDE. For example, do not use IDE-specific keyboard shortcuts, code snippets, or templates. Do not create IDE-specific project files or folder structures. While these features may be convenient, they will not work outside of that IDE.

# Build and test from the command line

You should be able to build, compile, test, and run your code from the command line, without needing an IDE. Define your build process using a tool like Make, Maven, or Gradle and create a command-line interface. This ensures your code can be built anywhere, not just in an IDE.

# Use plain text for configuration

Use plain text files for any configuration, rather than IDE-specific config files. For example, use .gitignore files for source control rather than IDE-specific git options. Use plain text .env files rather than IDE-specific environment config.

# Conclusion

While IDEs offer useful features for developers, a codebase should not rely on or depend on an IDE. By using standard text files, avoiding IDE-specific features, enabling command-line building and testing, and using plain text for configuration, you can ensure your codebase is portable and IDE-agnostic. This flexibility provides more freedom and control for you and any other developers working on the code. Keeping your codebase IDE-agnostic may require more discipline, but the benefits to your productivity and autonomy as a developer are worth it.

## License

Copyright 2016-present [Miguel Rodrigues](https://joserodrigues443.github.io).

Released under the [GPL 3](https://github.com/JoseRodrigues443/joserodrigues443.github.io/blob/master/LICENSE) license.
