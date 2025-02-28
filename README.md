# CodeREDPros2024

# What Is Does
- Create an airline chatbox that when the users type in their cirtiria, it going to look up the suitable flight for them.
- Extract users' input to JSON file using OpenAI.
- Insert the JSON file to Amadeus API to generate the matching results to another JSON file.
- Use OpenAI to convert the result JSON file back to NLP and output the answer to the users.

# Tools of Developments
- Front-end: HTML/CSS.
- Back-end: Flask (Python).
- APIs: OpenAI, Amedeus.

# Challenges
- Convert the input cities to their airport code.
- Convert the different input dates to a uniform format.
- Handle the front-end input to make an understandable JSON file in the back-end for further generation.

# Accomplishments
- Create a functioning chatbox website with applealing UI
- Manage large flights dataset in order to give an appropriate response.
- Implement a feature that transfer speech to text input.

# How to use the program
- Clone the project by 
```bash
git clone https://github.com/bindle03/CodeREDPros2024.git
cd CodeREDPros2024
```
- Install the dependencies
```bash
pip install -r requirements.txt # May need to install the C++ build tools
```
- Create a .env file
```python
OPEN_API= # Your OpenAI API key
```
- To run the project
```python
python app.py # The app should be running on port 5000
```