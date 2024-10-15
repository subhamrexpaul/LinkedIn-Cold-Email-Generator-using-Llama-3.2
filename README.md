# LinkedIn-Cold-Email-Generator-using-Llama-3.2

Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions. 

**Imagine a scenario:**

- Microsoft needs a Principal Software Engineer and is spending time and resources in the hiring process, onboarding, training, etc.
- Scaler is an education and career advancement company that can provide a highly trained software development engineer to Microsoft. So, the business development executive (Mohan) from Scaler is going to reach out to Microsoft via a cold email.

![img.png](![img](https://github.com/user-attachments/assets/91d73b8c-4224-4e33-a8f1-4001ee371955)
)

## Architecture Diagram
![img.png](![architecture](https://github.com/user-attachments/assets/f29b4176-7a46-4c1e-9745-8d2357c39ff5)
)

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   

**Author:** Subham Paul  
**License:** MIT License

**Additional Terms:**
This software is licensed under the MIT License. However, commercial use of this software is strictly prohibited without prior written permission from the author. Attribution must be given in all copies or substantial portions of the software.
