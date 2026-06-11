# Scenario A

- The text color is Red
- It is not underlined
- It is Aligned Center

- The logic behind my answers is inline CSS which always wins over internal and external CSS.

# Scenario B

- Arial, sans-serif, the p rule overrides the body rule directly.

- Yes they are thesame color
- Hex=33 Math=(3\*16)+3 =51, All three pairs are 33 so result is rgb(51, 51, 51 ).

# If you remove the p rule

- Paragraph inherit the body font-family " "Poppins", sans-serif", because font-family is an inherited property, children automatically take the parents value.

# Scenario C

- hsl(240, 100%, 50%);
- Because the second rule comes later in the file and targets the exact same selector h1. It overwrites the first one.
- The Cascade — when two rules have the same selector and same property, the one that appears last in the CSS file wins. This is literally where the “C” in CSS comes from — Cascading Style Sheets.​​​​​​​​​​​​​​​​
