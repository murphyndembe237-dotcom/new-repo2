
# Configure your identity (only needed once per computer)
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

# Initialize a new repository
git init

# Stage all files in the folder
git add .

# Save your work with a message
git commit -m "Added my first C program"

# Connect your repo to GitHub (replace URL with yours)
git remote add origin https://github.com/username/my-first-repo.git

# Upload your code to GitHub
git push -u origin main

# If you want to get the latest changes from GitHub
git pull origin main
