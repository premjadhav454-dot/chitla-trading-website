CHITLA TRADING - DEPLOY STEPS (GitHub + Vercel)
1. Unzip. Open the unzipped folder: you must see index.html, about.html, css, js, images directly inside it.
2. Copy ALL of that into your project folder (replace old files). Delete any old Images / CSS / JS folders with capital letters.
3. VS Code terminal:  git add .   then   git commit -m "Update website"   then   git push
4. Vercel: Settings > Root Directory must be empty (or the folder that has index.html). Framework Preset = Other. No build command.
5. After deploy press Ctrl+Shift+R. Test: yoursite.vercel.app/css/style.css must show code, not 404.
