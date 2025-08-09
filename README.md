# Node.js Demo App with CI/CD

This is a sample Node.js application that uses GitHub Actions to build a Docker image and push it to Docker Hub.

## Steps to Use

1. **Create a GitHub Repo**  
   Create a new repository on GitHub and upload all files from this project.

2. **Set GitHub Secrets**  
   Go to your repository → Settings → Secrets and variables → Actions → New repository secret:  
   - `DOCKERHUB_USERNAME` = Your Docker Hub username  
   - `DOCKERHUB_TOKEN` = Your Docker Hub access token

3. **Push to main branch**  
   Commit and push changes to the `main` branch. The workflow will automatically run.

4. **Check Docker Hub**  
   The image will be available in your Docker Hub account.

---

Created for DevOps Task 1 Internship
