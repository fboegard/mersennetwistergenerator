## Welcome to GitHub Pages in main!!!!!

<script src="https://code.jquery.com/jquery-1.12.4.js" integrity="sha256-Qw82+bXyGq6MydymqBxNPYTaUXXq7c8v3CwiYwLLNXU=" crossorigin="anonymous"></script>
<script src="https://github.com/fboegard/mersennetwistergenerator/blob/main/mersennetwister.js" crossorigin="anonymous">
</script>

<p>Click the button to display an alert box.</p>

<button onclick="myFunction()">Generate random number 1 -> 100</button>

<script>
 var mt = new MersenneTwister(seed); // if no seed is defined, seed randomly
 var mt2 = new MersenneTwister();
 
function myFunction() {

//   alert("Hello! I am an alert box!");
 var randomnr = mt.int();
 var randomnr2 = mt2.int();

   alert("Random " + randomnr) ;    // random 32-bit integer
   alert("Random2 " + randomnr2);
}
</script>


You can use the [editor on GitHub](https://github.com/fboegard/mersennetwistergenerator/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/fboegard/mersennetwistergenerator/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we???ll help you sort it out.
