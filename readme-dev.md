# https://nextjs.org/docs

# Install npm and dependencies
sudo apt install npm

npm install -g typescript
npm install next react react-dom
npm install --save gray-matter
npm install next-mdx-enhanced
npm install @mapbox/rehype-prism

# To build and run locally
# see the build commands in package.json
npm run dev

# Check if production build will succeed before pushing
# see the command in netlify.toml 
npm run export

