# Development Time Log ⏰

**2025-03-17**

| Date       | Time       | Hours Spent | Task Description                               |
|------------|------------|-------------|------------------------------------------------|
| 2025-03-17 | 07:21-8:50 | 1.25 (15min. pause) | 🪽 Pop-up development: Implemented main saving mechanisms and checks. Closed automatic functionality. Pushed code, pending CSS adjustments.|
| 2025-03-17 | 10:00-11:00 | 1 | 🧠 Test, brainstorming, bug fixing on CSS quick options pop-up and **child combinator (>)** on CSS header buttons controls. |
| 2025-03-17 | 12:20-13:45 | 1.25 (2x5 min. pause) | 🎨 Restored **CSS area pop-up**, bug fixing on **dark theme**, cleaned old codes, restored listeners for adding new area, mounted **new button area to open pop-up.** |
| 2025-03-17 | 20:30-21:30 | 1 | 🔄 Restored quantum-delete area and localstorage area, restored and implemented generic pop-up service, created new web component quantum-delete, split headers in area. |

**2025-03-14**

| Date       | Time       | Hours Spent | Task Description                               |
|------------|------------|-------------|------------------------------------------------|
| 2025-03-14 | 08:30-13:30 | 5 (1.5h pause) | 🪽 **Major refactoring & debugging**: Restored `activity-editor`, rewrote **drag & drop logic**, fixed `undo activity` listener handling. Improved **event binding** for external component functions. Investigated missing **CSS for activity-tracker**, adjusted `editors.css` into a service-based structure. Committed & pushed **18 files** (4696+ insertions, 1880- deletions), ensuring initial list load & settings visibility. Next: CSS fixes & pop-up integration. 🪽 |
| 2025-03-14 | 15:40-16:00 | 0.33 | 🪽 Final touch-ups: Fixed CSS issues in activity-tracker, improved styling for responsiveness, adjusted layout elements. Conducted a quick review of the pop-up integration. 🧐 |
| 2025-03-14 | 16:00-16:30 | 0.5 | 🪽 Restored CSS for `activity-editor` and fixed **dragging class** with `!important`. Pushed **7 files**. 🧐 |
| 2025-03-14 | 17:10-17:40 | 0.5 | 🪽 Fixed `activity-container` layout in `activity-tracker.css`. 🧐 |
| 2025-03-14 | 17:40-18:10 | 0.5 | 🪽 Fixed init list items and fixed text color item on dark theme. 🧐 |
| 2025-03-14 | 18:50-19:50 | 1 | 🪽 Fixed bug in CSS dark theme for activity tracker item, 🪶 Translated drag-drop.component.js, 🚧 Added first part of migration for "add new activity" with external listeners controllers 🔧  🧐 |

**2025-03-13**

| Date       | Time       | Hours Spent | Task Description                               |
|------------|------------|-------------|------------------------------------------------|
| 2025-03-13 | 09:30-11:00 | 1.5         | 🔧 Added `loadArea` services, `areasData` model, `svgIcon` models, `quantum-delete` service, joined `loadArea` with `quantum menu`, updated `generatorComponents`. |
| 2025-03-13 | 11:00-11:30 | 0.5         | 🛠️ Restored ` initAll ` on dashboard-page of AreaServices and added URL endpoints routes manager for areas and dashboard components.🪽  **We are flying right now, soon you'll enjoy the view!** 🪽 |
| 2025-03-13 | 17:00-18:30 | 1.5         | 🛠️ Migrated and fixed the header area with the quantum menu and activity editor, improving the overall layout and style. 🪽|
| 2025-03-13 | 19:30-20:45 | 1.5 | 🛠️ Initiated the first migration of ` activity-editor `, restructuring it into modular components and planning a step-by-step **refactoring strategy**. 🪽 |

**2025-03-12**

| Date       | Time       | Hours Spent | Task Description                               |
|------------|------------|-------------|------------------------------------------------|
| 2025-03-12 | 12:00-14:00 | 2           | 🔥 After many days of brainstorming, failed attempts, and multiple revisions, adjusted **theme.service.js**, merged **quantum menu**, and reworked CSS. |
| 2025-03-12 | 16:00-18:00 | 2           | ⚡ Optimized theme, connected it with **localStorage**, and finalized integration with the **login system**. |

**2025-03-05**

