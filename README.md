# gulpnuke.sh

## 1.Main purpose of the project
Main purpose is using one script to create all dependencies and proper folder structure for project.

## 2.How to use
*Working with NVM only*

*Project folder MUST have a valid name without spaces, use `project-name` format*
```fish
sh -c "$(curl -fsSL https://raw.githubusercontent.com/n3g3n/gulpnuke.sh/main/gulpnuke.sh)"
```
```fish
chmod +x gulpnuke.sh
```
```fish
bash gulpnuke.sh
```

### 2.1 Script will do
- Folder structure
 - It will create follow folder stricture (see paragraph 2.1.a)
- Install Gulp4 (master branch)

### 2.1.a Folder stricture
- gulpfile.js
- .nvmrc
- src
  - /base
  - index.html
    - /scss
      - index.scss
    - /css
      - index.css
    - /js
      - index.js
    - /img
      - screenshot.png
    - /fonts


### 2.1.b How to use project later
For start developing use follow:
```bash
gulp watcher
```
For make `dist` folder use `gulp`
```bash
gulp
```
