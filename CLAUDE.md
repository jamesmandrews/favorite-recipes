# Claude Code Rules

## Git Commits
- Never add `Co-Authored-By` lines to commit messages
- Never add any AI/Claude/Anthropic attribution to commits

## Recipes
- When adding a new recipe, always add it to the README.md in the appropriate category section, in alphabetical order
- All recipe files live under `recipes/` organized by category (appetizers, breads, desserts, mains, sauces, sides)
- Always translate recipes to English
- Always include both imperial and metric measurements. If a recipe only has one system, convert and add the other
- **All recipes MUST follow this format** (see `recipes/mains/pork/filipino-adobo-pork-ribs.md` as reference):
  1. `# Title`
  2. `> Short description` (blockquote)
  3. `## Details` — metadata in a two-column table (Source, Cuisine, Servings, Prep Time, Cook Time, etc.)
  4. `## Ingredients` — tables with columns: `Ingredient | Imperial | Metric` (never a single "Amount" column). Use `### Subsection` headings to group ingredients when needed
  5. `## Instructions` — use `### Step Name` subsection headings to group related steps
  6. `## Notes` — bullet list
  7. `---` followed by `**Tags:**` line with backtick-wrapped hashtags
