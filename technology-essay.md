About the technologies I’ve used, for the most part, I’ve used native libraries shipped with Xcode, with SpriteKit, UIKit and PlaygroundSupport being the major ones.
SpriteKit is used in the page called 'Left' and helps visualize the process of charging a capacitor. I also used Xcode’s SpriteKit tool to design the environment of the capacitor. I must admit, I didn’t know anything about SpriteKit until taking on this challenge, hence might I have solved some parts of the code in a less 'idiomatic' manner, but the learning curve has been quite drastic nonetheless and was undoubtedly very entertaining as well.
UIKit plays a major roles in the live view of the introduction. Since I wanted to create a kind of iOS-app like experience to measure and change values, UIKit was the go to library. UIKit is also essential for the self-coded function plotter which is integrated in the iOS simulation. This app, I've sadly couldn't manage to finish in time, thus, I have implemented an alternative that uses the Playgrounds capabilities.
PlaygroundSupport was key to embed my visualizations and ViewController into the playground’s live views, but also to enable features such as the Timer to work (see Introduction).
A minor library in use is Darwin, which solely serves the purpose to ship the 'pow’”-function in order to write the function that lets one calculate the capacitor’s voltage in the charging process. It is used in the code of the page called 'Left'.
It was my goal to not use ‘non-native’ libraries, hence have I also created my own function plotter. Ultimately, I believe that this way, I do also have more possibilities to manipulate my code.
