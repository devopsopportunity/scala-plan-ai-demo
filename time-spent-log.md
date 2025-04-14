# Development Time Log ⏰

**2025-04-14**

| Date       | Time              | Hours Spent | Task Description                          |
|------------|-------------------|-------------|-------------------------------------------|
| 2025-04-14 | 7:30 - 10:30 | 3h | 🧠🧠🧠🧠 Final configuration approved + redirection of the weekend roadmap + full administrative logging. No code added, but high-level technical consultancy performed (strategic planning, JS agent demo logic, user tour orchestration). Prepared a simplified but meaningful demo path: tour-driven task creation, automatic relocation to completed section, agent-created data clean-up on exit. |
| 2025-04-14 | 11:15 - 11:45     | 0.5h        | ⚠️ Implemented control logic for the maximum number of activities: when the user exceeds 20 created areas, an informational popup is triggered, reusing the existing UI template. The system now gracefully handles edge cases, keeping the demo flow clean and intuitive. |
| 2025-04-14 | 12:00 - 14:20     | 2.3h        | 🧩 Designed and applied a custom CSS scrollbar to the dashboard panel, improving the UX by avoiding reliance on the browser’s default scrollbar. Smooth scrolling effects were added to ensure a more polished and professional feel. |

**2025-04-13**

| Date       | Time              | Hours Spent | Task Description                          |
|------------|-------------------|-------------|-------------------------------------------|
| 2025-04-13 | 9:30 - 12:30 | 3h | 🧠🧠🧠 Multiple attempts to integrate Shepherd.js with dynamic DOM injection + ESM import issues + incompatibilities with static HTML files. Debugged conflict between plugin initialization and disabled console.log. No visual progress but crucial groundwork laid for internal agent flow logic. |

**2025-04-12**

| Date       | Time              | Hours Spent | Task Description                          |
|------------|-------------------|-------------|-------------------------------------------|
| 2025-04-12 | 10:00 - 12:30 | 2.5h | 🧠 Initial debugging of Shepherd.js: first conflict with DOM not loading properly on modal trigger. Early design for JS agent-driven onboarding process. 🧠 |

**2025-04-11**  

| Date       | Time              | Hours Spent | Task Description                          |
|------------|-------------------|-------------|-------------------------------------------|
| 2025-04-11 | 7:30 - 18:30 | 11h (incl. 5.5h break) | 🧠 Systematic Shepherd.js integration testing + minimifier collision with Tensor plugin. Refactor attempts repeatedly blocked by ESM-related execution bugs. Documented anomalies in browser scope. |

**2025-04-10**  

| Date       | Time      | Hours Spent | Task Description                          |
|------------|-----------|-------------|-------------------------------------------|
| 2025-04-10 | 10:00 AM - 10:00 PM | 12h (incl. 4h break) | 🧠 Tutorial dev: pop-up **agents** (area/activity-editor), lock footers (core), Shepherd.js CSS/core refactoring 💯 |

**2025-04-09**

| Date       | Time      | Hours Spent | Task Description                          |
|------------|-----------|-------------|-------------------------------------------|
| 2025-04-09 | 09:00-11:00 | 2h          | 🐛 **Bug fixing**: Sorted and drag-drop on show linked activities |
| 2025-04-09 | 15:45-16:15 | 30m         | 💡 **Research & Brainstorming**: Winston.js (Node.js logging) + Shepherd.js (JS tutorial system) |
| 2025-04-09 | 16:25-16:55 | 30m         | 🐛 **Bug fixing**: Area drag-drop when flag is completed |
| 2025-04-09 | 17:15-19:55 | 2h 40m | 🚀 Built welcome-popup.component (HTML+CSS+JS) + fixed flag bugs in: show-me-linked, show-me, quantum-menu, drag-drop, area-header, area-drag-drop, activity-header, dashboard-page (.component/.html), areas.service, storage.service 🪱 (worm legacy: survived in drag-drop logic) |
| 2025-04-09 | 20:45-21:53 | 1h 08m   | 🧠 Tutorial Dev **Shepherd.js**: Initial tutorial.js setup. Custom CSS styling. Doc study + installation issue solving |

