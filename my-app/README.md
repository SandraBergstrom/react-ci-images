# Getting Started

### In the terminal do:
<code>cd my-app</code>

<code>nvm install 16 && nvm use 16</code>

<code>npm install</code>

### You can then run the project with the command
<code>npm start</code>

### Items to be aware of
Inside the folder named src you will find a file named posts.json. This file will not be used until a challenge later in the content.  

For convenience react comes installed in this template. A package named axios has also been installed as it will be required in a challenge later.

### Bug

- If you get "sh: 1: react-scripts: not found" when trying to run npm start - navigate to my-app and run "npm install" .

- If you get the following error message:
opensslErrorStack: [ 'error:03000086:digital envelope routines::initialization error' ], library: 'digital envelope routines', reason: 'unsupported', code: 'ERR_OSSL_EVP_UNSUPPORTED'

then type the following in the terminal and then run npm start again:

export NODE_OPTIONS=--openssl-legacy-provider


