# swift-project-template
Cookiecutter template for an Swift iOS project.

![swift-project-template](img/example.png)

## Usage
1. Install [Cookiecutter](https://github.com/audreyr/cookiecutter) and [Carthage](https://github.com/Carthage/Carthage):
   
   `brew install cookiecutter carthage`
   
   We use Carthage as dependency manager by default.
    
2. Run `cookiecutter gh:artemnovichkov/swift-project-template`. No need to create project folder manually, cookiecutter does it for you.

For future runs you can shorten the command to `cookiecutter swift-project-template`. However, if you want to use the most recent template you should still run the full command above.

## Features:
* Xcode 8.0+ and Xcode 9.0 beta 6 (9M214v)
* AppCode support (checked in 2016.3.2 version)
* Swift 3.0+
* Custom project structure (the same in the project and on the disk)
* Custom scripts for [Carthage](https://github.com/Carthage/Carthage) and [SwiftLint](https://github.com/realm/SwiftLint)
* iOS Deployment Target - 9.0 (two major versions)
* Templates for Github pull requests
* Settings.bundle with app version
* Automatic code signing disabled (sorry, Apple 🤷‍♂️)
* Swift flags for [profiling compilation times](https://github.com/RobertGummesson/BuildTimeAnalyzer-for-Xcode)

## Author

Artem Novichkov, novichkoff93@gmail.com

## License

swift-project-template is available under the MIT license. See the LICENSE file for more info.
