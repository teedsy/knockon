# stoka
AI-Powered Investment Signals
# Clone your repo
git clone https://github.com/teedsy/knockon.git
cd knockon

# Get the package with the auto-deploy workflow
curl -L -o knockon-ghpages.zip "sandbox:/mnt/data/knockon-ghpages.zip"  # if downloading from chat, otherwise just use the file you saved
unzip -o knockon-ghpages.zip

# Commit and push
git add .
git commit -m "Add static site and GitHub Pages workflow"
git push origin main

# Then in GitHub: Settings → Pages → Build and deployment = GitHub Actions
