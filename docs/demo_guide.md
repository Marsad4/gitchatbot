# Demo Guide for GitChatBot

Welcome to **GitChatBot**!  
This chatbot answers questions based on the content stored in this repository.  

## Features
- Automatically updates when new content is pushed to GitHub.
- Uses embeddings to provide context-aware answers.
- Can process `.md`, `.txt`, and code files.

## Example Questions
- What is GitChatBot?
- How does the webhook update the knowledge base?
- Which files are used to train the chatbot?

## Getting Started
1. Clone the repository.
2. Add or update documentation files (like this one).
3. Push changes to GitHub.
4. The webhook will trigger ingestion automatically.

## FAQ
**Q:** Do I need to restart the server after adding content?  
**A:** No. Just push your changes and the webhook will handle re-ingestion.

**Q:** Which file formats are supported?  
**A:** Markdown (`.md`), text (`.txt`), and source code files.
