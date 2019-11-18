# eclipse.importProjects.feature.deploy

How to install:

1. Clone this repo to your local drive.
2. Start your Eclipse.
3. Select  Help->Install new software->Add->Local-> 'your installation folder'.
4. Click Add.
5. Uncheck 'Group items by category'.
6. Select 'eclipse.importProjects.feature'.
7. Install.


How to use:

After installation, exit Eclipse. On the CLI use:

eclipsec -application eclipse.importProjects.application -data 'path to workspace' -import 'path to project'

Wait until import is finished.
Launch Eclipse.
