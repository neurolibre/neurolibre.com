# neurolibre.com
[![Netlify Status](https://api.netlify.com/api/v1/badges/8a148d2f-65f5-4d81-b2a5-de707b204822/deploy-status)](https://app.netlify.com/sites/angry-yalow-d7d0de/deploys)

This is the website of the Neurolibre publishing platform, an initiative of the Canadian Open Neuroscience Platform. The site is built with [hugo](https://gohugo.io/), deployed with [netlify](https://www.netlify.com/), and the content is populated automatically via [Neurolibre submissions](https://github.com/neurolibre/submit). 

To test it locally, you will need to:
1. Clone/fork this GitHub repo: `git clone https://github.com/neurolibre/neurolibre.com`
1. Make sure you're inside the **neurolibre.com/** directory (`cd neurolibre.com`), then **clone the submodule for themes:** `git submodule update --init --recursive --remote`
1. If [Hugo](https://gohugo.io/) is not installed, follow the steps in their documentation to install it on your machine: https://gohugo.io/getting-started/installing/
1. To run the website locally, make sure you are still in `neurolibre.com/` dir and type `hugo serve -D`.
   - The -D option is to serve the website including the draft .md files.

