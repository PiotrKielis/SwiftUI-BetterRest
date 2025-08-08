BetterRest is a SwiftUI application that helps you determine the ideal time to go to bed based on your desired wake-up time, amount of sleep, and daily coffee intake.
It uses Core ML and a trained machine learning model to make accurate predictions, ensuring you get the most restful sleep possible.
Features
Wake-up time selection – Choose when you want to wake up using a clean, simple DatePicker.
Sleep amount control – Set your desired hours of sleep with a Stepper for fine-tuning.
Coffee intake tracking – Select how many cups of coffee you drink per day.
Smart bedtime calculation – Uses a Core ML model (SleepCalculator.mlmodel) to suggest the optimal time to go to bed.
Beautiful gradient background – A warm orange-to-black gradient for an aesthetically pleasing look.
SwiftUI Navigation – Smooth, modern interface with NavigationStack and alerts.
How it works
You input your wake-up time, desired sleep hours, and coffee consumption.
The app passes these values to the Core ML SleepCalculator model.
The model predicts the amount of actual sleep you’ll need based on your inputs.
The app calculates your ideal bedtime and presents it in a friendly alert.

Technologies Used
SwiftUI for the UI and layout.
Core ML for the sleep prediction model.
NavigationStack for modern navigation.
LinearGradient for the background design.


Requirements
iOS 16.0+
Xcode 14+
SleepCalculator.mlmodel included in the project.

<img width="357" height="698" alt="Zrzut ekranu 2025-08-8 o 18 40 07" src="https://github.com/user-attachments/assets/ef291b9d-2a46-43a8-b73c-aaaff098c11b" />
<img width="347" height="697" alt="Zrzut ekranu 2025-08-8 o 18 40 22" src="https://github.com/user-attachments/assets/a7757b97-288d-4428-bc14-734dad8371d3" />
