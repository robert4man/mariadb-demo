# MariaDB Demo Container
This is a demo dev container project for MariaDB to run in Codespaces for teaching and learning.

Simply launch the container in Codespace and run the following command to load the Chinook database:

`$ mariadb -u root -p < Chinook.sql`

This will create a new database called `Chinook` and load the data into it. This will take some time to complete on the default Codespace container. Students can also use Docker locally if they prefer using VS Code and the [Remote Development extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack).

The default database password is simply `mariadb`.