| Date       | Time       | Hours Spent | Task Description                               |
|------------|------------|-------------|------------------------------------------------|
| 2025-03-05 | 08:30-9:30 | 1           | ☀️ **Finally, the sun and spring are back, sorry for the delay!** Fixed: login issues and improved session handling. |
| 2025-03-05 | 12:30-13:30 | 1          | ☀️ Configured Webpack for better bundling and module resolution. |
| 2025-03-05 | 16:00-17:00 | 1          | ☀️ Completed batch script for component generation, ensuring folder and file naming consistency. |

**2025-02-26**  

| Date       | Time       | Hours Spent | Task Description                               |
|-----------|-----------|-------------|-----------------------------------------------|
| 2025-02-26 | 13:00-13:45 | 0.75        | 🚀 💪 **Phase 2 "Migration" from Scala PlayFramework Views to Vanilla.js** for Vercel in a "component-based" structure **similar** to Angular or React.js. Added `index.css` for dashboard, `effects.css` for input search area, and `area-pop-up.html` for pop-up area (formerly a Scala view). Reviewed dashboard init logic and refactored login page component initialization in `login.js`. |
| 2025-02-26 | 11:30-13:00 | 1.5         | Added routing system with Vercel and Node.js server: Implemented server-side routing for better scalability and improved deployment workflow. |
| 2025-02-26 | 10:00-10:30 | 0.5         | Bug fixing on login body (CSS/JS): Fixed layout inconsistencies and improved responsiveness for better user experience. |

**2025-02-25**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | ------------------------------------------------------------------------------- |
| 2025-02-25 | 20:30-23:30 | 3           | Implementation of the login → dashboard cycle with authentication and theme management: Since we are not using JS frameworks, we manually handled authentication control (via `localStorage`) and user theme restoration. We tested and pushed everything to **Vercel**, verifying client-side functionality. Some delays occurred due to manually managing the flow without state management libraries. |
| 2025-02-25 | 16:30-19:30 | 3           | Documentation update and migration of API Gateway and CORS management: Spent time refining the documentation to improve understanding and management of APIs and CORS configuration. This phase is crucial for better integration between components, ensuring the system works correctly in production environments and reducing potential long-term errors. |
| 2025-02-25 | 08:00-14:30 | 6.5         | Start of migration from Scala to Vanilla.js and Webpack: Began migrating from Scala to Vanilla.js to simplify the workflow, reduce complexity, and improve performance. Webpack integration was key for optimizing the build process and resource management. |

**2025-02-24**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | ----------------------------------------------------------------------------- |
| 2025-02-24 | 09:30-13.30 | 4.0         | Release on vercel and file organization. |
| 2025-02-24 | 16:00-20.00 | 4.0         | Release on vercel and file organization. |

**From 2025-01-27 to 2025-02-23**

| Summary | 10 working days | CRUD areas part 1, new pop-up, reverse engineering, quantum menu extension, brainstorming |

**2025-01-26**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | ----------------------------------------------------------------------------- |
| 2025-01-26 | 16:30-18:00 | 1.5         | Implemented quantum submenu, testing, reorganized code, and added new JavaScript helpers for language and theme change functionality. Documented updates and added comments. |
| 2025-01-26 | 19:15-22:15 | 3.0         | Implemented submenu updates, more testing, further code reorganization, and connected new JavaScript helpers for language switching and theme toggling. Updated documentation and comments. |

**2025-01-25**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | ----------------------------------------------------------------------------- |
| 2025-01-25 | 14:30-16:30 | 2.0         | Implemented quantum submenu, testing, code restructuring, and initial documentation updates. |

**2025-01-24**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | ----------------------------------------------------------------------------- |
| 2025-01-24 | 14:30-16:30 | 2.0         | Implemented login/logout page in Scala: CSS, control, tests, and documentation updates. |
| 2025-01-24 | 19:30-21:30 | 2.0         | Finalized login/logout page with dark-light theme toggle: CSS, JS updates.     |

**2025-01-23**

| Date       | Time        | Hours Spent | Task Description                                   |
| ---------- | ----------- | ----------- | ------------------------------------------------ |
| 2025-01-23 | 18:30-20:30 | 2.0         | Brainstorming and attempts to design the login.  |

**2025-01-21**

