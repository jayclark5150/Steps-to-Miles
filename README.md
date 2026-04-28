# Steps-to-Miles
A simple iOS shortcut to convert steps to miles
This is a clean and simple conversion tool. Here is a professional `README.md` file for your **Step To Miles** shortcut, formatted without icons.

---

```markdown
# Step To Miles

This iOS Shortcut calculates the distance traveled in miles based on a user's specific step length and total step count. Unlike standard trackers that use a generic average, this tool allows for personalized precision by accounting for individual stride lengths.

## Features

- Personalized Stride Input: Allows users to input their specific step length in inches.
- Accurate Conversion: Uses the mathematical constant of 63,360 inches per mile for precise distance calculation.
- Clean Formatting: Automatically rounds the final distance to the nearest hundredth for easy reading.
- Instant Notification: Displays the final distance in a clear system alert.

## How It Works

The shortcut performs the following logic:

1. Stride Length: Prompts the user for the number of inches in one step (providing averages of 27 inches for women and 30 inches for men as a reference).
2. Step Count: Prompts the user for the total number of steps taken.
3. Calculation:
    - Multiplies Step Length by Step Count to get total inches.
    - Divides total inches by 63,360 (the number of inches in a mile).
4. Rounding: Rounds the resulting figure to two decimal places.
5. Result: Displays an alert stating: "You walked [Number] miles."

## Installation

1. Ensure the Shortcuts app is installed on your iPhone, iPad, or Mac.
2. Download the .shortcut file from this repository or use the provided iCloud share link.
3. If importing for the first time, you may need to allow "Private Sharing" or "Untrusted Shortcuts" in your device settings.

## Requirements

- iOS 15.0 or later / macOS Monterey or later.
- Shortcuts App.
```
