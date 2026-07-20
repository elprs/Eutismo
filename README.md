# Classroom Schedule — Vercel Static Deployment

Repository structure:

```
index.html
vercel.json
teacher/index.html
display/index.html
AUDIO_ASSET_POLICY.md
README.md
```

Vercel settings:
- Framework Preset: Other
- Root Directory: repository root
- Build Command: blank
- Output Directory: blank

Routes:
- `/`
- `/teacher/`
- `/display/`

Important: replace the old `vercel.json`. The old file used clean URLs and rewrites that could interfere with the folder routes.
