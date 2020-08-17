# What-I-Learned-Week-13

# Bento Box

An exercising in using CSS Grid to arrange small Japanese `div`s into boxes.

### Mission - working exclusively in `style.css`.

exp) #app {
  display: grid;
  grid-template-rows:1fr 1fr 2fr 1fr ;
  grid-template-columns: 1fr 2fr 1fr ;
  width: 826px;
  height: 936px;
}

.box {
  width: 100%;
  height: 100%;
}


# Holy Responsive Grid, Batman!

Use Grid to change a holy grail layout into a responsive layout.

### tools needed - media queries - consists of a media type and can contain one or more expressions, which resolve to either true or false.

exp) @media (min-width: 601px) and (max-width: 800px){
  #app {
    display: grid;
    height: 1000px;
    grid-template-columns: 15% 60% 25%;
    grid-template-rows: 20% 30% 30% 20%;
    font-size: 5em;
    text-align: center;
  }
}


# # Instabox - A Subsidiary of Flexbook

### Mission - working on replicating this Instagram website.

#### Some Resources

* CSS Tricks' excellent [run-through](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) of Flexbox. 


# Flexing @Media

Make a responsive website that uses media queries. 

Here are the different column layouts we want:

1. When the screen is less than 600px, make 1 column of 20.

2. When the screen is between 600px and 800px, make 2 columns of 10.

3. When the screen is between 800px and 1000px, make 10 columns of 2.

4. When the screen is greater than 1000px, make 20 columns of 1.

