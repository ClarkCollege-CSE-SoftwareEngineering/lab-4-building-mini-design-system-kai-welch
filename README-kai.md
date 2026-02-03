***CSE325 / Lab 4 / Kai Welch / Feb 2 2026***

# Reflection Section
> Notice how the Button component uses spacing.xs, spacing.sm, etc. instead of hardcoded values like '4px', '8px'. What would you need to change if your design team decided to increase all spacing by 2px?
- I would need to add another size that is 2px smaller than current setting. For example, if it's sm: '8px', I would need to make 6px field. Then apply it in atoms/Button.tsx.

> The Alert molecule imports and uses Icon, Text, and Button atoms. If you needed to update how all buttons look across your entire application, how many files would you need to change? How does this demonstrate Frost's point about the value of atomic design?
- I would only need to change Button.tsx to change how buttons look. I would also need to spacing.ts or typography.ts if I'm changing spacing or fonts of the buttons. 

> How does composing the Alert molecule from Icon, Text, and Button atoms demonstrate the value of atomic design?
- Atoms makes easy to make a molecule because ther are already a set of components I can place. 

> What role do design tokens play in maintaining consistency across your components? 
- It reduces the work to maintain and modify while keeping the design consistent because when I want to make a change in design, I can do so by editing one file and it can be applied to the whole system.

> If you needed to add a "dark mode" to this design system, what would you need to change?
- I would need to add another sturct of color set in tokens/colors.ts. 

# Key Concepts