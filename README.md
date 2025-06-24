# Project Reflection
**1. Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**

The primary goal of the Inventory App is to provide users with a straightforward and accessible way to manage their personal or small business inventory directly from their mobile devices. The app meets user needs by allowing them to easily track items, quantities, and descriptions, all while featuring a user-friendly interface for adding, editing, and deleting inventory items. Additionally, the app provides real-time notifications, allowing users to activate SMS alerts for important inventory events, which enhances its utility and keeps them informed.

**2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**

To meet user needs, the app features a secure login screen, a dashboard that displays current inventory, screens for adding and editing items, a settings page for configuring SMS notifications and storing contact numbers, and confirmation dialogs for critical actions such as deletions. Each screen is designed for clarity and ease of use, featuring large touch targets, clear labels, and a consistent color theme that creates a welcoming and accessible user experience. Following Material Design guidelines ensure that navigation and actions are familiar and intuitive, contributing to the overall success of the user interface.

**3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?**

The coding process began with a focus on modularity and reusability. Activities and adapters were structured to separate concerns and maintain an organized codebase. I implemented Android best practices, such as using RecyclerView for the inventory list and CardView for visual grouping while leveraging XML for clear and maintainable layouts. SharedPreferences was utilized for storing settings. These strategies are widely applicable to future projects, as they enhance the ease of extending and debugging the code while also supporting better long-term maintainability.

**4. How did you test to ensure your code was functional? Why is this process important, and what did it reveal?**

Testing was conducted continuously throughout the development process, utilizing both manual interactions and edge-case scenarios. This included checking login credentials, adding, editing, and deleting items, toggling SMS settings, and managing permission dialogs. This iterative testing approach was crucial for identifying issues such as UI alignment problems, input validation failures, and bugs related to permission handling. Overall, testing ensures reliability and enhances the user experience by not only uncovering bugs but also identifying opportunities to improve usability and accessibility.

**5. Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?**

One major challenge was managing SMS permissions and integrating system-level notifications in a secure, user-friendly manner that complies with Android policies. This involved designing a separate permissions activity and providing clear user prompts, which required careful planning and iteration. Additionally, I introduced confirmation dialogs for actions that could lead to data loss, which not only reduced the risk of accidental data loss but also enhanced user trust and confidence.

**6. In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

The inventory management functionality demonstrates my skills in both UI design and backend logic, particularly through the seamless integration of RecyclerView with add/edit dialogs and confirmation prompts before deletion. Furthermore, the implementation of user-centered features, such as SMS notifications and customizable settings, showcases my commitment to accessibility and addressing real user needs.
