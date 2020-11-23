# DubbizleAssigment

//
//  README.md
//  DubbizleAssigment
//
//  Created by Nadeem Akram on 23/11/20.
//  Copyright © 2020 Nadeem Akram. All rights reserved.
//

 1. Dubbizle Assignment
 Dubbizle Assignment by Nadeem Akram (nadeemakram2388@gmail.com)  from Prachi shah  (prachi.shah@bayut.com).


 2. Requirements
- [Xcode 12]
- [Fastlane](https://fastlane.tools)(Optional)

 3. Getting Start
- Open `DubbizleAssignment.xcodeproj` in Xcode 12
- Build the project

 4. Problem Statements
[Problem Statements](ReferanceDoc/iOS Project.pdf)

 5. Swift
This project is build using Swift 5.

 6. 3rd Party
- No third party library or Pods
​
​## 7. Unit and UI Test case
- ​Only one screen covered

​I'm not using any 3rd parting to mocking and stubs the objects. I build my own protocol based solution by creating fake `URLSession`.
​
​## 8. Architecture
​In this project, I'm using MVVM architecture without any Reactive 3rd party lib(like RxSwift etc.). For binding purposes, I'm using the custom binding class to bind properties and UI elements with ViewModels. 
​
​## 9. Memory Management
​![](ReferanceDoc/MemoryLeaks.png)
​​
​## 10. Fastlane 
​- `fastlane ios tests` - Runs all the tests
​- `fastlane build` - Run all the tests and build
