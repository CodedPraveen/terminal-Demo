# 1. In The folder if we run `.`

```
npm create vite@latest my-project
```

- install any library and framework than folder structure look like this `folder` - `my-project` and neither we use `.` Like this

```
npm create vite@latest .
```

- this like command use to avoid a folder create
- so our folder struture look like this `folder` and All the file import direct - `node_modules, src, and another file`

# 2. Use of `code -r`

- if we run this

```
npm create vite@latest my-project
```

- than if we open folder `my-project` without close VS Code tab than use
```
code -r .\my-project
```
this close currently tab and open ` my-project ` so we access direct file

# 3. use cd 