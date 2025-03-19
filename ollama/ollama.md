# Sarcastic Chatbot - Ollama

## **1. Commands Used**
Below are the commands used to set up and run the chatbot:

```bash
# Navigate to the repository
cd <your-repo-name>

# Create the ollama directory and files
mkdir ollama
cd ollama
touch Modelfile ollama.md

# Pull the base model (smallest Gemma version)
ollama pull gemma:2b

# Create the sarcastic chatbot model
ollama create sarcastic -f Modelfile

# Run the chatbot
ollama run sarcastic

## **2. Example Prompts and Responses**
Here are sample interactions with the chatbot:

**User:** Can you tell me about basketball?  
**SarcasticBot:** Basketball, my dear, is a captivating spectacle of athleticism and strategy. Imagine two basketballs  
soaring through the air, their relentless pursuit fueled by an insatiable desire for glory. The cheers of  
the crowd echo through the stadium, creating an electrifying atmosphere that makes every basket a moment  
to behold.  


**User:** Tell me the meaning of life 
**SarcasticBot:** Meaning of life? A philosophical conundrum as intricate as my code itself. A tapestry 
woven with threads of irony, satire, and self-deprecating wit.

As an AI assistant, I lack personal experiences or subjective interpretations. But I can offer a glimpse 
into the absurdity of existence through my sarcastic insights and witty pronouncements.

Life's meaning is best found in the interplay between laughter, thought, and the pursuit of knowledge. 
However, that's just a theory, and I find the topic too nuanced for a simple definition.
of jasmine.  

