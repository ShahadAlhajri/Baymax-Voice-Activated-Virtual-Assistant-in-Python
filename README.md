# Baymax: Voice-Activated Virtual Assistant in Python  

## Description  
A Python-based virtual assistant inspired by Baymax, the lovable companion from the animated film *Big Hero 6*. Combining advanced Python libraries and APIs, this assistant streamlines user interactions with features like speech recognition, text-to-speech conversion, language translation, and real-time API integrations. It provides services such as retrieving news, flight details, and translations, ensuring a friendly and responsive user experience.  

---

## Project Overview  
This virtual assistant replicates some supportive and interactive functions, including:  
- **Translation**: Converts English text to Arabic with spoken responses for a seamless experience.  
- **News Updates**: Retrieves and reads aloud the latest headlines using the News API.  
- **Flight Information**: Provides real-time flight details, including status, departure, and arrival information.  
- **Conversational Loop**: Engages users by following up after each interaction to create a natural conversational flow.  

---

## Key Features  
1. **Speech Recognition**: Converts spoken commands into text using Google Speech Recognition.  
2. **Text-to-Speech (TTS)**: Generates natural audio responses using gTTS.  
3. **Language Translation**: Translates English text to Arabic using the GoogleTrans API.  
4. **News API Integration**: Fetches top headlines from the News API in real-time.  
5. **Flight Data Retrieval**: Provides flight details via the AviationStack API.  
6. **Task Identification**: Uses TF-IDF and cosine similarity to match user input with predefined tasks.  

---

## Technical Implementation  
This assistant is built using the following technologies:  
- **Speech Recognition**: Processes spoken input into actionable text.  
- **gTTS**: Converts text into spoken responses for better accessibility.  
- **GoogleTrans**: Handles translations between English and Arabic.  
- **AviationStack API**: Retrieves live flight details like departure and arrival times.  
- **News API**: Fetches up-to-date news headlines.  
- **TF-IDF Vectorizer**: Analyzes text input for task identification.  
- **Cosine Similarity**: Matches user queries with predefined tasks.  

---

## Sample Interaction  
Here’s how Baymax interacts with users:  
- **Translation**:  
  - *User*: "Translate a text from English to Arabic."  
  - *Baymax*: "Please say the text you want to translate to Arabic."  
  - *User*: "Applied natural language processing."  
  - *Baymax*: "Here is the translation in Arabic: معالجة اللغة الطبيعية التطبيقية"  

- **News Retrieval**:  
  - *User*: "What are the top news headlines today?"  
  - *Baymax*: Retrieves and reads aloud the latest headlines.  

- **Flight Details**:  
  - *User*: "Could you get the flight details for flight KU101?"  
  - *Baymax*: Provides detailed information, such as the airline, flight number, and arrival times.  

---

## How to Run  
1. Install the required Python libraries and APIs using the commands provided in the script.  
2. Replace `YOUR_API_KEY` with your personal API keys for NewsAPI and AviationStack.  
3. Run the script in Google Colab to experience the assistant in action.

---

## Future Enhancements  
- Expanding functionalities with additional APIs.  
- Incorporating advanced natural language processing for enhanced task identification.  
- Developing a graphical user interface (GUI) for a more user-friendly experience.  

---

## References  
1. Basak, S. (n.d.). Text-to-Voice [Computer software]. GitHub. Retrieved from [Text-to-Voice Repository](https://github.com/shuvobasak4004/Text-to-Voice/tree/main).  
2. Prasad, D. (n.d.). Virtual-AI-assistant [Computer software]. GitHub. Retrieved from [Virtual-AI-assistant Repository](https://github.com/DevashishPrasad/Virtual-AI-assistant).  

---

## Conclusion  
This project represents the fulfillment of a childhood dream: creating a virtual assistant inspired by Baymax. By combining creativity and technology, this assistant embodies compassion and efficiency, simplifying daily tasks and enhancing productivity in a fun and interactive way.
