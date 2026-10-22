# CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The goal was to provide an app that could be used in a warehouse setting to track inventory. It was designed to address the needs of several user types, such as a worker that ships and receives items and needs to update quantities, a manager that is responsible for managing what items are part of the database and ordering items with low inventory, and potentially even a higher-level executive that would need to monitor inventory levels.
The requirements of this app were a functioning inventory tracker with the following features:
  - User login and account creation
  - Ability to add, delete, and edit items, including quantity
  - A database for housing the app information with two tables:
      - An inventory table to manage the items
      - A user table to manage user accounts
  - SMS capability to notify users of depleted inventory items

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app needed several screens to meet the different users' needs. These included:
  - A login screen to access the app
  - A screen for new account creation
  - A screen with a grid for displaying inventory items
  - A settings screen to enable or disable SMS messaging
  - A screen that would show item details and allow for quantity adjustments
  - A screen for editing an item's details or deleting the selected item (this screen also served as the new item entry screen, just with the delete button disabled)
My designs kept the user needs in mind by providing a layout that should be familiar to most app users, such as a text link to create a new account, a three dots menu in the action bar of the main screen, and an easily accessible floating action button for quick item creation. Also, the intuitiveness of tapping an item to view its details and make changes should be familiar to most mobile device users.
These designs were successful because they employed common functionality that mobile users would pick up on quickly, making for a user-friendly experience.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
Unfortunately, my strategies for this project were haphazard at best. Aside from following the progression of the projects (proposal, layout design, code development), I generally let my panic and stress guide my actions. This led to me jumping around the app randomly, making changes without testing them, and trying to fix "bugs" that might not even be exist yet. In the future, I will set aside these poor techniques and employ a more methodical, incremental approach to ensure each component works on its own before trying to integrate them together.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
Again, my testing approach was not ideal. I would try (and fail) many times just to launch the app, making seemingly random changes after each failed attempt. After some time, I was able to calm my mind a bit and work towards testing one part at a time, such as ensuring that adding a new item worked as expected with the correct page flow and database updates. Following an incremental approach to testing is vital to solid app development as it shortens the time it takes to find and fix bugs, thus speeding up the overall app development. For me, it revealed that I have a lot to learn about how to manage a development project, and that taking time to focus on one thing at a time will produce a much better product.

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
Throughout the entire project, one challenge I faced over and over was the IDE informing me of outdated styles and deprecated functions. This was due to following older examples from the textbook. The Android OS is continually evolving and updating to provide new functionality and improve existing features. Therefore, I often found myself reaching for the most up-to-date documentation to learn how to code a more effective app.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
One area I think I did well was repurposing the add item screen to also work as the edit item screen. I was able to take the context from which the user accesses the screen to determine if the fields should be blank or populated, and if the delete button should be shown. This not only let me skip creating an extra fragment, but also improved the maintenance aspect by consolidating resources to reduce the areas that may need to be updated in the future. For example, if an extra field like the item's manufacturer were added later, there would only be one fragment and java file that would be updated instead of two. This reduces the likelihood of bugs and coding errors.
