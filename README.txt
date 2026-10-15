Make DexifyLeagueMobile.apk without installing anything (GitHub does the build)
1. Make a free account at github.com and click New repository. Name it dexifyleague-mobile, keep it Private, click Create.
2. On the empty repo page click "uploading an existing file". Open this unzipped folder and drag EVERYTHING in it (app, gradle, .github, build.gradle, settings.gradle, gradle.properties) into the page. Click Commit changes.
   If the .github folder doesn't upload: click Add file > Create new file, type  .github/workflows/build.yml  as the name, paste the text from that file in this folder, and commit.
3. Click the Actions tab. A run called "Build APK" starts by itself (if asked, click "I understand my workflows, go ahead and enable them"). Wait about 3 minutes for the green tick.
4. Click the run, scroll to Artifacts, click DexifyLeagueMobile-apk to download a zip. Inside is app-debug.apk.
5. Send app-debug.apk to your phone, open it and allow "install unknown apps".
