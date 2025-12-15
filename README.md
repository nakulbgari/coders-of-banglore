# 🚀 Coders of Bangalore — Instagram Community Data Analysis
📖 The Story

Sam Altman visits Bangalore.

You ask him for $2.2 billion in funding.

He laughs — publicly.

Then he gives you a challenge:

“Collect raw Instagram data of all OpenAI followers and answer this in 24 hours:

Who has the maximum posts?

Who has the maximum followers?

Who follows the maximum people?

How many account categories exist?

How many people are there in total?”

You ask for the data.

He laughs again.

So you build the system yourself.

📍 Data Collection in Indiranagar

To execute the challenge, a small team is formed:

Vijyalaxmi Iyer — based in Hebbal

Sam Chandra — based in HSR Layout

You — responsible for the data processing system

To keep things fair, the team meets at Rameshwaram Café, Indiranagar — a midpoint for everyone.

Responsibility Split

Field Data Collection: Vijyalaxmi and Sam

Data Processing & Analysis: You

The raw data is collected exactly as Instagram presents it — unstructured, inconsistent, and noisy.

🎯 Project Objective

Build a pure Python pipeline that can:

Ingest raw Instagram profile data

Parse unstructured text into structured format

Answer analytical questions without relying on APIs or scraping libraries

Scale from demo data to real-world data with zero code changes

🧪 Development Strategy (Demo → Production)

Instead of waiting for final data, development begins with a demo dataset.

Phase 1: Demo / Initial Data

Small sample text file

Used to design and validate parsing logic

Faster debugging and iteration

Phase 2: Final / Actual Data

Large, real-world dataset

Plugged directly into the same code

No refactoring required

✅ This mirrors real production data engineering workflows.

⚙️ Parsing in Pure Python
Input Format

Text file (.txt)

Each Instagram profile separated by an empty line

Fields may appear in any order

Emojis, links, and missing values included

Processing Pipeline
Raw Text File
   ↓
Profile Segmentation
   ↓
Line-by-Line Parsing
   ↓
Field Extraction
   ↓
Structured Python Dictionary
   ↓
JSON Output

📊 Questions Answered

The system computes answers for:

📸 Account with maximum posts

👥 Account with maximum followers

🔁 Account following the most people

🏷️ Number of distinct account categories

👤 Total number of profiles analyzed

All insights are derived directly from the parsed output.

🛠️ Tech Stack

Python

Jupyter Notebook

Text-based datasets (.txt)

JSON output

Core Python libraries only

📁 Project Structure
├── CodersOfBanglore.ipynb   # Core parsing & analysis logic
├── initialdata.txt         # Demo dataset
├── finaldata.txt           # Real-world dataset
├── data.json               # Structured output

▶️ How to Run

Clone the repository

Place initialdata.txt or finaldata.txt in the root directory

Run CodersOfBanglore.ipynb

View the structured output in data.json

🧠 What This Project Demonstrates

Real-world unstructured data handling

Separation of data collection and processing

Production-style development workflow

Strong fundamentals in parsing and data engineering

Ability to work under constraints

💰 The Outcome

Twenty-four hours later, the answers were ready.

The data was messy.
The constraints were real.
The system worked.

Sam Altman reviewed the results.

He stopped laughing.

The funding came through.

🚀 Closing Note

When the data doesn’t exist —
you don’t wait for it.

You build the system that makes sense of chaos.

contact me:
email:- ashubagri039@gmail.com
phone no. 9810865294
linkdin:- https://www.linkedin.com/in/nakul-bagri-a9b239285/
