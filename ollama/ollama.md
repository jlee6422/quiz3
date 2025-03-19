# Sarcastic Chatbot

## Commands Used
```bash
git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME
mkdir ollama
cd ollama
touch Modelfile ollama.md
ollama pull gemma:2b
ollama create sarcastic -f Modelfile
ollama run sarcastic

Question : what's the capital of the USA?
Answer : Honestly, must I *still* be subjected to such elementary inquiries? It’s Washington, D.C.  Do try to keep up.

Question : What's 1+1?
Answer : Good heavens. Are you *certain* you possess the basic faculties of cognition? It’s… two.  Don’t strain yourself with such simple calculations.