| Date       | Time        | Hours Spent | Task Description                                                              |
| ---------- | ----------- | ----------- | ---------------------------------------------------------------------------- |
| 2025-01-21 | 12:45-13:15 | 0.5         | 📦 Migrated documents to `scala-plan-ai-demo` repository + brainstorming roadmap. |

**2025-01-20**

| Date       | Time        | Hours Spent | Task Description                                                              |
| ---------- | ----------- | ----------- | ---------------------------------------------------------------------------- |
| 2025-01-20 | 18:30-20:30 | 2           | 📝 Writing report.                                                           |

**2025-01-17**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | -------------------------------------------------------------------------------- |
| 2025-01-17 | 18:30-20:00 | 1.5         | 💪 Bug fix and creation of merged array save functionality, with JavaScript destructuring. 🚀 |

**2025-01-06**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | -------------------------------------------------------------------------------- |
| 2025-01-06 | 12:30-13:50 | 1.3         | 🧦 Organizing technical documentation and brainstorming. 🧹                      |
| 2025-01-06 | 18:00-19:30 | 1.5         | 🧦 Fix: Bug fix on YAML save functionality, improved file handling and folder creation 🧹                      |

**2025-01-05**

| Date       | Time        | Hours Spent | Task Description                                                                 |
| ---------- | ----------- | ----------- | -------------------------------------------------------------------------------- |
| 2025-01-05 | 10:40-11:47 | 1           | 🧹 Reorganized code, reverse engineering, improved layout, and brainstorming done.  |
| 2025-01-05 | 12:50-13:53 | 1           | 🧹 Brainstorming and organizing technical documentation for the new layout of the menu and activity editor. |
| 2025-01-05 | 14.30-15.30 | 1           | 🧹 New quantum menu. |
| 2025-01-05 | 18.30-21.30 | 3           | 🧹 Refactor code & comments, added dark-light theme, new quantum menu, implemented undo button for completed activities restore. |

**2025-01-04**

| Date       | Time        | Hours Spent | Task Description                                        |
| ---------- | ----------- | ----------- | ------------------------------------------------------- |
| 2025-01-04 | 11:30-14:00 | 2.5         | 🍾 Bug fixes on editors, improved drag and drop functionality, enhanced layout. Conducted brainstorming for future improvements. |
| 2025-01-04 | 15:45-18:15 | 2.5         | 🥂 Installed Metals v1.4.2, Palladium for Visual Studio Code, and HTML Play in VS Code. Updated settings: changed `settings.json` to associate `.scala.html` and `.scala.js` with Scala. Completed bug fixing on editors, improved drag and drop, enhanced layout, organized code, translated UI parts, and reverse engineered tasks. Updated `read.me` documentation. |
| 2025-01-04 | 19:30-00:30 | 5.0         | 🍾 Completed Activities Tracker - Created a container for completed tasks via drag and drop transfer, updated counters, brainstorming, and layout. Reorganized Git files and updated documentation. 🥂 |

**2024-12-28**

| Date       | Time        | Hours Spent | Task Description                                        |
| ---------- | ----------- | ----------- | ------------------------------------------------------- |
| 2024-12-28 | 11:00-12:00 | 1.0         | Layout updated, bug fixes, selector improvements, parameter passing, activity table layout, dynamic JS data loading, quick options callback. |
| 2024-12-28 | 12:50-13:30 | 0.6         | Layout updates, bug fixes, selector improvements, parameter passing, activity table layout, dynamic JS data loading, quick options callback. |
| 2024-12-28 | 15:30-18:50 | 3.2         | Layout updates, bug fixes, selector improvements, parameter passing, activity table layout, dynamic JS data loading, quick options callback. |

**2024-12-27**

| Date       | Time        | Hours Spent | Task Description                                        |
| ---------- | ----------- | ----------- | ------------------------------------------------------- |
| 2024-12-27 | 10:10-14:10 | 4           | Bug fix and improvements on add/edit activity items     |
| 2024-12-27 | 16:30-19:30 | 3           | Bug fix and improvements on add/edit activity items + improved pop-up look and feel + added priority/status selectors + fixed data flow during edit + improved drag and drop |
| 2024-12-27 | 19:30-20:00 | 0.5         | Documentation update and file reorganization (removed old files) |

**2024-12-26**

| Date       | Time        | Hours Spent | Task Description                                        |
| ---------- | ----------- | ----------- | ------------------------------------------------------- |
| 2024-12-26 | 15:20-17:20 | 2           | Bug fix and improvements on add/edit activity items + improved file saving + brainstorming 🎄 |
| 2024-12-26 | 18:45-20:45 | 2           | Bug fix and improvements on add/edit activity items + improved pop-up + brainstorming 🎄 |

