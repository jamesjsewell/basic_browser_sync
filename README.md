## browser-sync setup ##
### basic webapp ###

1. `git clone https://github.com/jamesjsewell/basic_browser_sync.git your_project_name` change your_project_name to the actual name of the project

2. `git remote remove origin`

3. create a new github repository for your project and
set this as your project's remote

4. `git add .`

5. `git commit -m "your commit message"`

6. `git push origin master`

* `npm install`
* `npm run start`

if you decide to use this example for your project, and you need more than just a basic webpage, or you want to use a different folder structure:
you'll need to edit the `browser_sync_config.js` file. It's commented to make it easier to understand how it works.
Basically just add and edit paths so that browser-sync will watch the files that you need it to watch. Also you may want to go to the bottom of the file and change the path that the server is using. 


