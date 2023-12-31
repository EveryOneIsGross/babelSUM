# babelSUM

A simple command-line txt file reader that lets users choose a system voice for reading and can summarize spoken text using an AI agent. Supports txt, epub, and pdf files.

## ![babelSUM](https://github.com/EveryOneIsGross/babelSUM/assets/23621140/2cb09820-b558-41ff-a3bd-4e5957406979)

---

## Features

- Voice selection with pyttsx3 or ElevenLabs TTS API.
- Split text into manageable chunks for reading.
- Search functionality to find relevant segments based on user queries.
- AI-based summarization of recently spoken text.
- Store and retrieve embeddings for efficient search.
- Multithreading for uninterrupted reading and user interaction.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- pip

Install the required packages:

```
ebooklib
pyttsx3
json
threading
queue
pickle
re
gpt4all
PyPDF2
numpy
elevenlabs
sklearn
```
