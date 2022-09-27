# my-portfolio

## Deployed Link
https://peterm012.github.io/my-portfolio/

## Site Picture 
![image](https://user-images.githubusercontent.com/110750833/192427540-01fbde0b-feac-40a2-940f-9f6b98259459.png)

## Technologies Used
- HTML - Used to create elements on the DOM
- CSS - Styles html elemnts on page 
- Git - version control system to track changes to source code
- GitHub - hosts reposiory that can be deployed to Github Pages

## To Do
- Add links that scroll to corresponding selection
- Have at Least 5 Links
- About ME, Work, Contact Me
- First Application must be the biggest image
- Images of Applications and Tags in boxes
- When image is clicked on must send user to deployment page
- Resize Page to correspond with respective screens or device
- Have a responsive Layout that adapts to viewport

## Summary 
This project was to show how to properly refactor and improve the code base for sustainability and accessibility. Using semantic HTML I improved the quality of selectors and properties in CSS. I used comments between each line to provide organization and maintain a healthy form of communication between other developers. I also exceeded expectations with code using alt attributes and optimized the search engine parameters to meet the client's accessibility standards.

## Code Snippet
Code for HTML Tags on the Images 
```html

<figure class="laptop-figure-tag tag-featured">
   <img src="./assets/images/laptop-main.png" class="laptop-img" alt="Laptop with a notebook, a coffe cup, and a bag on a table"></img>
</figure>

```
Code for the CSS Tags on the Images
```css
.laptop-figure-tag {
    position:relative;
}

.laptop-figure-tag::before {
    position:absolute;
    top: 80%;
    display:block;
    color: red;
    padding: 0.5rem 1rem;
    font-weight:bold;
}

.laptop-figure-tag.laptop-figure-tag.tag-featured::before {
    content: "Coming Soon";
    background-color: black;
    border-radius: 5px 50px 30px 15px;
}
```
