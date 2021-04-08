# Getting Started with this boilerplate

This boilerplate is minimalist, based on Create react app with electron installed, then moving to viteJS with electron.

The two things that have been installed is :

- Foreman to launch procfile in dev mode.
- Electron-builder to pack the application.

You can change the way this application launch as you want, it's just a way to do it.

## Usage

Install the application with :

```
npm install
```

Then you have access to those commands :

| Command          | Description                                                |
| ---------------- | ---------------------------------------------------------- |
| npm run test     | Run test                                                   |
| npm run start    | Run only react application on your localhost               |
| npm run dev      | Run react with electron                                    |
| npm run electron | Just run electron without react                            |
| npm run dist     | Compile react application and compile electron application |


## Modification

Don't forget to modify the package.json with your description, project name and your name (author).

```
"name": "projectname",
"description": "your description",
"author": "your name",
```

Also you want to use your own repository, don't forget to change the git remote like so :

```
git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```

The **electron-wait-react.js** file permit electron to wait the launch of react application, in order to prevent some bug in local.
