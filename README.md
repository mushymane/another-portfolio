# Portfolio

## Description
![alt text](assets/images/mushy.gif)

This project is a way to showcase my previous work. It currently consists of an HTML file and a linked CSS file. The HTML has a simple structure, consisting of a header, navbar, hero, about me, projects, and contact section. A majority of the content is located within containers which lets the CSS work its magic. Many of the tags also have ids and classes which the CSS file can point to for styling and positioning. Flexbox is the tool used to power the responsiveness. It adjusts to the viewer's screen resolution to be easier to read, and to be a little more aesthetically pleasing. It also utilizes media queries to be optimized for smaller screen sizes such as tablets and smartphones.

The features of the page include a navigation bar with internal links, an about me section, a projects section with links to each project, and a footer with my contact information.

To view the web page visit this [link](https://mushymane.github.io/another-portfolio/)

## Technologies Used
- HTML - used to structure and create elements on the DOM
- CSS - styles the HTML elements on page
- Git - version control
- Github - where the repository is hosted
- Visual Studio Code - text editor
- Font Awesome - amazing icons
- Google Fonts - for the Work Sans font
- ScreenToGif - for recording short screen captures

## Code Snippet
HTML
```
<section id="projects">
        <div class="project-container">
            <div class="project-header">Projects</div>
            <div class="projects">
                <div class="project-card">
                    <a href="https://github.com/mushymane" target="_blank" class="project-1" title="BLACKPINK IN YOUR AREA">
                        <div class="text-container">
                            <h3 class="name">Blackpink Alerts</h3>
                            <p>
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                                Vitae eum dicta, vel quos harum molestiae rerum tempore modi assumenda officia, minima architecto. 
                                Maxime consequatur culpa doloremque libero obcaecati! Quod, quae.
                            </p>
                        </div>
                    </a>
                    <button class="button">
                        <a href="https://github.com/mushymane" target="_blank">Code</a>
                    </button>
                </div>
```
CSS
```
.projects {
    width: 100%;
    display: flex;
    flex-flow: wrap;
    justify-content: center;
    align-items: center;
}
```

## Author Links
[LinkedIn](https://www.linkedin.com/in/luigilantin/)
[Github](https://github.com/mushymane)