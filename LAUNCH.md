# Launch instructions

## Start the demo locally

```powershell
cd "C:\Projects\Google photos project\demo"
node server.js
```

Then open:

- `http://localhost:3000` — case launcher
- `http://localhost:3000/kyoto/gallery.html` — Case 1 (Kyoto)
- `http://localhost:3000/kyoto_recurring/gallery.html` — Case 2 (Diwali)
- `http://localhost:3000/sharma/gallery.html` — Case 3 (Prescription)
- `http://localhost:3000/tokyo_layover/gallery.html` — Case 4 (Tokyo)

## Rules while editing

- Nothing runs/edits unless the message contains `okay run this` (see AGENTS.md)

## Revert point if needed

```powershell
cd "C:\Projects\Google photos project\demo"
git reset --hard backup-pre-pads
```

Or restore from `C:\Projects\Google photos project\demo_backup`.

## Pending

- Cases 2/3/4: enlarge candidate spaces like Case 1 (48 tiles) — Case 1 done
- Blue arrows removal was Case 1 only — check if other cases have the same floating buttons

## Tomorrow's log

1. Broken images across the whole gallery — non-rendering tiles need fixing
2. `journey.html` scroll journey — drop it altogether
3. Case 3 (Sharma) output/confirm screen needs fixing
