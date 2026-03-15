# web3-fullstack
A full stack web3 on-chain blog and CMS built with JavaScript. This project allows users to create, manage, and deploy their own blockchain-based blog, with all data stored on-chain.

## What it does
This repo provides a basic structure for a web3 blog, including user authentication, post creation and editing, and a simple content management system. It's designed to be modular and customizable, so you can easily add or remove features as needed.

## Getting started
To run the project locally, follow these steps:
1. Clone the repo: `git clone https://github.com/your-username/web3-fullstack.git`
2. Install dependencies: `npm install`
3. Start the development server: `npm run start`

## Example usage
Create a new blog post by sending a transaction to the `createPost` function, passing in the post title and content as arguments. For example:
```javascript
const postTitle = 'My first blog post';
const postContent = 'This is the content of my first blog post';
await contract.createPost(postTitle, postContent);
```
This will create a new post on the blockchain, which can then be retrieved and displayed on the frontend.

Note: This is just a starting point, and you'll need to modify the code to suit your specific use case. Be sure to check out the [issues](https://github.com/your-username/web3-fullstack/issues) page for known bugs and areas for improvement.