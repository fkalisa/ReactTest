# Getting Started with Create React App

- npm run start
- npm run test
- 
- CI=true npm run test
- CI=true npm run test -- --coverage
- npm run build : optimised for production

# Deploying using surge

-- deploying static content 

project: add build at the end
/Users/florakalisa/Documents/dev/devops/github-actions/react-demo/build
[magical-zipper.surge.sh]()

- surge

# Code formatting withno prettier

https://prettier.io/docs/en/install.html

the rule for format are : .prettierrc

npm install --save-dev --save-exact prettier

npx prettier --check "**/*.js"

npx prettier --write "**/*.js" 

npm run format:check
