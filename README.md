# Tip Calculator 

## *Thomas Hsieh*

**Tippy** computes the tip and total amount for a bill. The app uses the base amount and tip percentage to calculate the amount owed, and it also describes the quality of service based on the tip.

Time spent: **2.5** hours spent in total

## Functionality 

The following **required** functionality is completed:

* [X] User can enter in a bill amount (total amount to tip on)
* [X] User can enter a tip percentage (what % the user wants to tip).
* [X] The tip and total amount are updated immediately when any of the inputs changes.
* [X] The user sees a label or color update based on the tip amount. 

The following **extensions** are implemented:

* [X] Custom colors palette selected
* [X] Replace the text describing the tip (“poor”, “good”, etc) with emojis.
* [X] Add the ability to split the bill across any number of people.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://im7.ezgif.com/tmp/ezgif-7-5689e01eb89e.gif' width='' alt='Video Walkthrough' />

GIF created with [EZGif](https://ezgif.com/).

## Notes

When implementing the split bill by number of people, the app would crash if there were no bill/tip. Similar to updating the tip amount, I had to add checks to only update when there was actually a number value for meal cost and tip amount.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
