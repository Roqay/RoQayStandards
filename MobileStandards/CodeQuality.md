# Code Quality

- Code must have comments to describe what it is doing not just general comments like services, home, data, ...etc.
- Any part of code that do check like status check or something must have a comment to describe each status and what it represents.

  > For example: If I have a status that will be `0` while pending, `1` while in progress and `2` while done, this must be explained in the comment before that status check not just checking the numbers without knowing what it represents.

  > It is preferred to use `enums` for that case as they are made for that purpose.

- Variable names must be representative of what data that variable hold.

  > For example: If I have a variable that holds the user data, it should be called `userData` not just `data`.

- Method names must be representative of what the method do.

  > For example: If I have a method that gets the user data, it should be called `getUserData` not just `getData`.

- It’s preferred to have a comment above each method to describe it, the parameters and the return type.
- Repeated code in same class should be extracted in method.
- Repeated code in different classes should be extracted in `utils` class.
- Repeated code styles in `Android` should be extracted as style in the `styles` file.
- Repeated UI components should be extracted to a component file and imported and used in rest of needed files.
- Apps must be connected to `Firebase` and implement `Firebase Crashlytics`.
- Stop using deprecated or unmaintained libraries.
- Useless/Commented code and imports should be removed.
- Try to write clean code as possible as you can.
- Try to separate parts of code as possible as you can.
- Try to write small methods that do single functionality.
- If you know a design pattern, don’t hesitate to use it if you fully understand it and how it works and help you.
