## This is a full stack project using React + Vite, NodeJS Express

Steps to init project:

- ```npm create vite@latest -- --template react client``` install the packages in the 'client' folder
- ```npm install three @react-three/fiber @react-three/drei maath valtio react-color framer-motion``` install 3d packages
- ```npx tailwindcss init -p``` install tailwind packages. Then follow the guide [here](https://tailwindcss.com/docs/guides/vite) to complete the Tailwind settings.
How to install Tailwind in React: [view this article](https://www.freecodecamp.org/news/how-to-install-tailwindcss-in-react/)

- Update the web assets using the [files here](https://drive.google.com/drive/folders/166wA5NsMV_5D8NN7ujDDbPXC1X65vf2I)
- ES7+ React extension
-> Type `rafce` to init an arrow

- To run the project, cd to the project directory (in this case is the `client` folder)

- Dependencies on server side ```npm intall cloudinary cors dotenv express mongoose nodemon openai```

## Notes:

- B2B: Fix wrong commit after push
git commit --amend -m "your message"
git push --force origin main

- Shirt not rendered issue: In case of <mesh> or <Decal> broken, you'll need to reinstall drei package `npm install @react-thre
e/drei --latest`, also removed map-anisotropy={16} as it is no longer working

- If you encounter issues while deploying server, you might need to remove the package-lock.json

- You can host the web app on a backend server such as [render.com](https://render.com/)

- If the AIPicker doesn't work, it could be due to the expiry of OpenAI key


Shout out to JS Mastery for the instruction