**2025-04-08**  

| Date       | Time        | Hours Spent       | Task Description |
|------------|-------------|-------------------|------------------------------------------------------|
| 2025-04-08 | 11:00-17:30 | 6h 30m (30 min break) | 🛠️ 📊 **Full System Upgrade**: 1) Pop-up/panel counters 2) Time buttons bugfix (sort/group) 3) Drag-drop link blocks 4) Added max-activities limiters |

**2025-04-07**

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-04-07 | 14:00-15:30 | 1h 30m | 🎂 **Birthday Achievements**: Celebrated with cake 🍰 → 1) Fixed area name YAML downloads in activity-editor 2) Added new YAML download feature per area 3) Debugged export systems. Best birthday workflow! 🎂 |
| 2025-04-07 | 16:50-18:20 | 1h 30m      | ➕ Added counters for all activities and completed tasks |
| 2025-04-07 | 18:20-18:40 | 20m | 📊 Added completed/active counters to YAML downloads |

**2025-04-06**

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-04-06 | 17:30-20:30 | 3h | 🐞 **Critical Bug Fixes**: Resolved area ID and calendar prevent-default issues across multiple components. Modified: `header-component.html`, `area-activity-popup.component.js`, `area-drag-drop.component.js`, `quantum-menu.component.js`, `rename-area-popup.component.js`, `activity-core.service.js`, `areas.service.js`, `editors.service.js` |

**2025-04-04**

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-04-04 | 09:15-10:00 | 45m | 🙏🐞 **UI Fixes + Feature**: Created notice-popup, fixed logout listener bug. Modified: `quantum-menu.html`, `quantum-menu.component.js` |
| 2025-04-04 | 16:00-18:11 | 2h 11m | ➕🧠📢 **UI/UX Overhaul**: Reworked pop-up system (new area creation, rename and settings notifications), added character limit for area names, with brainstorming sessions and bug fixes throughout the process. |

**2025-04-03**

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-04-03 | 09:30-10:30 | 1h | 🐞🔗✅🗑️🪚✂️ Bug fixing on **hard delete** and **soft delete** for activity tracking system. Modified: `activity-tracker.component.js`, `area-drag-drop.component.js`, `ui-helpers.service.js`. |
| 2025-04-03 | 11:52-12:52 | 1h  | 🌊🔥 **Implemented CASCADE DELETE!** Modified: `ui-helpers.service.js`, `areas.service.js`, `activity-tracker.component.js`. Now deletion propagates correctly to linked tasks! 🚀💪 |
| 2025-04-03 | 15:38-16:50 | 1h 12m | 🎨 **UI Enhancements & Tooltips Overhaul**: Added tooltips to **sidebar, areas, activity-editor, settings, search-area**, and **Quantum Menu** (even when sidebar is closed). Added **Download Button** (functionality pending - will add a popup). 💾🖱️🛠️ **Modified files**: `area-header.html`, `new-area.html`, `quantum-menu.component.js`, `quantum-menu.css`, `search-area.html`, `dashboard-page.html`, `areas.service.js`. |
| 2025-04-03 | 16:55-17:02 | 7m | 🐞🎨 Bug fixing on **CSS notifications** in `quantum-menu.css`. |
| 2025-04-03 | 18:00-19:18 | 1h 18m | 👤🔧 Bug fixing on Quantum Menu & created Profile Popup. Files modified: quantum-menu.component.js, quantum-menu.html, dashboard-page.component.js |

**2025-04-02**

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-04-02 | 07:45-09:17 | 1h 32m | 🔗 Bug fixing and improvements on delete **on cascade** per each activity. |
| 2025-04-02 | 10:25-11:18 | 53m | 🗑️ **Task completed!** On cascade delete (second part) for single activity. Modified files: `area-drag-drop.component.js`, `activity-tracker.component.js`. 🚀🔥💪 |
| 2025-04-02 | 12:21-16:24 | 3h 36m (incl. 30m break) | 🌊✅ *MAJOR MILESTONE!*: Finalized **cascade delete system** + **task move** logic. Full localStorage data synchronization. Modified files: `activity-editor.component.js`, `area-drag-drop.component.js`, `area-drag-drop.css`, `drag-drop.component.js`, `activity-core.service.js`, `editors.service.js`. Code changes: 248++ insertions, 170-- deletions ⚡. (including brainstorming for managing completed tasks whether to make them editable or not.) |
| 2025-04-02 | 16:28-16:38 | 10m         | 🐞 **Hotfix**: Counter bug in activity-tracker. Modified: `area-drag-drop.component.js` |
| 2025-04-02 | 17:50-21:16 | 2h 41m (incl. 45m break) | 🧠✨ **Brainstorming, new component & fixes**: added 'show-me' component, fixed quantum-delete button, general debugging |

