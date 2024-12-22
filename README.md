# CS-360

• Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The purpose of the app I developed was to help users along with their weight loss journey by tracking their weight loss records in a collected, intuitive manner.

• What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app featured a login screen to verify the user's credentials, a screen to create a new account, and then a main screen that allows the user to add a goal and submit their daily weight.

• How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
The first step was to document and create diagrams of what I was expecting the application to look like. From here, I created a UI with all the required features. This served as a working template for the backend code. Starting with the login screen, I coded each activity one at a time, allowing for each activity to be tested before working on the next. This ensured the application was bug-free and kept me focused on what needed to be added.

• How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
I made it a point to test as I worked through developing the backend of the application. If I hadn’t developed this modularly, then when first trying to start the application, there would have been more problems than I could handle, making it really hard to backtrack and fix the bugs.

• Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
One place I innovated was using the system resources module to store the goal weight in a buffer, making it so the application could first check if there was an existing, recent weight goal in the database for that user. If there wasn’t, the application would check the buffer. If the buffer was set to zero, the application would then make the user set a goal before adding the daily weight. This ensured that a goal was set and also made it so the user wouldn’t have to set a goal each time they logged into the application.

• In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
Using SQLite was interesting. It would have been better to have an assignment working with SQLite over the sensor module, but I was able to create a schema that handled all of my needs.
