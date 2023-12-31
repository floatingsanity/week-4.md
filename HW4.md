## Link of React hello world : 
https://github.com/floatingsanity/create-react-app.3.git
## Link of Angular heloo world : 
https://github.com/floatingsanity/angular-boilerplate.git
## Link of Vue hello world: 
https://github.com/floatingsanity/vite-vue.2.git
## Link of Svelte hello world : 
https://github.com/floatingsanity/sveltekit-boilerplate.git

## my attempt to port my card in vue : 
https://github.com/floatingsanity/vue.git


## What are the similarities and what are the differences in repo structure? Find 5 similarities and 1 difference between each of the 4.

### similarties:
- Source Code Directory: All four repositories are likely to have a directory where the source code for the application is stored, often named "src" or "app."
- Package.json: Each repository typically contains a package.json file that defines project dependencies, scripts, and metadata.
- Node Modules: They all include a "node_modules" directory where project dependencies are installed.
- Gitignore: Most repositories have a .gitignore file to specify files and directories that should not be tracked by version control.
- Readme.md: Many repositories have a README.md file with project documentation and instructions.

### diffrence:
- Framework-Specific Configuration: The main difference lies in the configuration files and folder structure specific to each framework. For example, React projects might have a "public" folder for static assets,
- while Angular projects often include an "angular.json" file for configuration.

## at the syntax of a js/template file from each. Identify something vanilla in each and something library specific in each (8 total items here)?

### React:
- Vanilla: JSX syntax for defining components.
- Library-Specific: React's "useState" and "useEffect" hooks for managing state and side effects.

### Vue:
- Vanilla: Template syntax for defining components (e.g., <template>).
- Library-Specific: Vue's "v-model" directive for two-way data binding.

### Angular:
- Vanilla: TypeScript class-based component definition.
- Library-Specific: Angular's decorators like "@Component" and "@Input" for component metadata.

### Svelte:
- Vanilla: HTML-like syntax for defining components.
- Library-Specific: Svelte's "store" for managing global state

## R eview package.json - What is common amongst them, what's different? What commands can we run? Try to run all the different commands in the repo for each project.

### Commonalities:
All package.json files will have dependencies and devDependencies sections. They often include scripts for running, building, and testing the application.
### Differences:
The specific dependencies listed and the scripts available can vary significantly between projects, depending on the framework and its requirements.

## Rank order these for readability / ease of your understanding and give a brief justification as to why you thought 1 was the easiest and 4 was the hardest to understand (or that you didn't understand!)

- Vue: Vue.js tends to have a straightforward and intuitive structure, with a clear separation of concerns in the codebase. Its template syntax is also easy to understand for most developers.
- React: React's component-based structure is well-documented and widely adopted, making it relatively easy to follow. JSX is familiar to many developers, although it might require a learning curve for some.
- Svelte: Svelte's simplicity can make it easy to understand, but its unique approach may be less familiar to developers coming from other frameworks. Once grasped, the code can be quite readable.
- Angular: Angular's extensive configuration and use of decorators can make it more challenging for some developers to grasp, especially those new to the framework. It often requires a steeper learning curve
compared to the others.
