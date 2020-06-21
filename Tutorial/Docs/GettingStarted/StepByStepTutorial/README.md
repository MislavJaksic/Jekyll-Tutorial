## Step-by-step Tutorial

Visit the `Projects/step-by-step` to see the final result.  

Initialize a Jekyll project.  

Create content pages and layout pages.  
Use `Front Matter` to set variables.  
Layouts can be nested.  

Include is a repeat content fetched by a layout.  
Data files are content list stores.  

Assets are CSS, JS and image files.  
Layouts reference assets.  

You can use Jekyll for blogging.  
Posts have a strict file name format.  
Collections are groups of posts.  

### Order of resolution

1) Content
2) Innermost layout
3) Includes
4) Data
5) Assets

Content calls a layout.  
A layout can call another layout.  
Layouts call includes.  
Layouts and includes call data.  
Layouts are styled with assets.  
