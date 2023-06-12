# Introduction
- Brief overview of the website and its purpose.

# Website Features
## [Note](apps/example-think-python/src/components/note)
- This feature allows users to create and manage notes within the application's user interface, enabling users to create, organize, and customize their notes.
- The [note cards](apps/example-think-python/src/components/note/note-card.tsx) provide a visual representation of the notes, while the [delete](apps/example-think-python/src/components/note/note-delete.tsx) functionality, [color picker](apps/example-think-python/src/components/note/note-color-picker.tsx), and [toolbar](apps/example-think-python/src/components/note/note-toolbar.tsx) enhance the overall note management experience within the application.

  <img src="https://github.com/yahan-ds/itell_python/assets/93264144/3c3fba41-29eb-426e-847c-e2d1e0c80a33" alt="note image" title="choose an operation" width="whatever" height="100"> 
  <img src="https://github.com/yahan-ds/itell_python/assets/93264144/9eded38c-cfe7-4326-93fa-2287f4128e40" alt="hightlight image" title="highlight the content" width="whatever" height="100">

  <img src="https://github.com/yahan-ds/itell_python/assets/93264144/b56d876f-ebb9-4710-a29c-55a65760bbd1" alt="enter note image" title="add a note: type in the notes. click 'enter' to save." width="whatever" height="250">
  <img src="https://github.com/yahan-ds/itell_python/assets/93264144/eecd9d5b-20a2-4769-bfad-67d8edd722b8" alt="remove highlight" title="delete the highligh" width="whatever" height="250">

## [Theme](apps/example-think-python/src/components/theme)
- With this feature, users can select the visual theme for the textbook's display.
- They have the option to choose between Light or Dark mode, or they can set it to follow the system theme automatically by clicking the sun/moon icon at the upper right corner.

  <img src="https://github.com/yahan-ds/itell_python/assets/93264144/a0bfa77d-a283-4abd-88cd-51440f3102aa" alt="light image" title="light mode" width="whatever" height="135">
  <img src="https://github.com/yahan-ds/itell_python/assets/93264144/d2ec9808-ebdc-4eb3-b742-62b9ff9ba8ce" alt="dark image" title="dark mode" width="whatever" height="135">

## [Dashboard](apps/example-think-python/src/components/dashboard)
- This feature displaies a summary of the user/student's activities and statuses in a dashboard
-

# Configuration
### Environment setup
1. Install pnpm
2. Run `pnpm install` to install the dependencies listed in the `package.json` file.
3. Run `pnpm run (<custom project script>)` from the root of the entire itell repo. For example, the custom project script for think-python is `dev:tp`, so run `pnpm run dev:tp`.
4. The website will then be available at http://localhost:3000 by default.

### Creat a new textbook
1. Create your customized web page by adding a new folder (using the Next.js framework) in the [`apps`](apps) folder. You can duplicate the `apps/example-think-python` folder and modify the configuration. 
2. Rename the file to reflect the new page you're creating. 

### Adding content
1. Use mdx files to add content. See the [MDX writing tutorials here](https://kabartolo.github.io/chicago-docs-demo/docs/mdx-guide/writing/).
2. Create mdx files in the `apps/<textbook_name>/content` folder based on your content archetecture. For example, [`apps/example-think-python/content/chapter-0.mdx`](apps/example-think-python/content/chapter-0.mdx) will be translated to a web page at http://localhost:3000/chapter-0, where the  `example-think-python` is `textbook_name` in this case. 

### Customization
1. How to customize the website's appearance, themes, or branding.
2. Provide instructions for modifying templates, CSS, or other customization options.

# Troubleshooting
- Common issues: List frequently encountered problems and their solutions.