**2025-04-01**

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-04-01 | - | - | 🐟 **April Fool's joke!** Just for fun! |

**2025-03-28**  

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-03-28 | 08:00-08:45 | 45m | 🔗 Connected item area activity with activity-editor through a link and dynamically disconnected it. |
| 2025-03-28 | 09:00-13:00 | 4h (incl. 1h30m pause) | 🛠️ Bug fixing on delete task, improved link-area with activity-editor, added new logic for link removal (disappears from list, updates activity area list, saves in local storage). Updated CSS: changed status with 🚧 'area working on the street' emoji. |
| 2025-03-28 | 16:50-18:20 | 1h 30m | ✅ Improved area-link with completed status when users drag into completed activities container. Also improved 'undo' when user changes own idea to restore task, restoring area and activity status by updating the 'workflow' manager tasks. 🔥🔥|

**2025-03-27**

| Date       | Time        | Hours Spent | Task Description                                      |
|------------|------------|-------------|-----------------------------------------------------|
| 2025-03-27 | 08:30-09:15 | 45m         | 🐞 Improved reset areas                             |
| 2025-03-27 | 11:50-12:10 | 20m         | 🛠️ Implemented **hard delete** and bug fixing on quantum-delete (Area Service) |
| 2025-03-27 | 12:20-14:52 | 2h 32m      | 🔥 Hard bug fixing and solved side effects: menu route sidebar, refresh page, reload area after login, bug fixing on CSS tracker and activity-editor |
| 2025-03-27 | 16:00-16:13 | 13m         | 🐞 Bug fixing on activity tracker after logout/login action |
| 2025-03-27 | 16:20-17:27 | 1h 07m      | 🔥 Hard bug fixing on activity-tracker total counter on refresh and login/logout, removed old related files |
| 2025-03-27 | 19:11-20:30 | 1h 19m      | 🔗 Added link manager in area-activity: first part toggle |

**2025-03-25**

| Date       | Time             | Hours Spent | Task Description |
|------------|----------------|-------------|------------------|
| 2025-03-25 | 14:00-15:00 | 1h | 🐞 bug fixing on popup selectors for area and activity-editor |
| 2025-03-25 | 15:00-17:42 | 2h 42m | 🛠 🔥 Bug fixing on activity-editor control, created new component activity-header, bug fixing on activity-editor, drag-drop, header-component, activity-core (12 files changed) |
| 2025-03-25 | 18:50-19:30 | 40m | 🐞 Bug fixing on save YAML Download + installed **npm package js-yaml** 🔧 |
| 2025-03-25 | 19:50-21:10 | 1h 20m | 🧠 Brainstorming on *data demo*, bug fixing on *common activities*, bug fixing on popup generic, bug fixing on reset |

**2025-03-24**

| Date       | Time             | Hours Spent | Task Description |
|------------|----------------|-------------|------------------|
| 2025-03-24 | 12:00-13:00     | 1h          | 🔧 Improved area memory management and added area reset in `quantum-menu.component.js` and `areas.service.js` |
| 2025-03-24 | 14:00-15:30     | 1h 30m      | 🚀 Implemented task addition, area switching, and reload functionality. Fixed task visibility between `activity-editor` and areas, and ensured data is properly handled. Changed old `localStorage` key to a primary key for task and area management. |
| 2025-03-24 | 16:30-17:30      | 1h          | 🦷 Improved task deletion in area with toast and `localStorage` manager. Optimized code for `ui-helpers.service.js` and fixed bugs in `activity-core.service.js`. |
| 2025-03-24 | 18:00-19:05   | 1h 5m       | 🔄 Connected activity storage per area via `editors.service.js` and event listeners. Improved area drag & drop logic, optimized positioning, and refined `activity-editor` interactions. **Enhanced stability and usability for the demo.** |

