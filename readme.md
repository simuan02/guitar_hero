## Setup instructions

Before executing any script, the MongoDB database must be initialized using Docker.

### Prerequisites
<<<<<<< HEAD
=======

>>>>>>> fa435b517d50d7f12729b38e1f3529b16da68f1a
- Git
- Docker Desktop (with Docker Compose)
- Python 3.10+

<<<<<<< HEAD
---

=======
>>>>>>> fa435b517d50d7f12729b38e1f3529b16da68f1a
### Database initialization

Execute the following commands from terminal, before executing any script:

### Windows:

git clone https://github.com/simuan02/guitar_hero.git

cd guitar_hero

.\scripts\restore.ps1

### Mac/Linux:

git clone https://github.com/simuan02/guitar_hero.git

cd guitar_hero

chmod +x scripts/restore.sh

./scripts/restore.sh

This will start a MongoDB container and restore the database locally at:
mongodb://localhost:27017

### LLM Configuration

Before executing scripts that utilize LLMs, create a .env file in the project root and declare a valid API KEY for Google Gemini:

GUITAR_HERO_API_KEY = "GEMINI_API_KEY"