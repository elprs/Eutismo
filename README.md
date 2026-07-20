# Visual Classroom Schedule

Static classroom pilot prepared for GitHub and Vercel.

## Files

- `index.html` — landing page
- `teacher.html` — teacher controls
- `display.html` — student-facing classroom display
- `vercel.json` — static Vercel settings and basic security headers
- `AUDIO_ASSET_POLICY.md` — audio licensing guidance

## Deploy through GitHub and Vercel

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In Vercel, create a new project and import the GitHub repository.
4. Leave Framework Preset as **Other**.
5. Do not set a build command.
6. Leave the output directory empty.
7. Deploy.

After deployment:

- `/` opens the landing page.
- `/teacher` opens Teacher Control because clean URLs are enabled.
- `/display` opens Classroom Display.

## Important pilot limitations

- Teacher and display synchronization currently uses browser-local storage and `BroadcastChannel`.
- It works best in two windows or tabs of the same browser profile on one computer.
- Separate devices will require a real-time backend in a later version.
- Uploaded pictures, schedules, and audio are stored locally in that browser and are not yet shared across devices.
- Do not store student-identifying information in this pilot.
