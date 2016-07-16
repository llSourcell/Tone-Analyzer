Overview
============
This is a Tone Analyzer demo written in Javascript using Node.js. This is the code for the Tone Analysis Episode of Fresh Machine Learning on [Youtube](https://youtu.be/_ZqB9zUgi2w). The code is a simple node.js web app. It creates an HTML form for the user to submit some text on the index page. Once they hit submit, it will use that text as a parameter and query the [Watson Tone Analyzer API](http://www.ibm.com/watson/developercloud/tone-analyzer.html). The API will return the tone analysis as JSON that you can view in terminal. 

Dependencies
============
* npm - (https://docs.npmjs.com/cli/install)
* node - (https://nodejs.org/en/)

Basic Usage
===========

Step 0 - Make sure to sign up for IBM's [BlueMix](http://www.ibm.com/cloud-computing/bluemix/) and sign up for the Tone Analyzer service. Use those credentials and replace the dummy credentials in the index.js file on lines 31 and 32 with your own.

Step 1 - Once you've downloaded the repo, in the main directory you can just type the following into terminal

```shell
npm install
```
This will install all of your dependencies from the package.json, including the Watson Developer Cloud npm module. 

Step 2 - Once your dependencies are installed, you can go ahead and run the app via

```shell
node index.js
```
Step 3 - Go to [http://localhost:3000](http://localhost:3000/) in your browser to see the web app. Input some text that you'd like
tone analyzed and hit the submit button. In terminal, you'll see the JSON response appear from the Watson API. These are all the percent estimations for a variety of emotional and sentimental areas of your text.

Credits
===========
Initially created by Siraj Raval but maintained by everybody.
