# Contributing

## Add or update a component

1. Add/update design in `Figma` and develop in `packages/components/src/`.
3. Add/update stories for its normal, disabled, and relevant edge states.
4. Add interaction tests for important user behavior, include accessibility requirements following `WCAG` and `A11y`.
5. Check accessibility results in Storybook & link Figma preview.
6. Run the project checks before opening a pull request.

## Component conventions

- Use the `...-` prefix for custom-element names.
- Document public properties, events, slots, and CSS custom properties.
- Document the ways which accessibility is considered, and where relevant, the level of WCAG met.
- Use semantic HTML and support keyboard interaction.
- Prefer design tokens over hard-coded colors and spacing.