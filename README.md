# Gitpages Copy Button
A repo to try to figure out how to add a copy button to code snippets on GitPages. 
On github when using code snippet blocks there is automatically a copy button added.
```sh
Example: code snippet
```
However when this converted to Gitpages this feature dissapears giving rise to the aims of 
this repo.
# Goals
1. Add functional Copy Button.
2. Format Copy Button.
3. Make it deployable on any Gitpages website. 

Following the tutorial found [here](https://www.aleksandrhovhannisyan.com/blog/how-to-add-a-copy-to-clipboard-button-to-your-jekyll-blog/) this is the result.

{% include codeHeader.html %}
```someLanguage
code goes in here!
```
It doesn't seem to be copying
That tutorial doesn't seem to however the website it uses seems to used a more advanced copy button
so I am going to try to recreate it from the source files of this website.

```html {data-file="_includes/codeHeader.html" data-copyable=true}
<div class="code-header">
  <button class="copy-code-button">
    Copy code to clipboard
  </button>
</div>
```
