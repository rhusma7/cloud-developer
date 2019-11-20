# cloud-developer
Udacity Cloud Developer Nanodegree
Udagram Image Filtering 
Tasks
Setup Node Enviornment

You'll need to create a new node server. Open a new terminal within the project directory and run:

    Initialize a new project: npm i
    run the development server with npm run dev

Create a new endpoint in the server.ts file

The starter code has a task for you to complete an endpoint in ./src/server.ts which uses query paramater to download an image from a public URL, filter the image, and return the result.

We've included a few helper functions to handle some of these concepts and we're importing it for you at the top of the ./src/server.ts file.

import {filterImageFromURL, deleteLocalFiles} from './util/util';

Deploying your system

Follow the process described in the course to eb init a new application and eb create a new enviornment to deploy your image-filter service! Don't forget you can use eb deploy to push changes.