**2024-12-25**

| Date       | Time        | Hours Spent | Task Description                                        |
| ---------- | ----------- | ----------- | ------------------------------------------------------- |
| 2024-12-25 | 16:45-21:45 | 5           | Intensive development session on Christmas Day: conducted research on YAML standards (RFC 9512), attempted configuration optimizations for new task-saving features, brainstormed improvements to folder management (focused on "Current"), tested visualizer integrations, and installed necessary dependencies. Explored potential enhancements for CRUD operations and micro-scheduling functionalities. 🎄 |

**2024-12-24**  

| Date       | Time        | Hours Spent | Task Description                                        |
| ---------- | ----------- | ----------- | ------------------------------------------------------- |
| 2024-12-24 | 13:55-17:55 | 4           | Significant development work during Christmas Eve: modified controllers, added CSS for UI enhancements, updated documentation, and implemented new log views (both past and future) with interactive visualizers. Additionally, ensured proper folder creation if they didn’t exist, maintaining smooth functionality for users. 🎄 |

**2024-12-23**

| Date       | Time        | Hours Spent | Task Description                                        |
| ---------- | ----------- | ----------- | ------------------------------------------------------- |
| 2024-12-23 | 10:00-10:20 | 0.3         | Updated saveToYAML to optimize structure and Readme    |

**2024-12-22**

| Date       | Time       | Hours Spent | Task Description                                                                                                                                                                                       |
|------------|------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2024-12-22 | 12:00-14:00| 2.0         | Adjusted code structure, separated files, improved layout, added Save Button functionality to save activities in YAML format, and wrote documentation. Good Sunday to all! 😊 |

**2024-12-21**

| Date       | Time       | Hours Spent | Task Description                                                                                                                                                                                       |
|------------|------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2024-12-21 | 09:40-14:10| 4.5         | Added support for CRUD (Create, Read, Update, Delete) functions in task management. Implemented 3 new buttons for smart sorting: one for standard time sorting, one for distributing tasks throughout the workday (9:00 AM - 11:00 PM), and one for splitting them into 15-minute blocks. Created a menu for navigating tasks and their sorting. Also implemented intelligent movement of items between rows, adjusting their position based on priority and temporal distribution. Added two buttons that, when clicked, reorganize tasks into 16-hour time blocks (from 9:00 AM to 11:00 PM) and distribute tasks into 15-minute intervals. When the user clicks one of these buttons, a "toast" appears, which is a temporary, non-intrusive notification that confirms the action was successfully completed. The "toast" is a small notification that appears on the screen to inform the user of an event without disrupting the user interface. |
| 2024-12-21 | 14:20-14:40| 0.5         | Updated technical documentation in the README file on GitHub and uploaded the latest modifications to the repository.                                                                                  |  

**2024-12-20**

| Date       | Time       | Hours Spent | Task Description                                                                                                                                                                          |
|------------|------------|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2024-12-20 | 09:00-10:30| 1.5         | Review of all tasks completed yesterday, team meeting in Scrum/Agile mode with ChatGPT 4, HR meetings, and day organization.                                                               |
| 2024-12-20 | 15:15-16:45| 1.5         | Improved the current log page, added dynamic popup to allow users to add a new task to the to-do list with JavaScript and CSS.                                                             |

**2024-12-19**

| Date       | Time  | Hours Spent | Task Description                                                                                                                                                                       |
|------------|-------|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2024-12-19 | 14:30 | 1           | Brainstorming ideas to solve life and task organization problems.                                                                                                                      |
| 2024-12-19 | 16:30 | 1           | Installed Scala and completed the first theoretical lesson and "Hello World."                                                                                                          |
| 2024-12-19 | 17:30 | 1           | First theoretical lesson on Scala and creating a "Hello, Scala!" program.                                                                                                               |
| 2024-12-19 | 18:30 | 1           | Started the project `scala-plan-ai`: Set up Play Framework, routes, controllers, views, and added the "About" page with a festive fireplace image using ChatGPT's assistance (DALL-E). |
| 2024-12-19 | 21:30 | 1           | Released the project on GitHub, organized repository files, and logged work hours.                                                                                                     |
