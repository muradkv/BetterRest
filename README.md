# BetterRest

![Swift](https://img.shields.io/badge/Swift-5.0+-FA7343?logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-18.0+-000000?logo=apple&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-15.0+-147EFB?logo=xcode&logoColor=white)
![Framework](https://img.shields.io/badge/Framework-SwiftUI-007AFF)
![CoreML](https://img.shields.io/badge/Tech-Core_ML-FF9500)

A smart sleep calculator app built natively for iOS, developed as **Project 4** of the 100 Days of SwiftUI course.

Instead of guessing when you should go to sleep, BetterRest uses Machine Learning to predict your ideal bedtime based on your desired wake-up time, sleep goal, and daily coffee intake. 

## Preview
<img width="25%" alt="Simulator Screenshot - iPhone 16 Plus - 2026-05-21 at 03 46 42" src="https://github.com/user-attachments/assets/771981e6-9e91-4ffc-8389-890000b849eb" />

## Features

* **Machine Learning Integration:** Powered by a custom Core ML model trained via Create ML (Tabular Regression) to accurately predict sleep patterns.
* **Dynamic UI Updates:** The recommended bedtime is calculated and updated on the fly using computed properties—no "Calculate" button required.
* **Native iOS Feel:** Built with a clean `Form` and `Section` layout that perfectly mimics native iOS settings.
* **Advanced Date Handling:** Uses `Calendar`, `DateComponents`, and modern SwiftUI `.formatted()` modifiers to seamlessly manipulate and display time.

## About the Project & Challenge

This application was built to fulfill **Project 4 (Days 26-28)** of the SwiftUI learning path created by Paul Hudson (Hacking with Swift). 

The core goal of this project was to introduce Machine Learning into iOS apps and master date mathematics. Key topics practiced and improved in this project include:
* **Core ML & Create ML:** Importing a `.mlmodel` file, creating an instance, and passing features (wake time, sleep amount, coffee) to get a prediction.
* **Date Mathematics:** Converting `Date` objects into seconds from midnight using `DateComponents`, and subtracting seconds from a `Date` to get a new time.
* **SwiftUI Controls:** Handling user input elegantly using `DatePicker`, `Stepper`, and `Picker` components inside a `Form`.
* **State-Driven UI:** Leveraging `@State` to instantly trigger UI redraws and calculate results dynamically.

🔗 **[Full project description here](https://www.hackingwithswift.com/100/swiftui/26)**
