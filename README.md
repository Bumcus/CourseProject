## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Bumcus/CourseProject/edit/master/README.md) to maintain and preview the content for your website in Markdown files.
  
# This is my project page.
   Welcome to my course project page.
   First choose a topic of interest from the menu:

      ### Items of Interest
      <a href="#pageTwo" class="w3-bar-item w3-button">Authors</a>
      <a href="#pageThree" class="w3-bar-item w3-button">Movies</a>
      <a href="#pageFour" class="w3-bar-item w3-button">Add Review</a>
      <a href="#pageFive" class="w3-bar-item w3-button">Past Reviews</a>
           
      ## Authors           
         
       
  ### Some of my favorite authors of all time.
     -[Terry Brooks](http://terrybrooks.net/)
     -[R.A. Salvator](http://rasalvatore.com/)
     -[Terry Goodkind](https://www.terrygoodkind.com/)
          

		<li><a href="#pageOne" data-icon="home">Home</a></li>
		<li><a href="#pageThree" data-icon="arrow-r">Next</a></li>
	

  <body>
      <div id="pageThree" data-role="page" data-theme="a" data-add-back-btn="true"
            <h1>Have a great day!</h1>
        </div>

        <div data-role="main" class="ui-content">
          <p>Some of my favorite movies.</p>
          <ul data-role="listview" data_inset="true" rel="external">
            <li data-role="list-divider">Favorite Movie list:</li>
            <li><a href="http://www.starwars.com/">Star Wars</a></li>
            <li><a href="http://www.startrek.com/">Star Trek</a></li>
            <li><a href="http://www.lordoftherings.net/">Lord of the Rings</a></li>
          </ul>
        </div>
      <div data-role="footer" data-add-back-btn="true">
		<div data-role="navbar">
		  <ul>
		    <li><a href="#pageTwo" data-icon="arrow-l">Authors</a></li>
		    <li><a href="#pageOne" data-icon="home">Home</a></li>
		    <li><a href="#pageFour" data-icon="arrow-r">Next</a></li>
		  </ul>
		</div>
        <h1><img src="images/copyright_logo.png" height="30" alt="Copyright Logo"></h1>
      </div>
    </div>
  </body>

  <body>
	<div data-role="page" id="pageFour" data-theme="a" data-add-back-btn="true">
	  <div data-role="header" data-theme="a">
		<h1>Add a review about the subject of the week</h1>
	  </div>
	  <div data-role="content">

		<form action="#pageFive" method="updateReviews">
			  <label for="fname">First name:</label>
				  <input type="text" name="fname" id="fname" data-clear-btn="true">
			  <label for="lname">Last name:</label>
			    <input type="text" name="lname" id="lname" data-clear-btn="true">
			  <label for="user_review">Review:</label>
			    <textarea rows="10" cols="40" name="review" id="user_review" data-clear-btn="true"></textarea>
				<input type="reset" value="Reset Button">
        <label for="btn_submit" Submit Button </label>
				<button type="button" onclick="addReview()" id="btn_submit">Submit Button</button>
		</form>
	  </div>
	  <div data-role="footer" data-theme="a" data-add-back-btn="true">
	   <div data-role="navbar">
		<ul>
		  <li><a href="#pageThree" data-icon="arrow-l">Movies</a></li>
		  <li><a href="#pageOne" data-icon="home">Home</a></li>
		  <li><a href="#pageFive" data-icon="arrow-r">Next</a></li>
		</ul>
	  </div>
		<h1><img src="images/copyright_logo.png" height="30" alt="Copyright Logo"></h1>
	  </div>
	</div>
  </body>

  <body>
      <div id="pageFive" data-role="page" data-theme="a" data-add-back-btn="true">
        <div data-role="header">
            <h1>List user reviews</h1>
        </div>

        <div data-role="main" class="ui-content">
          <p>Some of my favorite movies.
            <div data-role="content">
              <div class="ui-grid-c">
              <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:60px">Movie A</div></div>
              <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:60px">Movie B</div></div>
              <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:60px">Movie C</div></div>
              <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:60px">Movie D</div></div>
              </div>
            </div>
			  <ul id="reviewsList" data-role="listview" data_inset="true" rel="external" data-filter="true">
          <li></li>
        </ul>
		  </p>
        </div>
      <div data-role="footer" data-add-back-btn="true">
		<div data-role="navbar">
		  <ul>
		    <li><a href="#pageFour" data-icon="arrow-l">Add Review</a></li>
        <li><a href="#pageOne" data-icon="home">Home Page</a></li>
      </ul>


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

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Bumcus/CourseProject/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
