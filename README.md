# Motivation:

Thanks for interviewing at Stripe. At Stripe, our interview process has some interviews where you
write code, typically on your laptop. To make sure that we can use our time best in the interviews,
we'd like to have you do some setup on your laptop in advance.

First, clone or download this repository to your computer via the links on the right
(creating a fork of the repository is not necessary).

We've created a (rather ad-hoc) gradle project to help candidates
determine if their laptops were setup to write Kotlin, so interviews can
be about evaluating the candidate, and not the way their environment is
setup.

## Using Android Studio

To open the project in Android Studio:
- Make sure you have Android Studio v3.6 or later installed on your computer
- Select `File > Open...` from the menu.
- Select `Trust project`
- Select `File > Sync project with gradle files`
- Ensure that you have an emulator running Android 9 (API level 28) set up:
    https://developer.android.com/studio/run/emulator
- Run the `app` target on your locally configured Android emulator

## Using IntelliJ IDEA

To open the project in IntelliJ IDEA:

- Ensure the bundled "Kotlin" & "Gradle" plugins are enabled.
- Select `File > New > Project from Existing Sources...` from the menu.
- Navigate in the file selector to the root directory of this repository.
- Ensure "Import project from external model" and "Gradle" are selected, click Finish.

A new window should then appear with the project.
