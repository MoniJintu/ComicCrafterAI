
# Comic Crafter AI


A React application which uses  an API to generate 10 comic images from text prompt and creates a strip. The strip of images can be resized and rearranged to download a suitable comic image.

A screenshot of an example comic generation:
![Screenshot from 2023-11-27 09-11-59](https://github.com/rashmigr01/comic-creator/assets/77162931/26b7e25f-9e28-4671-af3a-660340a12eeb)

## INTRODUCTION 
ComicCrafter AI is a generative AI-based comic creation tool designed to run entirely on local edge devices. It empowers users to bring their stories to life in a comic-style format using simple text prompts .By leveraging on-device AI capabilities, ComicCrafter AI ensures faster generation times, enhanced privacy, and full creative control, making it an ideal solution for storytellers, hobbyists, and comic enthusiasts who want to generate content anytime, anywhere.
## Tech Stack

To implement the application, the following tech was used:

**Backend:** Node.js

**Frontend:** React


**Libraries:** react-grid-layout, html2canvas

**Deployment:** gh-pages



## Run Locally

#### Clone the project:

Create a local copy of this repository on your machine. You can use github cli/ssh keys as some other options!

```bash
  git clone 
```

#### Go to the project directory:

Switch to the installed directory with a simple cd command.

```bash
  cd Comic-Crafter-AI
  ```


#### Install dependencies:

Install the necessary dependencies packages to your system with the following command.

```bash
  npm install
```

#### Run the development server:

To begin a development server execute the below command. This command will start the development server, and you should be able to access your React app at http://localhost:3000 in your web browser. You can stop the sever with `Ctrl + C`.

```bash
  npm start
```

Build the Production Version:

Optionally, create a production-ready build with this command which generates an optimized and minified build in the `build` folder.

```bash
  npm run build
```

Deploy:

To deploy to gh-pages, with preset scripts, the following command is useful.

```bash
  npm run deploy
```

However, it is not recommended that you deploy directly without running the workflows setup on github for lint checks and tests.

## Development Operations

After the above local installation, you can perform development operations to modify and extend the application.

The application is created using `create-react-app`. Read more about it [here](https://create-react-app.dev/).

During development, you can install packages to use frameworks or libraries using the following command:

```bash
  npm install your_package --save-dev
```

The main code base architecture can be visualized as follows:

![image](https://github.com/rashmigr01/comic-creator/assets/77162931/2066eb03-b591-45ae-b590-5886e17790f7)

The `AppLayout` along with the two main files of `ComicForm` and `ComicDisplay` are responsible for the functionality. Another file of interest is the `GenerateComic` API call function which is responsible for the text to image generation.

    
## Examples

Here are some comic examples as output by the application:

#### Comic 1

![comic_strip_6](https://github.com/rashmigr01/comic-creator/assets/77162931/5405910a-49a3-4f14-b8cc-ca71d71f6179)

#### Comic 2

![comic_display (5)](https://github.com/rashmigr01/comic-creator/assets/77162931/e904b0ff-c5e5-4b70-a842-f1f7705e087b)


## User Flow

The following steps are part of the user flow on the comic creator:

- Input text prompts for all 10 panels and click on the `GENERATE COMIC` button to make API calls.
![image](https://github.com/rashmigr01/comic-creator/assets/77162931/65f1b734-eeb1-4c0c-8ce5-d2ef0f444c0b)

- The progress bar depicts the number of returned API calls out of ten and thus the number of generated images.
![Screenshot from 2023-11-27 09-08-53](https://github.com/rashmigr01/comic-creator/assets/77162931/af6fa7eb-1f91-40bc-b629-cf6501975c4e)

- The default comic strip of a vertical layout is created.
![Screenshot from 2023-11-27 09-10-08](https://github.com/rashmigr01/comic-creator/assets/77162931/82c3e793-154a-4fd4-83e1-0160e95413d0)

- The pictures can be resized and reordered to create a more appealing and suitable comic strip.
![Screenshot from 2023-11-27 09-11-59](https://github.com/rashmigr01/comic-creator/assets/77162931/729d5a5c-bcb6-454a-a697-610db3dceedd)



- Click on the `DOWNLOAD IMAGE` button to download a `comic_strip.png` image of the current strip.
![comic_strip_6](https://github.com/rashmigr01/comic-creator/assets/77162931/5405910a-49a3-4f14-b8cc-ca71d71f6179)

- Repeat the above steps to create more comics.
## Acknowledgements

We would also like to acknowledge  hugging face Large Language Model, which is central to our project.

Special thanks to the open-source and educational AI communities for their continued inspiration and innovation.

## Team Member

1. Jintu moni nath 
