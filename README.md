<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
<<<<<<< HEAD
=======
<<<<<<< HEAD
# 🧑‍💻 What is [AI Engineering](https://maven.com/aimakerspace/ai-eng-bootcamp)?

AI Engineering refers to the industry-relevant skills that data science and engineering teams need to successfully **build, deploy, operate, and improve Large Language Model (LLM) applications in production environments**.  

In practice, this requires understanding both prototyping and production deployments.

During the *prototyping* phase, Prompt Engineering, [Retrieval Augmented Generation (RAG)](https://www.youtube.com/playlist?list=PLrSHiQgy4VjFlWgcLHatJCBgfeE8smVyP), and [Fine-Tuning](https://www.youtube.com/playlist?list=PLrSHiQgy4VjGMzyXsSlvN-TjPaqFFsAGP) are all necessary tools to be able to understand and leverage. Prototyping includes:
- Building RAG Applications
- Fine-Tuning LLMs & Embedding Models
- Building Agent/Reasoning Applications
- LLM Application Deployment

When *productionizing* LLM application prototypes, there are many important aspects ensuring helpful, harmless, honest, reliable, and scalable solutions for your customers or stakeholders. Productionizing includes:
- RAG Evaluation and Improvement
- Monitoring and Visibility Tooling
- Efficient Inference and Serving
- Scaling LLM Applications

This bootcamp builds on our two previous courses, [LLM Engineering](https://maven.com/aimakerspace/llm-engineering) and [LLM Operations](https://maven.com/aimakerspace/llmops) 👇

- Large Language Model Engineering (LLM Engineering) refers to the emerging best practices and tools for training, fine-tuning, and aligning LLMs before production deployment.  LLM Engineering is the counterpart to ML Engineering (MLE) which focuses on LLM-specific techniques like prompt engineering, reinforcement learning, quantization, and other methods required by this new paradigm.
    
- Large Language Model Ops (LLM Ops, or LLMOps (as from [WandB](https://docs.wandb.ai/guides/prompts) and [a16z](https://a16z.com/emerging-architectures-for-llm-applications/))) refers to the emerging best-practices, tooling, and improvement processes used to manage production LLM applications throughout the AI product lifecycle.  LLM Ops is a subset of Machine Learning Operations (MLOps) that focuses on LLM-specific infrastructure and ops capabilities required to build, deploy, monitor, and scale complex LLM applications in production environments.

# 🏆 **Grading and Certification**

To become **AI-Makerspace Certified**, which will open you up to additional opportunities for full and part-time work within our community and network, you must:

1. Complete all project assignments.
2. Complete a project and present during Demo Day.
3. Receive at least an 85% total grade in the course.

If you do not complete all assignments, participate in Demo Day, or maintain a high-quality standard of work, you may still be eligible for a *certificate of completion* if you miss no more than 2 live sessions.

# 📚 About

This GitHub repository is your gateway to mastering the art of AI Engineering.  ***All assignments for the course will be released here for your building, shipping, and sharing adventures!***

# 🙏 Contributions

We believe in the power of collaboration. Contributions, ideas, and feedback are highly encouraged! Let's build the ultimate resource for AI Engineering together.

Please to reach out with any questions or suggestions. 

Happy coding! 🚀🚀🚀

=======
# my-first-repo
>>>>>>> d460467 (Update README.md)
<<<<<<< HEAD
---
title: BeyondChatGPT Demo
emoji: 📉
colorFrom: pink
colorTo: yellow
sdk: docker
pinned: false
app_port: 7860
---

<<<<<<< HEAD
=======
## my task

Here are the things I need to accomplish
1. Get my machine setup
1. Get all my access keys
1. Write some code

All Done
>>>>>>> 2fc0375 (my first commit (#1))
=======
# Beyond-ChatGPT
<<<<<<< HEAD
<<<<<<< HEAD
Chainlit App using Python streaming for Level 0 MLOps
<<<<<<< HEAD
>>>>>>> 1f87be8 (Initial commit)
=======

LLM Application with Chainlit, Docker, and Huggingface Spaces
In this guide, we'll walk you through the steps to create a Language Learning Model (LLM) application using Chainlit, then containerize it using Docker, and finally deploy it on Huggingface Spaces.

Prerequisites
A GitHub account
Docker installed on your local machine
A Huggingface Spaces account


### Building our App
Clone [this](https://github.com/AI-Maker-Space/Beyond-ChatGPT/tree/main) repo.

``` bash
git clone https://github.com/AI-Maker-Space/Beyond-ChatGPT.git
```

Navigate inside this repo
```
cd Beyond-ChatGPT
```

Install the packages required for this python envirnoment in `requirements.txt`.
```
pip install -r requirements.txt
```

Open your `.env` file. Replace the `###` in your `.env` file with your OpenAI Key and save the file.
```
OPENAI_API_KEY=sk-###
```

Let's try deploying it locally. Make sure you're in the python environment where you installed Chainlit and OpenAI.

Run the app using Chainlit

```
chainlit run app.py -w
```

Great work! Let's see if we can interact with our chatbot.

Time to throw it into a docker container a prepare it for shipping

Build the Docker image. We'll tag our image as `llm-app` using the `-t` parameter. The `.` at the end means we want all of the files in our current directory to be added to our image.
``` bash
docker build -t llm-app .
```

Run and test the Docker image locally using the `run` command. The `-p`parameter connects our **host port #** to the left of the `:` to our **container port #** on the right.
``` bash
docker run -p 7860:7860 llm-app
```

Visit http://localhost:7860 in your browser to see if the app runs correctly.

Great! Time to ship!

### Deploy to Huggingface Spaces

Make sure you're logged into Huggingface Spaces CLI

``` bash
huggingface-cli login
```

Follow the prompts to authenticate.


Deploy to Huggingface Spaces


Create a new Huggingface Space

=======
=======
=======
---
title: BeyondChatGPT Demo
emoji: 📉
colorFrom: pink
colorTo: yellow
sdk: docker
pinned: false
---

>>>>>>> cabe14c (Update README.md)
>>>>>>> d460467 (Update README.md)
<p align = "center" draggable=”false” ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" 
     width="200px"
     height="auto"/>
</p>


## <h1 align="center" id="heading">:wave: Welcome to Beyond ChatGPT!!</h1>

For a step-by-step YouTube video walkthrough, watch this! [Deploying Chainlit app on Hugging Face](https://www.youtube.com/live/pRbbZcL0NMI?si=NAYhMZ_suAY84f06&t=2119)

![Beyond ChatGPT: Build Your First LLM Application](https://github.com/AI-Maker-Space/Beyond-ChatGPT/assets/48775140/cb7a74b8-28af-4d12-a008-8f5a51d47b4c)

## 🤖 Your First LLM App

> If you need an introduction to `git`, or information on how to set up API keys for the tools we'll be using in this repository - check out our [Interactive Dev Environment for LLM Development](https://github.com/AI-Maker-Space/Interactive-Dev-Environment-for-LLM-Development/tree/main) which has everything you'd need to get started in this repository!

In this repository, we'll walk you through the steps to create a Large Language Model (LLM) application using Chainlit, then containerize it using Docker, and finally deploy it on Huggingface Spaces.

Are you ready? Let's get started!

<details>
  <summary>🖥️ Accessing "gpt-3.5-turbo" (ChatGPT) like a developer</summary>

1. Head to [this notebook](https://colab.research.google.com/drive/1mOzbgf4a2SP5qQj33ZxTz2a01-5eXqk2?usp=sharing) and follow along with the instructions!

2. Complete the notebook and try out your own system/assistant messages!

That's it! Head to the next step and start building your application!

</details>


<details>
  <summary>🏗️ Building Your First LLM App</summary>

1. Clone [this](https://github.com/AI-Maker-Space/Beyond-ChatGPT/tree/main) repo.

     ``` bash
     git clone https://github.com/AI-Maker-Space/Beyond-ChatGPT.git
     ```

2. Navigate inside this repo
     ``` bash
     cd Beyond-ChatGPT
     ```

3. Install the packages required for this python envirnoment in `requirements.txt`.
     ``` bash
     pip install -r requirements.txt
     ``` 

4. Open your `.env` file. Replace the `###` in your `.env` file with your OpenAI Key and save the file.
     ``` bash
     OPENAI_API_KEY=sk-###
     ```

5. Let's try deploying it locally. Make sure you're in the python environment where you installed Chainlit and OpenAI. Run the app using Chainlit. This may take a minute to run.
     ``` bash
     chainlit run app.py -w
     ```

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/54bcccf9-12e2-4cef-ab53-585c1e2b0fb5"> 
</p>

Great work! Let's see if we can interact with our chatbot.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/854e4435-1dee-438a-9146-7174b39f7c61"> 
</p> 

Awesome! Time to throw it into a docker container and prepare it for shipping!
</details>



<details>
  <summary>🐳 Containerizing our App</summary>

1. Let's build the Docker image. We'll tag our image as `llm-app` using the `-t` parameter. The `.` at the end means we want all of the files in our current directory to be added to our image.
     
     ``` bash
     docker build -t llm-app .
     ```

2. Run and test the Docker image locally using the `run` command. The `-p`parameter connects our **host port #** to the left of the `:` to our **container port #** on the right.
    
     ``` bash
     docker run -p 7860:7860 llm-app
     ```

3. Visit http://localhost:7860 in your browser to see if the app runs correctly.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/2c764f25-09a0-431b-8d28-32246e0ca1b7"> 
</p>

Great! Time to ship!
</details>


<details>
  <summary>🚀 Deploying Your First LLM App</summary>

1. Let's create a new Huggingface Space. Navigate to [Huggingface](https://huggingface.co) and click on your profile picture on the top right. Then click on `New Space`.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/f0656408-28b8-4876-9887-8f0c4b882bae"> 
</p>

2. Setup your space as shown below:
   
- Owner: Your username
- Space Name: `llm-app`
- License: `Openrail`
- Select the Space SDK: `Docker`
- Docker Template: `Blank`
- Space Hardware: `CPU basic - 2 vCPU - 16 GB - Free`
- Repo type: `Public`

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/8f16afd1-6b46-4d9f-b642-8fefe355c5c9"> 
</p>

3. You should see something like this. We're now ready to send our files to our Huggingface Space. After cloning, move your files to this repo and push it along with your docker file. You DO NOT need to create a Dockerfile. Make sure NOT TO push your `.env` file. This should automatically be ignored.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/cbf366e2-7613-4223-932a-72c67a73f9c6"> 
</p>

4. After pushing all files, navigate to the settings in the top right to add your OpenAI API key.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/a1123a6f-abdd-4f76-bea4-39acf9928762"> 
</p>

5. Scroll down to `Variables and secrets` and click on `New secret` on the top right.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/a8a4a25d-752b-4036-b572-93381370c2db"> 
</p>

6. Set the name to `OPENAI_API_KEY` and add your OpenAI key under `Value`. Click save.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/0a897538-1779-48ff-bcb4-486af30f7a14"> 
</p>

7. To ensure your key is being used, we recommend you `Restart this Space`.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/fb1d83af-6ebe-4676-8bf5-b6d88f07c583"> 
</p>

8. Congratulations! You just deployed your first LLM! 🚀🚀🚀 Get on linkedin and post your results and experience! Make sure to tag us at #AIMakerspace !

Here's a template to get your post started!

```
🚀🎉 Exciting News! 🎉🚀

🏗️ Today, I'm thrilled to announce that I've successfully built and shipped my first-ever LLM using the powerful combination of Chainlit, Docker, and the OpenAI API! 🖥️

Check it out 👇
[LINK TO APP]

A big shoutout to the @**AI Makerspace** for all making this possible. Couldn't have done it without the incredible community there. 🤗🙏

Looking forward to building with the community! 🙌✨ Here's to many more creations ahead! 🥂🎉

Who else is diving into the world of AI? Let's connect! 🌐💡

#FirstLLM #Chainlit #Docker #OpenAI #AIMakerspace
```

</details>

<p></p>

### That's it for now!  And so it begins.... :)
=======
=======
>>>>>>> d3ec945 (Initial commit)
=======
>>>>>>> f76d2fa (Initial commit)
=======
>>>>>>> a21a9d7 (Update README.md)
=======
>>>>>>> cda88b7 (Update README.md)
# 🧑‍💻 What is [AI Engineering](https://maven.com/aimakerspace/ai-eng-bootcamp)?

AI Engineering refers to the industry-relevant skills that data science and engineering teams need to successfully **build, deploy, operate, and improve Large Language Model (LLM) applications in production environments**.  

In practice, this requires understanding both prototyping and production deployments.

During the *prototyping* phase, Prompt Engineering, [Retrieval Augmented Generation (RAG)](https://www.youtube.com/playlist?list=PLrSHiQgy4VjFlWgcLHatJCBgfeE8smVyP), and [Fine-Tuning](https://www.youtube.com/playlist?list=PLrSHiQgy4VjGMzyXsSlvN-TjPaqFFsAGP) are all necessary tools to be able to understand and leverage. Prototyping includes:
- Building RAG Applications
- Fine-Tuning LLMs & Embedding Models
- Building Agent/Reasoning Applications
- LLM Application Deployment

When *productionizing* LLM application prototypes, there are many important aspects ensuring helpful, harmless, honest, reliable, and scalable solutions for your customers or stakeholders. Productionizing includes:
- RAG Evaluation and Improvement
- Monitoring and Visibility Tooling
- Efficient Inference and Serving
- Scaling LLM Applications

This bootcamp builds on our two previous courses, [LLM Engineering](https://maven.com/aimakerspace/llm-engineering) and [LLM Operations](https://maven.com/aimakerspace/llmops) 👇

- Large Language Model Engineering (LLM Engineering) refers to the emerging best practices and tools for training, fine-tuning, and aligning LLMs before production deployment.  LLM Engineering is the counterpart to ML Engineering (MLE) which focuses on LLM-specific techniques like prompt engineering, reinforcement learning, quantization, and other methods required by this new paradigm.
    
- Large Language Model Ops (LLM Ops, or LLMOps (as from [WandB](https://docs.wandb.ai/guides/prompts) and [a16z](https://a16z.com/emerging-architectures-for-llm-applications/))) refers to the emerging best-practices, tooling, and improvement processes used to manage production LLM applications throughout the AI product lifecycle.  LLM Ops is a subset of Machine Learning Operations (MLOps) that focuses on LLM-specific infrastructure and ops capabilities required to build, deploy, monitor, and scale complex LLM applications in production environments.

# 🏆 **Grading and Certification**

To become **AI-Makerspace Certified**, which will open you up to additional opportunities for full and part-time work within our community and network, you must:

1. Complete all project assignments.
2. Complete a project and present during Demo Day.
3. Receive at least an 85% total grade in the course.

If you do not complete all assignments, participate in Demo Day, or maintain a high-quality standard of work, you may still be eligible for a *certificate of completion* if you miss no more than 2 live sessions.

# 📚 About

This GitHub repository is your gateway to mastering the art of AI Engineering.  ***All assignments for the course will be released here for your building, shipping, and sharing adventures!***

# 🙏 Contributions

We believe in the power of collaboration. Contributions, ideas, and feedback are highly encouraged! Let's build the ultimate resource for AI Engineering together.

Please to reach out with any questions or suggestions. 

Happy coding! 🚀🚀🚀

<<<<<<< HEAD
>>>>>>> 5481d36 (Adding Initial Content)
=======
=======
# my-first-repo
<<<<<<< HEAD
My Awesome Description
>>>>>>> 84a109b (Initial commit)
<<<<<<< HEAD
>>>>>>> d3ec945 (Initial commit)
=======
=======

## my task

Here are the things I need to accomplish
1. Get my machine setup
1. Get all my access keys
1. Write some code

All Done
>>>>>>> 2fc0375 (my first commit (#1))
<<<<<<< HEAD
>>>>>>> e98f560 (my first commit (#1))
=======
=======
# Beyond-ChatGPT
<<<<<<< HEAD
<<<<<<< HEAD
Chainlit App using Python streaming for Level 0 MLOps
<<<<<<< HEAD
>>>>>>> 1f87be8 (Initial commit)
<<<<<<< HEAD
>>>>>>> f76d2fa (Initial commit)
=======
=======

LLM Application with Chainlit, Docker, and Huggingface Spaces
In this guide, we'll walk you through the steps to create a Language Learning Model (LLM) application using Chainlit, then containerize it using Docker, and finally deploy it on Huggingface Spaces.

Prerequisites
A GitHub account
Docker installed on your local machine
A Huggingface Spaces account

### Building our App
Clone this repo

Navigate inside this repo

### Install requirements using `pip install -r requirements.txt`?????????

Add your OpenAI Key to `.env` file and save the file.

Let's try deploying it locally. Make sure you're in the python environment where you installed Chainlit and OpenAI.

Run the app using Chainlit

```
chainlit run app.py -w
```

Great work! Let's see if we can interact with our chatbot.

It works! Let's ship it!


### Deploy to Huggingface Spaces

Login to Huggingface Spaces CLI

``` bash
huggingface-cli login
```

Follow the prompts to authenticate.



Push Docker Image to Huggingface Container Registry

```
docker tag llm-app:latest huggingface/your-username/llm-app:latest
docker push huggingface/your-username/llm-app:latest
```

Deploy to Huggingface Spaces


<<<<<<< HEAD
=======
Create a new Huggingface Space

=======
=======
<p align = "center" draggable=”false” ><img src="https://github.com/AI-Maker-Space/LLM-Dev-101/assets/37101144/d1343317-fa2f-41e1-8af1-1dbb18399719" 
     width="200px"
     height="auto"/>
</p>


## <h1 align="center" id="heading">:wave: Welcome to Beyond ChatGPT!!</h1>

>>>>>>> 2cec8e7 (Update README.md)
## 🤖 Your First LLM App

In this repository, we'll walk you through the steps to create a Large Language Model (LLM) application using Chainlit, then containerize it using Docker, and finally deploy it on Huggingface Spaces.

Are you ready? Let's get started!

<details>
  <summary>🏗️ Building Your First LLM App</summary>

1. Clone [this](https://github.com/AI-Maker-Space/Beyond-ChatGPT/tree/main) repo.

     ``` bash
     git clone https://github.com/AI-Maker-Space/Beyond-ChatGPT.git
     ```

2. Navigate inside this repo
     ``` bash
     cd Beyond-ChatGPT
     ```

3. Install the packages required for this python envirnoment in `requirements.txt`.
     ``` bash
     pip install -r requirements.txt
     ``` 

4. Open your `.env` file. Replace the `###` in your `.env` file with your OpenAI Key and save the file.
     ``` bash
     OPENAI_API_KEY=sk-###
     ```

5. Let's try deploying it locally. Make sure you're in the python environment where you installed Chainlit and OpenAI. Run the app using Chainlit. This may take a minute to run.
     ``` bash
     chainlit run app.py -w
     ```

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/54bcccf9-12e2-4cef-ab53-585c1e2b0fb5"> 
</p>

Great work! Let's see if we can interact with our chatbot.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/854e4435-1dee-438a-9146-7174b39f7c61"> 
</p> 

Awesome! Time to throw it into a docker container and prepare it for shipping!
</details>



<details>
  <summary>🐳 Containerizing our App</summary>

1. Let's build the Docker image. We'll tag our image as `llm-app` using the `-t` parameter. The `.` at the end means we want all of the files in our current directory to be added to our image.
     
     ``` bash
     docker build -t llm-app .
     ```

2. Run and test the Docker image locally using the `run` command. The `-p`parameter connects our **host port #** to the left of the `:` to our **container port #** on the right.
    
     ``` bash
     docker run -p 7860:7860 llm-app
     ```

3. Visit http://localhost:7860 in your browser to see if the app runs correctly.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/2c764f25-09a0-431b-8d28-32246e0ca1b7"> 
</p>

Great! Time to ship!
</details>


<details>
  <summary>🚀 Deploying Your First LLM App</summary>

1. Let's create a new Huggingface Space. Navigate to [Huggingface](https://huggingface.co) and click on your profile picture on the top right. Then click on `New Space`.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/f0656408-28b8-4876-9887-8f0c4b882bae"> 
</p>

2. Setup your space as shown below:
   
>>>>>>> 4689b8a (Update README.md)
- Owner: Your username
- Space Name: `llm-app`
- License: `Openrail`
- Select the Space SDK: `Docker`
- Docker Template: `Blank`
- Space Hardware: `CPU basic - 2 vCPU - 16 GB - Free`
- Repo type: `Public`

<<<<<<< HEAD


>>>>>>> a21a9d7 (Update README.md)
Deploying on Huggingface Spaces using a custom Docker image involves using their web interface. Go to Huggingface Spaces and create a new space, then set it up to use your Docker image from the Huggingface Container Registry.

Access the Application

Once deployed, access your app at:

ruby
Copy code
https://huggingface.co/spaces/your-username/llm-app
Conclusion
You've successfully created an LLM application with Chainlit, containerized it with Docker, and deployed it on Huggingface Spaces. Visit the link to interact with your deployed application.
>>>>>>> 8377e05 (Update README.md)
<<<<<<< HEAD
>>>>>>> 13bd056 (Update README.md)
=======
=======
Please refer to the [LLMOps Dev Environment](https://github.com/AI-Maker-Space/LLMOps-Dev-101/)https://github.com/AI-Maker-Space/LLMOps-Dev-101/ for instructions.
>>>>>>> 7b8984d (Update README.md)
<<<<<<< HEAD
>>>>>>> 9fe3994 (Update README.md)
=======
=======
Please refer to the [LLMOps Dev Environment](https://github.com/AI-Maker-Space/LLMOps-Dev-101/) for instructions.
>>>>>>> 2902395 (Update README.md)
<<<<<<< HEAD
>>>>>>> 18c52ae (Update README.md)
=======
=======
<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/8f16afd1-6b46-4d9f-b642-8fefe355c5c9"> 
</p>

3. You should see something like this. We're now ready to send our files to our Huggingface Space. After cloning, move your files to this repo and push it along with your docker file. You DO NOT need to create a Dockerfile. Make sure NOT TO push your `.env` file. This should automatically be ignored.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/cbf366e2-7613-4223-932a-72c67a73f9c6"> 
</p>

4. After pushing all files, navigate to the settings in the top right to add your OpenAI API key.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/a1123a6f-abdd-4f76-bea4-39acf9928762"> 
</p>

5. Scroll down to `Variables and secrets` and click on `New secret` on the top right.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/a8a4a25d-752b-4036-b572-93381370c2db"> 
</p>

6. Set the name to `OPENAI_API_KEY` and add your OpenAI key under `Value`. Click save.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/0a897538-1779-48ff-bcb4-486af30f7a14"> 
</p>

7. To ensure your key is being used, we recommend you `Restart this Space`.

<p align = "center" draggable=”false”>
<img src="https://github.com/AI-Maker-Space/LLMOps-Dev-101/assets/37101144/fb1d83af-6ebe-4676-8bf5-b6d88f07c583"> 
</p>

8. Congratulations! You just deployed your first LLM! 🚀🚀🚀 Get on linkedin and post your results and experience! Make sure to tag us at #AIMakerspace !

</details>

<p></p>

### That's it for now!  And so it begins.... :)
>>>>>>> 4689b8a (Update README.md)
>>>>>>> a21a9d7 (Update README.md)
