This example covers all major CSS combinators and their practical applications:

1. Descendant Combinator (space):

   - Selects all descendants of a specified element
   - Example: `.container p` selects all paragraphs inside .container

2. Child Combinator (>):

   - Selects only direct children
   - Example: `.parent > span` selects only direct span children

3. Adjacent Sibling Combinator (+):

   - Selects element immediately following another
   - Example: `h2 + p` selects paragraphs directly after h2

4. General Sibling Combinator (~):
   - Selects all siblings following an element
   - Example: `h2 ~ p` selects all paragraphs after h2

Practical implementations shown include:

- Article layout structure
- Menu list styling
- Form layout and help text
- Card components
- Navigation menus
- Nested content structures
