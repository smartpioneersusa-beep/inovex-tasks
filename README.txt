INOVEX Task Manager — installable app (web address: https://tasks.inovex-group.com)

Upload this whole folder to Netlify (free):
1. Go to https://app.netlify.com/drop, sign in (free account), and drag this folder onto the page.
2. Site settings → Domain management → Add a domain → tasks.inovex-group.com → follow the prompt.
3. In Squarespace: Domains → inovex-group.com → DNS → Custom records → Add:
     Type CNAME · Host: tasks · Data: <your-site-name>.netlify.app
4. Wait up to an hour; Netlify switches on HTTPS by itself.
5. Share https://tasks.inovex-group.com/install.html with the team.

To change the portal's address later, edit config.js only.
