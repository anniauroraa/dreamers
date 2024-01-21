# dreamers
This is a portfolio about a project implementation (hence this repository is not actually runnable)

The project was a part of course offered by Tampere university: HTI.800 - Human-Technology Interaction Research and Innovation Project. Our group consisted of three people total. I was more in charge of the technical research regarding machine learning implementations but I also participated in the user research and design itself. 

Our basic idea for the project was to create a mobile app for a dream diary enhanced with AI. It's three main functionalities are:
1. Log your dreams with text or speech and the app generates an image based on your prompt
2. "My dreams"-section where all your logged dreams are collected to
3. "My friends"-section where you share your generated images to each other

## Here's a link to the Figma prototype of the application: [Figma prototype](https://www.figma.com/proto/aMEYqbr9P0CepuHOBEjftN/Untitled?type=design&node-id=1-4909&t=cyuooBzEatgurFzw-1&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=1%3A4909&mode=design)
![image](https://github.com/anniauroraa/dreamers/assets/58393890/39bc02a3-dbef-421c-8e07-c11dffbd1a93)


## About the machine learning implementation
Basically the base for the machine learning implementation lays on top of AUTOMATIC1111 stable-diffusion implementation. For research about prompting and image generation I used the [automatic1111 webUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui) and then for the application implementation the plan would be to use the [automatic1111 api](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/API). In this repository there is an example script how the api can be used. I used one of the more special computers at the university for running the stable-diffusion model locally because my own hardware lacked the ability for it.

For the example images below I used stable-diffusion model called ReV Animated that I downloaded from [civitai.com](url). 

![image](https://github.com/anniauroraa/dreamers/assets/58393890/dff32597-7f40-4ddb-9a02-789c5ae5333b)

There is also an example how the prompt itself changes the image without changing any of the other parameters provided by the automatic1111 webUI. One of the key challenges will be learning to extract the best key words from the user’s dream because the AI model requires a specific syntax for efficient output.

![image](https://github.com/anniauroraa/dreamers/assets/58393890/f7e585ea-6fc1-402c-ae73-7ca05bd250d3)

