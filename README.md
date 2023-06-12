# Introduction
- Brief overview of the website and its purpose.

# Website Features
- Functionality and features
- Explain how to use each feature and any configuration options related to them
### [Note](apps/example-think-python/src/components/note)
- This feature allows users to create and manage notes within the application's user interface, enabling users to create, organize, and customize their notes.
- The [note cards](apps/example-think-python/src/components/note/note-card.tsx) provide a visual representation of the notes, while the [delete](apps/example-think-python/src/components/note/note-delete.tsx) functionality, [color picker](apps/example-think-python/src/components/note/note-color-picker.tsx), and [toolbar](apps/example-think-python/src/components/note/note-toolbar.tsx) enhance the overall note management experience within the application.

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
