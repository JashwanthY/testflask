# Voice Object Finder

Discover and identify objects using your voice with this innovative project. The Voice Object Finder leverages speech recognition, computer vision, and natural language processing to locate and describe objects captured by a camera.

## Features

- **Voice Interaction:** Initiate the search by speaking the object you want to find.
- **Live Video Stream:** Toggle the live video stream to visually inspect the surroundings.
- **Visual Question Answering (VQA):** Utilizes a deep learning model to answer questions about the identified objects.


## Setup

Follow these instructions to set up and run the Voice Object Finder on your local machine.

### Prerequisites

- Python 3.6 or later
- pip

### Installation

Clone the repository:

   ```
   git clone https://github.com/b-sai/find_missing_object.git
   cd find_missing_object
   ```
   
Create a virtual environment:

**For Windows:**

```
python -m venv venv
source venv/Scripts/activate
```

**For Linux/Mac:**

```
python -m venv venv
source venv/bin/activate
```

Install dependencies:

```
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

NOTE: it might take about 5 minutes to install everything

Run the application:

```
python main.py
```

Open http://127.0.0.1:5000/ in your browser after following the above instructions.




