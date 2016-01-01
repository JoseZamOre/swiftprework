# Pre-work - TipperBook

TipperBook is a tip calculator application for iOS.

Submitted by: Jose Zamora Orellana

Time spent: 13 hours spent in total

## User Stories *If the program were to work, the following would have been implemented*

The following **required** functionality is complete:
* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [ ] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Splits up the tip total for up to 5 people.

## Notes

Though the given program does not operate, there have been many difficulties to make the program work again. My primary issue came about when I was trying to make the Settings window. I kept seeing this error on thefollowing line:
class AppDelegate: UIResponder, UIApplicationDelegate {
After some research, I have discovered the problem (Thread 1: signal SIGABRT) and how to fix it. Though it seems that I could not pinpoint where there was a disconnection in my "ViewController". I attempted to recreate the program from scratch but came across SIGABRT again, for an unknown reason. When I had checked back to my original program, it suddenly had stopped working.

## License

    Copyright 2015 Jose Zamora Orellana

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
