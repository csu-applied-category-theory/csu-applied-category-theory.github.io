---
title: Resources
nav: true
---

# (FA23) Getting Scala to run locally

Prerequisites: access to a terminal.

1. Install Java using <a href="https://www.oracle.com/java/technologies/downloads/#java17" target="_blank">this link</a> 
2. Install Scala 3 using <a href="https://www.scala-lang.org/download/" target="_blank">this link</a>
3. Install VSCode using <a href="https://code.visualstudio.com/download" target="_blank">this link</a>
4. Open VSCode, find the "Extensions" page (Code -> Preferences -> Extension) , and install the ["Metals"](https://scalameta.org/metals/docs/editors/vscode/)  extension on VScode.
5. Create a new file, hello.worksheet.sc, and type in `println ("Hello world!")` on line 1. Save and wait a bit, you should see `// Hello world` to the right of that line. You can now run Scala code locally!
6. (Optional - Importing existing Scala projects) Clone [this](https://github.com/scala/scala3-example-project) project using the command `git clone https://github.com/scala/scala3-example-project.git`. You may need to install `git`. Open the newly cloned directory on VSCode, import the build with `Metals: Import Build` command, and run `Main.scala`.

## Browser alternative with no installation
Use the online code editor at [https://scastie.scala-lang.org/](https://scastie.scala-lang.org/) - you will need to sign up for GitHub. You can save and share snippets, but will not be able to import other people's projects.



