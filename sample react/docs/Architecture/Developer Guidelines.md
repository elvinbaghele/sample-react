
# General Guidelines
### be very careful with the atoms, treat them like a library which anyone can use, avoid adding dependency and increase coupling.
- naming conventions `{name}.component.tsx` will be components.
- naming conventions `{name}.service.tsx` will be api calls.
- naming conventions `{name}.slice.tsx` will be reducers and actions.
- naming conventions `{name}.pages.tsx` will be layouts with outlets.
- `variable.css` will have css variables.
- `atomic.css` will have one liner css selectors.
- `{name}.css` will be imported from their respective folders example : `/src/components/auth/auth.css` will be imported to `/src/assets/styles/index.css`.
### Don't put every small thing onto redux, use this only if you need to use data in more than one place. 