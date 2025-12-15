[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Ucfc6TO_)
# Project Instructions

Follow the instructions here: https://vuxcode.netlify.app/new/we1/lessons/major-project-brief/

The aim of the project is to show how you have developed your website, the steps you have taken and the problems you have solved!

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT!

# Project Notes

I sent one version of the earlier versions of my website

# Project Summary

The goal of this project was to create a visually immersive website inspired by Dungeons & Dragons. The website presents different character classes in a fantasy-themed layout, where the user can choose a class from the index page and then read more detailed information on a separate page for each class.
I focused on creating a “game-like” feeling using background images, hover effects, custom fonts, and interactive elements. The index page works like a character selection screen, while the class pages are designed to resemble parchment or in-game lore pages to enhance immersion.

One of the biggest challenges during this project was positioning text correctly inside images. In the beginning, the text often appeared outside the image container instead of staying inside it. Through research and watching tutorials, I learned that the solution was to make the parent element position: relative and the child elements position: absolute. This ensured that the text moved only within the image container instead of the entire page.
Another important lesson was understanding how centering works.

https://www.youtube.com/watch?v=YEmdHbQBCSQ

transform: translate(-50%, -50%);

helped center elements based on their own size rather than the parent’s size. However, I also learned that this method still requires manual adjustment using top and left values, especially when working with text, since text elements are not perfectly square.
I also struggled initially with arranging multiple images in a “shop-style” layout. Revisiting older lessons helped me remember that grouping divs inside a parent div allows them to align them correctly in rows.
A smaller but important problem involved hover effects. When I added text on top of images, the text blocked the mouse clicks on the image. After researching the issue, I learned about pointer-events: none;, which allowed users to click the image even when hovering over the text.

If i had more time i would have added more in the different classes, i would have also added a multiclass page where you could have clicked on 2 different classes and then it would show their multiclass with information about it.

I was 4 hours short on the time budget because of other school projects and tests.
