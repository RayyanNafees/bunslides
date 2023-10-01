# Bun slides
Astro project initialised with Bun

## Steps to reproduce in WSL Ubuntu
1. Update apt
  ```bash
  sudo apt update
  sudo apt-get update
  ```
2. Install Node v12
  ```bash
  sudo apt-get install nodejs
  sudo snap install node
  ```
3. Install nvm to update to Node v20
  ```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
  nvm install 20
  ```
4. Install Bun runtime (supports Node v18+)
  ```bash
  curl -sS https://bun.sh.install | bash
  ```
5. Regular Astro project setup but this time with Bun 🚀
  ```
  mkdir astro
  cd astro
  bun create astro@latest <project> -- --template minimal
  ```

## Problems
None so far :)
