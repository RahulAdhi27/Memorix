# Memorix

PROBLEM STATEMENT:
Students and professionals often rely on videos, presentations, and PDFs for learning, but manually converting this content into effective study tools like flashcards or quizzes is tedious and inefficient. Existing solutions either lack customization (e.g., fixed question formats, no difficulty adjustment) or require extensive manual effort. This creates a barrier to active recall—a proven learning technique—by making it difficult to quickly generate personalized, high-quality study aids from diverse sources.

Our project solves this by automating the creation of customizable quizzes and flashcards from uploaded videos, PPTs, or PDFs—saving time while optimizing learning outcomes.


TEAM MEMBERS :-
Vijay Vignesh - dvijayvignesh@gmail.com 
Rahul Adhi - rahuladhi2709@gmail.com



SOLUTION :-
Our project is an AI-powered website that automates the creation of customizable study materials. Users can upload a YouTube video, PowerPoint presentation, or PDF document, and the platform instantly generates tailored flashcards or quiz questions based on the content. Key features include:
. Multi-format support: Process videos (audio/text extraction), slides, and documents.
. Customization: Adjust the number of questions and difficulty level (easy/medium/hard) to suit individual needs.
. AI-driven generation: Leverage NLP and machine learning to identify key concepts and formulate relevant questions.
This tool empowers learners to focus on understanding material rather than manual note-taking, saving time while improving knowledge retention through adaptive, interactive study aids.


GOOGLE DRIVE LINK - https://drive.google.com/drive/folders/1FzxJu7phNsH-0MASc0d1YIPSMNb06yIq?usp=drive_link



STEP-BY-STEP INSTRUCTIONS TO SETUP AND RUN THE PROJECT:

1) First, ensure you have Node.js installed (the project uses nodejs-20)

2) Install all dependencies:
   npm install

3) Set up the database schema:
   npm run db:push

4) For development with AI features, follow the Ollama setup in OLLAMA_SETUP.md if you want to use local AI. Otherwise, the system will run in demonstration mode (Question and 
   flashcard generation will not function)

5) Start the development server:
   npm run dev

6)The server will start on port 5000. You can access:
  Frontend: http://localhost:5000
  API endpoints: http://localhost:5000/api/*
