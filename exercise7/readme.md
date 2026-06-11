**1. No and here’s why the analogy holds perfectly.**
No, CSS needs something to style without HTML there’s nothing there. It’s like showing up with paint and furniture but there’s no building to put them in. You can have HTML without CSS (it’ll just look plain), but CSS alone is useless the browser has nothing to work with.

**2. Real scenario where inline CSS becomes a problem:**
Say you build a shopping site with 200 “Add to Cart” buttons, all styled inline with style="background-color=blue"
Your client then says “actually make all buttons green.”
Now you have to manually go into every single button and change it one by one. Miss one and the site looks inconsistent.
With external CSS you just change one line in one file and every button on the site updates at the same time. Done in seconds.

**3. Green and here’s why.**
Even though p comes first, .highlight is more specific. A class selector targets one specific group of elements you chose to label, while p targets every single paragraph on the page. The browser sees .highlight as a more precise instruction and follows it.
Think of it like this if someone says “everyone sit down” and then says “Abdul, stand up” you stand up. The specific instruction beats the general one.

**4. Why teach four color formats instead of one**

- Named colors — just type the word and move on. When you’re testing something quickly you don’t want to stop and Google a hex code, just write red and keep building.
- Hex — this is what designers speak. When someone sends you a Figma file every color in it will be a hex code, so you need to understand it just to communicate with the people you’ll work with.
- RGB — when your JavaScript needs to change a color dynamically, numbers are much easier to work with than a hex string. You can do math with numbers, you can’t do math with #ff0000.
- HSL — this one actually makes sense to your brain. If you want a lighter version of a color just bump the lightness up. You don’t need a color picker, you just think “darker” and turn the number down. Hex and RGB can’t do that.​​​​​​​​​​​​​​​​
