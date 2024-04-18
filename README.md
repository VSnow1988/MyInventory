# MyInventory
Sample Android mobile application built in SNHU CS360, upgraded in CS499 Computer Science Capstone.

This repo contains the project files for Android Studio at each stage of development over the course.
The course/degree expectations are to show skill and understanding in collaboration, communication, algorithmic logic, tools and design innovation, and security.

## MyInventory_0
Original final project submitted in CS-360.
This is an app for Android, written in Java, which tracks a user's inventory using local data in a SQLite database. The assignment's original objectives were to begin learning to use the Android Studio IDE and the Android Java libraries. This project shows an understanding of mobile design concepts, basic IDE functions and code with a working login function, layout, displaying data, and CRUD functions.

## MyInventory_1
First enhancement made in CS499, focused on software design and development. The main upgrade here was a UX redesign. Accompanying diagrams and personas are in the 'Design Documents' zip folder.
Changes to the code include:
- Entirely new layouts for each view, including a Recycler View and related classes.
- Added comment documentation.
- Changed filenames and variable names to align with standards and be more intuitive to understand.
- Fixed a few bugs.
- Handled IDE warnings.

## MyInventory_2
Second enhancement made in CS499, focused on algorithms and data structures. The plan for this enhancement was to add validations, and review all functions' algorithmic logic for security and efficiency. Code changes include:
- Security validations for all input.
- Error handling and loop-closing.
- Handled more IDE warnings and bugs.
- TODO/FIXME Task lists created.
- Logging features added for debugging.
- Improved documentation and commenting.

## MyInventory_3
Third enhancement made in CS499, focused on databases. The plan for this enhancement was to transition the application to using a remote database and translate the tables into NoSQL for enhanced performance, security, and to allow the user to share access with others to the same inventory.
Code changes include:
- Bug fixes, warnings addressed, further improvements to documentation comments.
- Major upgrade to the project version and dependencies in order to use a remote database and current tools.
- Changes to deprecated code and no-longer supported or buggy Java libraries.
- Addition of a Google Firestore database, with related code tested and functional.
- The entire Login view and Users table is now handled by the Firestore database.
- Complete numbered TODO/FIXME task list outlines the plan for upgrades and testing to create the deliverable product.
  
### Using These Files

When attempting to load these files into Android Studio for viewing, editing, or emulation, there are many dependency and version issues that could arise. This project was built on Android Studio Flamingo originally and Iguana for the enhancements. It was successfully run during development with 'Pixel 3 API 33' for parts 0-2, and 'Pixel_3a_API_extension_level_7_x86_64' for part 3 and beyond. Emulators are often problematic or slow. It is ideal to use a development mobile device paired with the IDE if possible. If you come across the notorious 'Cannot find R.': Try Build - clean and rebuild, File - empty the cache and restart, or check Gradle version and known bugs. When all else fails, try importing the files individually into a new Android Studio project and altering for your project and development environment.

The database upgrade (MyInventory 3 and beyond) requires an emulator/device with Google Play enabled and a security/access file for the database.
This has not been included for obvious reasons. You can use your own from your own firebase account if using this as a base or learning project - it will need to be placed in the base app directory.
If you are a client, interviewer, or collaborator who would like to demo the project in an emulator yourself, I will provide you with security permissions.

### More Information
This repo is displayed in my Github Pages portfolio created for the CS 499 Capstone Project. Further details, code review and documentation of the process can be found on https://vsnow1988.github.io/


