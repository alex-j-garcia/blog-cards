# UI Cards
A set of non-responsive cards, styled with CSS. Inspired by [this](https://www.uidesigndaily.com/posts/sketch-blog-cards-post-article-thumbnail-day-997) mockup on UI Design Daily:

**Source**
![Original UI Cards](assets/original-cards.png)

## My Approach
![My UI Cards](assets/my-cards.png)

I've layed the cards out using float, which might not be ideal, but I wanted to experiment with this technique and solidify my learning. The divs that contain the author information are positioned at the bottom of the cards using absolute positioning inside a relatively positioned element. The card header images use `object-fit` to size the images.

**In hindsight...**
* I assigned an explicit height to all the cards. There is a risk of overflow with this approach and the cards will not dynamically size should the content change. I would use a different layout technique, such as flexbox, that keeps child element size uniform without being explicit.
