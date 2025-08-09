# Minimal Docker Project for Docker Hub

## Steps to use in GitHub Codespaces

1. Open this repo in **GitHub Codespaces**.
2. Install Docker in Codespaces terminal:
   ```bash
   sudo apt update && sudo apt install -y docker.io
   sudo service docker start
   ```
3. Log in to Docker Hub:
   ```bash
   docker login
   ```
4. Build the image (replace `myusername` with your Docker Hub username):
   ```bash
   docker build -t myusername/myimage:latest .
   ```
5. Push to Docker Hub:
   ```bash
   docker push myusername/myimage:latest
   ```

After that, your image will be available in your Docker Hub repository.
