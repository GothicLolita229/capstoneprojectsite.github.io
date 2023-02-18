#### Kalie Kirsch, Marceia Patterson, Viana Butler, Ciara McLaughlin, Lourdes Linares

# Our Capstone Project


This project will be helpful for:
<ul>
  
  <li><strong>Neurospicy minds</strong> - an application that can take some of that decision fatigue off your mind</li>

  <li><strong>Personlized plans</strong> - You can choose what type of planning you'd like this to do, whether it be storing your favorite restaurants and then choosing one or randomly helping you decide on a recipe for dinner</li>
  
  <li><strong>Experience New Adventures</strong> - if you're stuck in a rut and you don't have the brain space to decide on activities to kill that boredom, this app is for you</li>

</ul>

## Useful Links


- [Capstone Project Link](https://pages.github.com)
- [Suggestions Box](https://linaresl1836.github.io/dev-blog) 

- This Website's URL: https://gothiclolita229.github.io/linaresl1836.github.io/

## Description
My Main project is the Co-Writers Website and it's a website that showcases young amateur author's work. This site gives users the opportunity to create stories even if they lack the skills to write great detail and have their words flow eloquently.
Amamteur authors will take the user input and create a story with the guidelines from the form's input.

## User Stories
[Co-Writers Website Kanban Board](https://github.com/users/GothicLolita229/projects/5)

## Code Snippets

Here my open Preview button JavaScript Code Snippet
```
openPreviewButtons.forEach(button => {
    button.addEventListener("click", () => {
        formSubmit();
        const preview = document.querySelector(button.dataset.previewTarget);
        openPreview(preview);
    });
});
overlay.addEventListener("click", () => {
    const previews = document.querySelectorAll(".preview.active")
    previews.forEach(preview => 
        {
            closePreview(preview)
    });
});
```

## Diagrams

![M5T1-ContextDiagram_Linaresl1836](https://user-images.githubusercontent.com/90853197/205704427-895e08f7-0159-4684-8da7-d9aef27b8dec.png)
