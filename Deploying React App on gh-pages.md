<h2> Deploying App on gh-pages </h2>
<b>Step 1:</b>
Run: npm i gh-pages <br><br>

<b>Step 2:</b>
Add "homepage": "https://amitkesari2000.github.io/Money_Planner-React" <br>
(i.e https://your_github_username.github.io/your_repo_name) <br>
Add  "deploy": "npm run build && gh-pages -d build" (in scripts object) <br>
Add above lines in package.json <br>
(See package.json file in this repo to clarify any doubts)

<b>Step 3:</b>
Run: npm run deploy

<h4>Your App is now hosted ;)</h4>
