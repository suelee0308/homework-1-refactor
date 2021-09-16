# homework-1-refactor
## HTML Changes Made
1. Changed first **div element** to **header element** because element contains a h1 header at the top of the page.

2.  Within the new **header element** changed **div element** that contains the ul into **nav element** because the list is a navigation bar on the webpage.

3. Changed **div element** that contains class="hero" to a **figure element** because it contains an image in the css file.

4. Changed **div element** with class="content" to **main element** because it contains the main content of the page.

5. Within the new **main element**, changed the three **div elements** to be three **article elements** because there are three self contained content areas within the main content.

6. Changed the **div element** after main to be an **aside element** because it contains content aside from the main page content.

7. Within the new **aside element**, change the three **div elements** to three **article elements** because there are three distinct content elements within the aside.

8. Changed last **div element** to **footer element** because this element contains a footer.

9. Changed the **h2** in the **footer** to an **h4** because it is last in the hierarchy of headers.

10. Added **alt** attributes to all **img elements** and **figure element** for accessibility.

11. Added missing **id** element to the first **article** within the **main element** so that the navbar link works. Link was broken initially.


---

## CSS Changes Made
1. Changed all **header div** elements to **header nav** elements to effect all the new **nav** elements in the html.

2. Reduced **.benefit-lead**, **.benefit-brand**, **.benefit-cost**, to one selector **aside-artcle** because all articles within the aside had the same styles.

3. Reduced **.benefit-lead h3**, **.benefit-brand h3**, **.benefit-cost h3**, to one selector **aside-artcle h3** because all h3 elements had the same styles.

4. Reduced **.benefit-lead img**, **.benefit-brand img**, **.benefit-cost img**, to one selector **aside-artcle img** because all images within the aside had the same styles.

5. Reduced **.search-engine-optimization**, **.online-repuation-management**, **.social-media-marketing**, to one selector **main article** because all articles within the main element had the same styles.

6. Reduced **.search-engine-optimization img**, **.online-repuation-management img**, **.social-media-marketing img**, to one selector **main article img** because all images within the main element had the same styles.

7. Reduced **.search-engine-optimization h2**, **.online-repuation-management h2**, **.social-media-marketing h2**, to one selector **main article h2** because all h2 within the main element had the same styles.

8. Changed **.footer h2** to **h4** because html changes. 

---

## Other notes
- HTML and CSS was done individually.
- W3 schools HTML semantics was used to change div tags.
- Read through classmate's README before writing mine.

## Mistakes made along the way
- Oversimplified CSS and broke href key. Had to redo CSS refactoring (which was out of the scope of this activity) but in refactoring, I commented out the original CSS that was repetitive instead of completely deleting it, which helped fix the CSS easier than when I had broken it.
- Wrote README after completing the HTML and CSS changes. Thought pushing changes along the way was enough.