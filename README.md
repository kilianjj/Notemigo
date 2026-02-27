# Notemigo

Prototype of a full-stack study app that combines note-taking, flashcards, and practice quizzes into a single platform.

Instead of treating notes and active recall as separate tools, this system seeks to combine the benefits of both techniques and includes generative AI features to reduce the amount of time it takes for a user to create study materials. The app allows users to generate flashcards and quizzes directly from prompts, reducing the time spent mannually entering or deriving such infromation so more time can be spent reviewing. Since the AI generation is prompt guided, users can tailor the style and difficulty of the output (e.g., conceptual questions, definitions, applied problems) in a manner that is optimal for their studying goals. 

Generated flashcards can be easily added to any of the user's flashcard decks for review. Generated quizzes are directly embedded in the LLM chat screen and support visualization of correct answers when submitted, and can also provide LLM-based feedback to free response answers. 

## Demo

You can try it out [here](https://notemigo.web.app/).

Demo account:

Username: demo

Password: demo_pass

## Code

You can find the code [here](https://github.com/kilianjj/creative-repo-name).

## Tech Stack

Frontend: Flutter

Backend: FastAPI

LLM Orchestration: LangGraph

Deployment: Docker containers deployed on Google Cloud
