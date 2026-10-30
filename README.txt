TASTY SWOOP — GITHUB PAGES SITE

This ZIP contains a complete static support website: index.html, privacy/, terms/, contact/, assets/ and .nojekyll. No build tools, API keys, accounts for visitors, analytics or external font services are required.

The public contact is Vladyslav Manoilo / vladislavmanoilo@gmail.com.

PUBLISH ON GITHUB PAGES
1. Create a repository for the site, for example tasty-swoop-support. GitHub Free supports Pages from public repositories.
2. Extract this ZIP. Put index.html, privacy/, terms/, contact/, assets/ and .nojekyll at the repository root. Upload the extracted files, not the ZIP itself. Keep the directory structure. README.txt may remain at the root.
3. In the repository, open Settings → Pages. Choose Deploy from a branch, then main and /(root), and save.
4. Wait until GitHub reports the deployment's URL. For a project site it normally looks like https://YOUR-GITHUB-OWNER.github.io/YOUR-REPOSITORY/ — that is a pattern, not a URL this package has published.
5. Open the public site and its Privacy, Terms and Contact pages. Confirm HTTPS and the email link before using the URLs in App Store Connect.

APP STORE CONNECT URLS
Support URL:       <your published site URL>contact/
Privacy Policy:    <your published site URL>privacy/
Marketing URL:     <your published site URL>
Terms of Use:      <your published site URL>terms/

For example, if the site root is https://OWNER.github.io/tasty-swoop-support/, the Privacy Policy URL ends in /tasty-swoop-support/privacy/. Replace OWNER with the actual repository owner. No GitHub username or repository has been assumed or created.

PREVIEW LOCALLY
In the extracted folder, run: python3 -m http.server 8000
Open http://localhost:8000/ in a browser. Stop the local server with Control-C when done.

MAINTENANCE
Update contact details consistently in all four HTML pages. Update the policy if app data handling changes; keep its displayed date current. The app's bundled policy should match material website policy changes.

The site's privacy policy distinguishes offline app data from optional support email and GitHub's website security logs. Terms link to Apple's Standard EULA rather than pretending to replace it. No App Store badge/download link is fabricated before a real app listing exists.
