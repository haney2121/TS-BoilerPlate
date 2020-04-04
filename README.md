## Start up

run npm start on a terminal to start the lite server
run tsc -w FILE.ts on another terminal to watch changes for a single file
run tsc to do all files in project add -w to watch all

start a new package.json: npm init
start a new tsconfig file: tsc --init

- compilerOptions:

  - target can change verison of JS suggest es6

Configured certain ts files:

- Exclude
  - configured to ignore excluded.ts to have it setup it for the user, can be removed. other settings could be wild card if desired. "_.dev.ts or \*\*/_.dev.ts"
  - Node_modules is added as well, not required it is excluded by default, but here as well for placement to see you can do this for when its added
- Include
  - Not configured, when set you need to include everything you want to do. by default it includes all, can be done by file or folder
- Files
- Not included, added like Include, but files
