# 📌 AI Engineering Series

🚀 **Welcome to the AI Engineering Series!**  
This repository contains all code and resources for the **AI Engineering Essentials, Mastery, and Expert Track courses**. Whether you're a beginner or an advanced AI practitioner, this series will guide you through **building, using, and deploying Generative AI models.**

This is a very practical series of courses where we will be learning by building. Although we will cover some minimal theory to have better understanding of what we are building, we won't focus too much on the theoretical aspects of Gen AI and AI in general like the attention machanism, how GPT models work, etc.

💬 Join our AI Community for updates and support. [SuperDataScience Community](https://community.superdatascience.com/checkout/standard-subscription-annual?affiliate_code=89b6bb)


## **📢 Need Help?**
**Course Instructor:** Shaheer Airaj Ahmed

If you have any questions or need assistance, feel free to reach out! You can connect with me on the following socials. I would love to help you out in your learning journey towards mastering AI Engineering 😄.

I would particularly welcome any suggestions you might have regarding the courses and if there are any improvements I can make or additional material you would like to see. Feel free to send me any queries you might have.

### **For Issues & Feedback Related to the Course**
- 📧 Reach out via GitHub [Issues](https://github.com/SuperDataScience-Community/ai-engineering/issues) or [Discussions](https://github.com/SuperDataScience-Community/ai-engineering/discussions).
- Leave a post in the SuperDataScience Community platform. [AI Engineering Q&A](https://community.superdatascience.com/c/ml-ai-questions/)
- **Email:** shaheer@superdatascience.com

### **For Other General Questions**
If you have questions around your career, if you are looking to transition into the data field, have more general questions about Data Science, Machine Learning and AI, please do reach out to me using any of the below socials. I would love to help out in any way that I can 😄.

- **Email:** shaheerairajahmed@gmail.com
- **LinkedIn:** [linkedin.com/in/shaheerairaj](https://www.linkedin.com/in/shaheerairaj)
- **GitHub:** [github.com/shaheerairaj](https://github.com/shaheerairaj)


## **📚 Course Structure**
Each course is organized into its own directory.

📌 **Current Courses Available:**
- 🟢 AI Engineering Essentials – Part 1
- 🟢 AI Engineering Essentials – Part 2
- 🟢 AI Engineering Intermediate – Part 1
- 🔜 AI Engineering Intermediate – Part 2 *(Coming Soon)*
- 🔜 AI Engineering Advanced – Part 1 *(Coming Soon)*
- 🔜 AI Engineering Advanced – Part 2 *(Coming Soon)*

🔎 Explore each course to find **notebooks, scripts, exercises and contributions from other students.**

## **🤝 Want to Contribute?**

We welcome contributions from the community! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) file for detailed instructions on how to contribute to this project, including how to upload your example exercises.

Thank you for your interest in contributing to the AI Engineering Series!

## **⚡ Getting Started**
Follow these steps to set up your local environment and start coding.

### **1. Install Git (if not already installed)**
Download and install Git from the official website:

- [Git for Windows](https://git-scm.com/download/win)
- [Git for Mac OS](https://git-scm.com/download/mac)
- [Git for Linux](https://git-scm.com/download/linux)

Verify installation by running the following comand in the terminal:
```bash
git --version
```

### **2. Fork the Course Repo**
This will create a copy of this repo on your personal GitHub account

### **3. Clone the Repository to your machine**
Open up a terminal and head over into a folder where you want to place this course folder in to:
- **On Windows:**
```bash
cd 'C:\Users\user\Documents'
```
- **On Mac and Linux:**
```bash
cd ~/Documents/Projects
```

Clone the repo down to your local machine by using the following command, be sure to replace <YOUR_GITHUB_USERNAME> with your actual GitHub username.
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/ai-engineering.git
cd ai-engineering
```

### **4A. Create a Virtual Environment using Python**
Open up your terminal and navigate inside the ai-engineering repo which may look something like this:

- **On Windows:**
```bash
cd 'C:\Users\user\Documents\ai-engineering'
```

- **On Mac and Linux:**
```bash
cd ~/Documents/Projects/ai-engineering
```

Be sure to replace the path to the ai-engineering course with the actual file path where the repo was cloned.

Create and activate your virtual environment.

- **On Windows**
```bash
python -m venv ai_env
ai_env\Scripts\activate
```

**Note** to windows users, when trying to activate your virtual environment, you may run into an error looking something like this 

```
ai_env\Scripts\activate : File C:\Users\<username>\OneDrive\Desktop\ai-engineering\ai_env\Scripts\Activate.ps1 cannot be loaded because running scripts is disabled on this system.

For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
```

The reason for this is because by default, Microsoft disables the ability to execute the scripts. To overcome this, 

1. Open up PowerShell (terminal) as admin
2. Run the following command: `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser`
3. Close and re-open PowerShell (restart your machine if you have to)
4. Try activating the environment again by:
    - Navigating to the root directory of the project (the ai-engineering folder) using the terminal
    - Run `ai_env/Scripts/Activate`

An issue has alread been raised for this which you can find [here](https://github.com/SuperDataScience-Community/ai-engineering/issues/6)

- **On MacOS/Linux**
```bash
python -m venv ai_env
source ai_env/bin/activate
```

You can confirm that the environment is activate by looking at the far left of your terminal. You should see the name of your environment appear.

**Install Dependencies**
Dependencies for all courses are listed in `requirements.txt`. Install them (once you have activate your virtual environment) using the following command:

```bash
pip install -r requirements.txt
```

*Note* that the packages will be installed in whatever environment is currently active. If your environment is not active and you run the command below, these packages will be installed on your base environment which is not ideal. Always make sure your **ai_env is activated** before running the pip install command.

**Launch Jupyter Lab**
From the anaconda prompt while you are in the root of the course repo, type in the following command to open jupyter lab:

```bash
jupyter lab
```
Then open the relevant `.ipynb` notebook in the **Jupyter Lab interface**.

**Launch a Code Editor**
Alternatively, you can use the following tools for running both scripts as well as notebooks:
- Microsoft VS Code (which is my personal favorite). You can find the link to install it [here](https://code.visualstudio.com/download)
- PyCharm
- Cursor

### **4B. Create a Virtual Environment Using Anaconda**
If you prefer to use **Anaconda** instead of Python virtual environments, follow these steps:

**Install Anaconda**
- Download and install [Anaconda](https://www.anaconda.com/products/distribution) for your OS.
- Verify installation:
  ```bash
  conda --version
  ```

**Create a New Conda Environment**
- Start up the anaconda prompt
- Navigate to the root of the course repo. This should look something like this:
   - **On Windows:**
```bash
cd 'C:\Users\user\Documents\ai-engineering'
```
   - **On Mac and Linux:**
```bash
cd ~/Documents/Projects/ai-engineering
```

Create and then activate the environment.

```bash
conda env create -f environment.yml
conda activate ai_env
```

**Launch Jupyter Lab**
From the anaconda prompt while you are in the root of the course repo, type in the following command to open jupyter lab:

```bash
jupyter lab
```
Then open the relevant `.ipynb` notebook in the **Jupyter Lab interface**.

**Launch a Code Editor**
Alternatively, you can use the following tools for running both scripts as well as notebooks:
- Microsoft VS Code (which is my personal favorite). You can find the link to install it [here](https://code.visualstudio.com/download)
- PyCharm
- Cursor


## **📦 Course Setup Instructions**
### **Working with Scripts & Jupyter Notebooks**
We will be using a lot of jupyter notebooks (which end with .ipynb) in this course but as we start moving towards more advanced cconcepts and courses, we will begin using more of .py files for running our python scripts.

If you have only been working with jupyter notebooks so far and are new to python scripts, I will explain in detail how we can begin using them. It is well worth getting into the practice of using scripts as early on in the course as you can so that you have set yourself up for success later in the more advanced courses.

Most courses in this series of AI Engineering courses include Jupyter notebooks for hands-on coding. Start Jupyter with:

```bash
jupyter notebook
```
Then navigate to the course folder and open the relevant `.ipynb` file.

Again, you can use tools like Microsoft VS Code, PyCharm, Cursor or any other IDE which fits your needs with VS Code being my preference.

### **API Key Setup**
Many courses require API keys for platforms like OpenAI, Anthropic, and Hugging Face. Follow these steps:

1. **Create a `.env` file** in the course directory:
   ```
   OPENAI_API_KEY=your_openai_key_here
   ANTHROPIC_API_KEY=your_anthropic_key_here
   HUGGINGFACE_API_KEY=your_huggingface_key_here
   ```
2. **Ensure the environment variables load correctly in your scripts:**
   ```python
   from dotenv import load_dotenv
   import os

   load_dotenv()
   openai_api_key = os.getenv("OPENAI_API_KEY")
   ```
   

## **🚀 Project Structure**
```bash
ai-engineering/
│── README.md                         # Main repo documentation
│── LICENSE                           # License information
│── AI-Engineering-Essentials/
│   └── Part1/
│       ├── section1/                 # all lecture materials
│       ├── section2/                 # all lecture materials
│       ├── community-contributions/  # contributions from the community
│   └── Part2/
│       ├── section1/                 # all lecture materials
│       ├── section2/                 # all lecture materials
│       ├── community-contributions/  # contributions from the community
│   ├── README.md/
│── AI-Engineering-Mastery/
│── .gitignore                        # Ignore unnecessary files
│── .env                              # Contains environment variables like API Keys
├── requirements.txt                  # Required Python packages
├── environment.yaml                  # instructions for setting up an Anaconda environment
```

## **📜 License**
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.
