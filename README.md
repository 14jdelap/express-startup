# express-startup

A bash script to set-up the basic packets, directories, and files for an Express project.

This includes:

- Packets
  - `express` framework: provides the abstractions to set-up the server and routes, among other things
  - `nodemon`: restarts the server automatically
- Directories
  - `views`
  - `public`: stores files available publicly; the code in `router.js` serves it statically out-of-the-box
  - `routes`: stores routes
  - `utils`: stores utility functions
- Files (with basic code)
  - `app.js`: runs the application
  - `router.js`: stores the app's routes
  - `path.js`: module to get the root directory
  - `package.json`: edited to include the script that runs `npx nodemon app.js` when `npm start` is executed
