# AI Short Film Prompt Generator

A lightweight Vietnamese prompt-generator web app for preparing Muse prompts from character reference images.

## Features
- Upload and preview a character reference image locally in the browser.
- Generate a complete prompt for a 60-second short film split into six consecutive 10-second clips.
- Southern Vietnamese voice/accent lock, dialogue continuity, character/style/lighting/color continuity instructions.
- Optional story, dialogue, style, ending, and aspect-ratio customization.
- Copy the prompt or download it as a `.txt` file.
- No API key, backend, framework, or build step.

## Important limitation
This app generates instructions; it does not analyze the image with an AI model or call Muse. Attach the same reference image to your Muse request along with the generated prompt. For better continuity, reuse the character reference on each clip and, if supported, use the previous clip's final frame as the next clip's input image.

## Deploy to GitHub Pages
1. Create a new GitHub repository, e.g. `ai-short-film-prompt-generator`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Open the published URL shown in Pages settings.

Everything runs client-side. Uploaded images are only previewed in the browser and are not uploaded anywhere by this app.
