# Hey there, YouTube fans! Feeling bored watching long videos? The next time why don’t you try scrolling down to the next step?

Readme (README.md) file has been **curated in a manner such that it can be familiar to customers with no technical background**, thus making it accessible to masses.  It can be directly used by customers(D2C). 

Now you a have an assistant in your quest of understanding, the most complicated, lengthy, informative videos on YouTube. Apply super cool AI technology to videos: in this way, they can be easily explained and you can come across something you might not have paid attention to otherwise. 
The LLM-app is designed with YouTube surfers in mind. It has the potential to help both students and content-creators, and can also substantially save their time and resources.      

https://github.com/Haryaksh1/Video-Analyser-LLM/assets/154970822/07831032-63e7-4837-9ac1-6df5d5f22d1c


## Key Points:

* Uses Pathway’s [LLM App features](https://github.com/pathwaycom/llm-app) to build LLM(Large Language Model)
* OpenAI API [Embeddings](https://platform.openai.com/docs/api-reference/embeddings) and [Chat Completion](https://platform.openai.com/docs/api-reference/completions)
* Generate AI assistant responses

## Here's what VidQuest can do for you:

* **See it all, at a glance:** One might have to forget about hours of watching lengthy videos. VidQuest provides fast and easy-to-understand results since AI technology helps me understand what shows are about in the blink of an eye.
* **Ask away, get answers:** Hypothesizing, what exactly is interesting to you in a video with kinetics? No problem! All you have to do is ask VidQuest your questions and our AI will locate the answers you are looking for in the video.
* **Easy to use, fun to explore:** VidQuest is fun and easy to use, which is quite apparent as you go through its interface. The interface is clean and quite easily navigable so you don’t need a tutorial to get started with all this discovering.

## How to get started:Here's how to get started:

* **Grab VidQuest:** Proceed to GitHub right now and then clone VidQuest to your computer. That is like having a mini AI assistant for your You Tube videos.
* **Follow the guide:** Here some simple steps to help you to get started with this operating system very quickly. Here are the steps you have to take and you are a VidQuest expert in no time!
* **Paste those links:** All you have to do is to insert the link of the YouTube videos that interest you into VidQuest directly.
* **Let VidQuest work its wonders:** Press the "Upload" button and, bingo! Which will be the work of VidQuest’s AI, to break down and simplify the required videos. 🪄
* **Ask away:** Have some questions to the video? No problem! All you need to do is to input questions onto VidQuest and let the Artificial Intelligence do the rest.

## Details
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/vidquest.git
    ```
    
2. **Create a conda environment using environment.yml file:**
3. **Create a .env file with following content**
   ```bash
    HOST = 0.0.0.0
    PORT = 8080
    EMBEDDER_LOCATOR=text-embedding-ada-002
    MODEL_LOCATOR=gpt-3.5-turbo
    MAX_TOKENS=200
    TEMPERATURE=0.0
    LOCAL_FOLDER_PATH= {YOUR_FOLDER_PATH}
    EMBEDDING_DIMENSION=1536
    OPENAI_API_TOKEN = {YOUR_API_TOKEN}
    ```
4. **Run the following commands**
   ```bash
   pip install llm_app pathway
    ```

5. **Run the main.py file**
    ```bash
    python main.py
    ```
    
6. **Run the Streamlit App:**
    ```bash
    streamlit run streamlit_app/ui.py
    ```
    
7. **Add YouTube Video Links:**
    Simply paste the URLs of the YouTube videos you want to explore into the provided text area.
  
8. **Initiate Summarization:**
    Click the "Upload" button to kickstart VidQuest's AI engine, summarizing your videos into easily digestible insights.
  
9. **Ask Questions:**
    Probe deeper into the video content by asking questions directly within the app. VidQuest's AI is ready to provide accurate and insightful answers.

## License

VidQuest is licensed under the [MIT License](LICENSE).

