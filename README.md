#  TASK-6-Host-a-Static-Website-with-GitHub-Pages

# Objective:
- Deploy a simple HTML (static) website using GitHub Pages.
# Tools Required:
- GitHub Pages
# Deliverables:
- App link: https://ramakrishnaragi.github.io/TASK-6-Host-a-Static-Website-with-GitHub-Pages/
- Repo link: https://github.com/Ramakrishnaragi/TASK-6-Host-a-Static-Website-with-GitHub-Pages.git
# Step-by-Step Guide:
- mkdir TASK 6: Host a Static Website with GitHub Pages
- cd TASK 6: Host a Static Website with GitHub Pages
#  Step 1: Create a simple index.html
```sh
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My GitHub Page</title>
  <link rel="stylesheet" href="style.css" />  # this link is fetching from style.css
</head>
<body>
  <div class="container">
    <h1>🚀Welcome to my Devops site!</h1>
    <p>Welcome to my static website hosted on GitHub Pages.</p>
  </div>
</body>
</html>
```
# Create a file style.css
```sh
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #a8d5a2; /* Nice soft green */
    color: #fff; /* White text for contrast */
  }
  
  .container {
    text-align: center;
    padding: 100px 20px;
    background-color: #a8d5a2; /* Same green background for full consistency */
    max-width: 100%;
    margin: 0;
  }
  
  h1 {
    color: #ffffff; /* White heading text */
    font-size: 3em;
    margin-bottom: 10px;
    background-color: #70b570; /* Slightly darker green behind heading */
    padding: 20px;
    border-radius: 10px;
  }
  
  p {
    font-size: 1.2em;
    background-color: #89c789; /* Light green behind paragraph */
    padding: 15px;
    border-radius: 10px;
    display: inline-block;
    color: #fff;
  }
```
# Step 2: Initialize Git and Push to GitHub
  # Follow this cmds:
  - git init
  - git add .
  - git commit -m "initial commit"
  - git branch -M main
  - git remote add origin https://github.com/<your-username>/my-static-site.git
  - git push -u origin main
![image](https://github.com/user-attachments/assets/db6e5ca0-d2a2-4385-acd2-fc3b185796c3)
# After files are pushed into github repo automatically action will work and complete the Build ---> report build status ---> deploy

![image](https://github.com/user-attachments/assets/e5593b10-f435-4caa-90fd-17cb44c53b77)

# Once check the pages in repo
    > Enable GitHub Pages:
    - Go to your repo on Github
    - Click setting ----> pages
    - Under source, choose: deploy from a branch
      Branch: main
      Folder: / root
    - Click save
    - GitHub will give you a live website link after a few seconds.

![image](https://github.com/user-attachments/assets/0ecc522c-41f9-48db-ac18-320a93b4834c)


# Then finally access the application use for github provided link:
-  https://yourusername.github.io/your-repo-name/

  
![image](https://github.com/user-attachments/assets/b4bd28bb-ab77-4873-840f-096fe53fbb5e)

#   THANKYOU
