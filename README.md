# Dall-E with MERN stack

Tutorial:
[Build and Deploy a Full Stack MERN AI Image Generation App | Midjourney & DALL-E Clone](https://www.youtube.com/watch?v=EyIvuigqDoA)

## Setup

Frontend:
1. `mkdir client`
2. `cd client`
3. `npm create vite@latest ./` then choose React framework and JavaScript variant.

4. Install TailwindCSS:
- `npm install -D tailwindcss postcss autoprefixer`
- `npx tailwindcss init -p`

5. `npm i file-saver`

Backend:
1. In root, type `mkdir server`
2. `cd server`
3. `npm init -y`
4. In the package.json file:
- Add to scripts: `"start": "nodemon index"`.
- Add below description: `"type": "module",` so that we can use ES6 import/exports instead of require statements.
5. `npm i cloudinary cors dotenv express mongoose nodemon openai`

### Run

Start frontend in `client` directory:
```
npm run dev
```

Start server in `server` directory:
```
npm start
```