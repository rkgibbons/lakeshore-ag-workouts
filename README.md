# Lakeshore AG Workouts

Age Group swim workouts for Lakeshore Stingrays.

## Folder Structure

- **Templates/**: Blank templates for creating new workouts
- **2026 LC/**: Long course workouts for 2026 season
- **Drylands/**: Dryland templates and workouts

## Workflow

Open and edit `Templates/swim_practice_template.tex` directly, then push it
to GitHub. In VS Code, use **Terminal > Run Task** (or `Cmd+Shift+P` >
`Tasks: Run Task`) and choose:

- **Open Practice Template** — opens the template for editing
- **Push Practice Template** — commits and pushes the template to GitHub

Or run the equivalent commands yourself:

```bash
cd ~/lakeshore-ag-workouts
git add Templates/swim_practice_template.tex
git commit -m "Update practice template"
git push
```
