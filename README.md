# Class-based CSS
As I was doing the markup for this challenge, I decided to use Sass for styling because I have always loved being able to use their nesting feature. However, after watching a conference talk by Andy Hume called [CSS for Grownups](https://www.youtube.com/watch?v=ZpFdyfs03Ug), I decided to give classes a go rather than heavily relying on nesting elements with Sass.

At first, I thought I was adding way too many classes to my elements; however, if I decided that I did not use the correct element in my markup, all I had to do was change the element tag (keeping the class name), and I did not have to hunt through my CSS to update my changes. I really love this! For example, if someone used divs instead of an article tag but then realized that they should really be using article for accessibility, they could just change the tag name to article, and the class styling would carry over.

I decided to see how I felt about using nested elements and get rid of all my classes as an experiment on another page. Changing back to heavily relying on nested elements, I did NOT like the feel of it. It stressed me out that I could change one element, and everything would implode. So I decided to see how I would use Sass effectively beyond variables. I decided to implement extend and inheritance, which is almost like having special CSS classes! I found this very effective, and would like to implement it in my original Sass styling in the future.

Ultimately, I think heavily using classes to style is a smart way to go about styling. This can be further accompanied by using extend/inheritance Sass features. Feel free to see how I styled in both ways. The main index.html is linked to styles.sass. This is the one that is class heavy. Pikachu.html is the one that relies on nesting but uses extend/inheritance.

index.html ---> styles.sass ---> class heavy

pikachu.index.html ---> styles_revisited.css ---> nesting & extend/inheritance
