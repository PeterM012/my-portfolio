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
This project was to create a delpoyed portfolio showcasing samples of my work to prove that I am a worthy candidate for an open position. I achieved this by utilizing advance CSS techniques. I did this by creating a webpage that adjust to the viewpoint needed without distorted the images or text. I implements a navagational bar with a hover action to really make the words pop. I also created the footer to display the logos/icons which can access the correlating destination. My biggest success for this project was getting the Tags to be displayed on the images at any viewpoint. Below is the code I used to achieve this. It took 3 days to solve my problem but i would say it displays great!

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
