Hugos 7-1 SCSS Pattern is a very good starting point for a multipage HTML website

You don't need to use every folder, I have only included what I think is the most important ones for any project. Especially if you use a CSS framework such as bootstrap or bulma.io

Most important folders

- **abstracts**
  - **_variables.scss** - Defining your color variables is helpful across document
  - **_mixins** - Specialized media query mixins are great for responsive webdevelopment
- **base**
  - **_base.scss** - This is where you define your generic HTML styles such as `h1, h2,h3,h4,h5,h6,img` elements
- **components**
  - **_buttons.scss** - You might not need a specialized buttons CSS file if you run bootstrap
- **layout**
  - **_header.scss** - Header specific Styles
  - **_footer.scss** - Footer specific styles
- **pages**
  - You don't necessarily need specific page styles most times. If you do they would be things like the contact page, home page, etc
- **themes**
  - Most projects don't need themes. If your making a webapp this would be like a dark and light theme.
- **vendors**
  - **_bootstrap.scss** - This is where you put your bootstrap overrides and customizations.
  
**Main.scss** imports all the files together