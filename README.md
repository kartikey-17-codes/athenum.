# [Athenum.]

> [Research ,decoded.]

## About The Project
[As we know , reading and understanding a research paper is a tiring task even for professionals , for students , its something we all avoid , but a research paper is extremely important for us to understand what's going in the world and how. So here is athenum , a space for students and professionals to read any research paper based on their field and skill level , athenum provides the user a detailed summary of each research paper , a chatbot to ask about any of your doubts , and most of all , a community to leave your opinions and debate about the research paper , the users can decode the research paper together with unity in a comment tab provided in every research paper tab. ]

### Key Features
* **AI Summarization:** Summarize complex research paper in a way that is easy to understand 
* **Intelligent Categorization:** label every research paper as easy/medium/hard based on the complexity of the topics that the paper covers
* **Community Discussions:** Leave your opinions about the paper , discuss the scope of the paper , debate the topics covered
* **Chatbot:** A chatbot specialized in handling queries related to the research paper 

## Tech Stack
**Frontend:**
* Next.js 14 
* Tailwind CSS
* Framer Motion

**Backend & Data:**
* Python 
* Supabase 
* OpenAI API 
* ArXiv API
  
## Architecture
**The "Harvester" (Python Worker):**
1.   Fetch from ArXiv...
2.   Process with OpenAI...
3.   Upsert to Database...

**The "Platform" (Next.js):**
1.  User authentication...
2.  Fetching data from Supabase...

## Getting Started

### Prerequisites
* Node.js & npm
* Python 3.13
* Supabase Account
* OpenAI API Key



