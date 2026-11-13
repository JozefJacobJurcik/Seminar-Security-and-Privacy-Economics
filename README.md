# Seminar: Security and Privacy Economics

Obsidian vault for the advanced seminar *Security and Privacy Economics*.  Open this folder as a vault in Obsidian and start at `00 Home.md`.

## Structure
```
00 Home.md              entry point: navigation and milestones
01 Course/              course overview and slides
02 Literature/          one note per paper and the literature index
03 Deliverables/
  Topic Presentation/   note + Latest/ + Versions/
  Seminar Paper/        note + Latest/ + Versions/
  Seminar Talk/         note + Latest/ + Versions/
04 Meetings/            team and professor meeting notes
Templates/              Obsidian templates (paper note, meeting note)
Attachments/            images and files embedded in notes
scripts/                data collection and analysis code
```

### Deliverable versions
- `Latest/` holds only the current file, with a stable name (e.g. `Seminar Paper.pdf`), so links to it keep working.
- `Versions/` holds dated snapshots. When you submit something or reach a milestone, copy the current file here as `YYYY-MM-DD <Deliverable> - <label>.<ext>`, e.g. `2027-01-29 Seminar Paper - First Draft.pdf`.

## Obsidian setup
`.obsidian/` is gitignored, so everyone sets this up once after cloning.

1. **Open the vault:** in Obsidian, choose *Open folder as vault* and select this repository folder.
2. **Attachments go to `Attachments/`:** *Settings → Files and links → Default location for new attachments* → *In the folder specified below*. Then set *Attachment folder path* to `Attachments`. Images and files you paste or drag into a note are now saved there.
3. **Templates:** *Settings → Core plugins* → turn on *Templates*. Then in *Settings → Templates*, set *Template folder location* to `Templates`. To use one, open the command palette (`Ctrl/Cmd+P`) and run *Templates: Insert template*.
4. **Show all file types (recommended):** *Settings → Files and links* → turn on *Detect all file extensions*. Without it, `.pptx`, `.docx`, `.tex` and similar files in `03 Deliverables/` won't appear in the file explorer.
