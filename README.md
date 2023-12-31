![Foundation Logo](https://github.com/FlineDev/Foundation/blob/main/Logo.png?raw=true)

# Foundation

This framework mainly consists of the files [AppFoundation.swift](https://github.com/FlineDev/Foundation/blob/main/Sources/AppFoundation/AppFoundation.swift) and  [TestFoundation.swift](https://github.com/FlineDev/Foundation/blob/main/Sources/TestFoundation/TestFoundation.swift) which contain just a collection of `@_exported import` statements of frameworks I use in every new app.

## Usage

Just add `https://github.com/FlineDev/Foundation.git` as a Swift package, referencing the `main` branch and let Xcode load all commonly used dependencies.

![Package Mapping in Xcode](https://github.com/FlineDev/Foundation/blob/main/Images/PackageMappingInXcode.png?raw=true)

Then, simply import `AppFoundation` or `TestFoundation` in your app or test targets Swift files and you no longer need to import `Foundation`, `SwiftUI`, `SwiftData`, `OSLog`, and a couple of other frameworks to eliminate the need for repeated imports. This serves a very similar purpose like the `import Foundation` Apple adds to every new Swift file by default, which is why I named this after that.

You are free to reference this framework as-is in your app, but note that I tend to use the latest Swift tools version at all times and that I might be adding or replacing frameworks over time without notice. So you might prefer to fork it and adjust it to your needs instead. That's mostly why I made this public.

## License

This library itself is released under the MIT License. See LICENSE for details.
For the licenses of the imported libraries, see their own LICENSE files. But I only use open-source libraries with a comparable LICENSE.