**2025-03-22**

| Date       | Time             | Hours Spent | Task Description |
|------------|----------------|-------------|------------------|
| 2025-03-22 | 07:15-08:18    | 1h         | 🛠️ Finished delete local storage function, pending editors and area movements saving. Fixed bug on reset of Quantum Menu loading. Created dynamic "item-id" based on time to allow movement between JavaScript arrays. 🐞 Bug fixing on activity-editor and activity-popup components to improve the common addActivityToList(item, isSave) function. |
| 2025-03-22 | 09:46-10:57    | 1h 11m     | Local storage with editing corrected; still needs to be done on all editing. |
| 2025-03-22 | 15:15-16:06    | 51m        | 🔧 Fixed event focus on Editors service with merge into local storage on activity list and bug fixing on activity-editor.css. |
| 2025-03-22 | 16:30-18:17    | 1h 47m     | ✅ Local storage on activity tracker fixed!!! - Major milestone achieved, including reset, rendering, and movement between activity-tracker and activity-list containers while maintaining all references! |
| 2025-03-22 | 21:00-22:00    | 1h         | 🚀 **Final development push:** Fixed positions and activities for local storage after drag-drop. Committed and pushed to Git: improved drag-drop, editing, and tracker with localStorage. Created `storage.service`, updated multiple services and UI components (`ui-helpers.service`, `editors.service`, `activity-core.service`, `quantum-menu`, `drag-drop.component`, `activity-tracker.component`, etc.). Added **reset button** in Quantum Menu for clearing session localStorage. ✅ **Git push success** with **1356 insertions(+), 560 deletions(-), 17 files changed**. 🎉 |

**2025-03-21**

| Date       | Time       | Hours Spent | Task Description                               |
|------------|------------|-------------|------------------------------------------------|
| 2025-03-21 | 07:30-8.30 | 1h | 🧠 Brainstorming |
| 2025-03-21 | 09:20-10:20 | 1h | 🛠️ Updated area-activity-popup and area-drag-drop, made logic for popup adder for each task in the area-activities drag-drop container |
| 2025-03-21 | 11:40-12:10 | 0.5h | 🐛 Bug fixing on activityTracker.decTotalActivities() from drag-drop |
| 2025-03-21 | 12:20-13:00 | 0.67h | 🔗 Update connection with tasks on the area-drag-drop component and little various 🐛 bug fixing - 9 files changed |
| 2025-03-21 | 13:00-13:15 | 0.25h | 🛠️ Bug fixing on decrementer tracking panel and created areaAddDeleteButton(item) |
| 2025-03-21 | 15:30-17:00 | 1.5h | 🏗️ Added generic-popup.css, updated generic-popup.service.js, updated editors.service.js for area task events, updated dashboard-page.component.js for generic CSS, bug fixing on quantum-menu.component.js, updated area-activity-popup.component.js for drag-drop and events task, updated webpack.config dev and prod, removed old folders public and views from refactoring of first project in Scala language! 🪜|
| 2025-03-21 | 17:40-19:40 | 2h | 🏗️ brainstorming and updating internal cargo elements 🏗️|

**2025-03-20**

| Date       | Time       | Hours Spent | Task Description                               |
|------------|------------|-------------|------------------------------------------------|
| 2025-03-20 | 07:30-11:30 | 4 | 🧠 Process started on the 18th: intensive development that resulted in modifications to **30 files**. Tasks performed include creating the Web components for the Area Activity Popup and Area Header, fixing the CSS, running tests, brainstorming, bug fixing on the popup, improving the header, updating *areas.service.js* and *area-activity-core.service.js*, and optimizing *generate-component.sh* with 4 parameters. |
| 2025-03-20 | 12:00-13:00 | 1 | 🧠 Added new components: **area-activities**, **area-drag-drop**, and updated the **menu switch logic** in the dashboard, completing the initial implementation and conducting basic tests. |

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
