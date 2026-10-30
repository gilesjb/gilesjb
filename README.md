# It's me 

## Fun fact about me

### Amazon droppings

If you look at the page source for any Amazon page, you'll see lots of comments like this
```html
<!-- sp:feature:aui-assets -->
```
These markers originate from a system called Shopping Portal,
which I conceived of and led the development team.
One of the things Shopping Portal does is insert content blocks ("features") into every page.
In this case the feature being inserted is the JavaScript and CSS assets required by the Amazon UI framework.
(I was also the original lead engineer for the AUI team.)

Shopping Portal solves the problem of ensuring that every page on the Amazon website gets consistent up-to-date
versions of site-wide assets and standard features like the navigation bar and footer.

*You may observe that dynamically inserting content into HTML streams (as Shopping Portal does)
does not play well with client-side-rendering or Next.js.
You would be correct about this!
Amazon very intentionally uses good ole server-side HTML rendering because it's the quickest way to get content to a user's browser,
and online shoppers are very sensitive to how fast webpages are.

<!--
**gilesjb/gilesjb** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
