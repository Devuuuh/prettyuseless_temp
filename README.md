<img width="1280" height="640" alt="git (1)" src="https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd" />



# Oops! Another Universe


#Team Name: Prettyuseless


### Team Members
- Team Lead:  Devapriya V. - Sahrdaya College of Engineering and Technology
- Member 2: Adhisree S- Sahrdaya College of Engineering and Technology

### Project Description
Parallel Universe Scanner is an interactive futuristic website that lets users explore fictional alternate realities. The user is detected through a camera, identified as being currently on Earth, and then given a choice of multiple imaginative universes.

After selecting a universe, the website generates a complete fictional version of the user's life in that reality, including age, family, relationship status, partner, children, occupation, abilities, home, personality, fun facts, and a short alternate-life story. The user can then decide whether to switch to that universe.

### The Problem (that doesn't exist)
What if you suddenly wondered:

“What would my life be like if I lived in a completely different universe?”

Unfortunately, there is currently no scientific emergency button for checking your alternate-universe life.

People are forced to live with only one timeline, one career, one relationship status, and one version of themselves.

This is clearly a problem that nobody asked us to solve.

### The Solution (that nobody asked for)
We created Parallel Universe Scanner — a completely unnecessary but highly entertaining solution.

The website scans the user, confirms that they are currently on Earth, and allows them to choose from multiple fictional universes.

Each universe contains a completely different version of the user with a unique:
Age
Family
Father and mother
Siblings
Relationship status
Boyfriend/partner, if applicable
Children, if applicable
Career
Home
Personality
Powers and abilities
Achievements
Funny facts
Alternate-life story

After exploring the selected reality, the user gets the ultimate question:

“Are you interested in switching to this universe?”

They can either enter the new universe or reject it and return to reality.

## Technical Details
### Technologies/Components Used
For Software:
HTML5 — Website structure
CSS3 — Styling, animations and visual effects
JavaScript — User interaction, camera handling, universe selection and dynamic content
Python — Backend logic
Flask — Python web framework and API
JSON / Python data structures — Universe information
Browser Camera API — Person detection/scanning experience
Git — Version control
GitHub — Source code hosting
Render — Web deployment
For Hardware:
No dedicated hardware is required.

The project runs using:

Laptop/Desktop
Built-in webcam or USB webcam
Internet connection
Display/monitor
### Implementation
For Software:
The project is implemented as a frontend-backend web application.
Frontend

The frontend consists of separate HTML, CSS and JavaScript files.

The website contains the following major stages:

Landing page
Camera scanning
Earth/current-universe identification
Universe selection
Alternate-life profile
Optional alternate-life story
Universe switching confirmation
Universe transfer animation
Final universe screen
Universe rejection screen
Backend

A Flask backend provides fictional universe data to the frontend.

The frontend communicates with the Flask API using JavaScript fetch() requests.

Example API routes:

GET /api/universes
GET /api/universe/aetheria
GET /api/universe/nexora
GET /api/universe/velmora
GET /api/universe/lunaria
GET /api/universe/drakonia
GET /api/universe/chronovia

The universe data contains information such as identity, family, relationships, children, career, home, powers, personality and story.
# Installation
Clone the repository:

git clone https://github.com/Devuuuh/prettyuseless_temp.git

Move into the project directory:

cd prettyuseless_temp

Create a Python virtual environment:

python -m venv venv

Activate the virtual environment on Windows:

venv\Scripts\activate

Install the required Python packages:

pip install -r requirements.txt

# Run
Start the Flask server:

python backend/app.py

Open the local website in your browser:

http://127.0.0.1:5000

Allow camera access when requested by the browser.

### Project Documentation
For Software:
Software Workflow

The application follows this workflow:

USER
  ↓
SCAN ME
  ↓
CAMERA ACTIVATED
  ↓
PERSON DETECTED
  ↓
CURRENT UNIVERSE IDENTIFIED
  ↓
EARTH 🌍
  ↓
CHOOSE A UNIVERSE
  ↓
SELECT / RANDOM UNIVERSE
  ↓
ALTERNATE LIFE GENERATED
  ↓
VIEW PROFILE
  ↓
VIEW OPTIONAL STORY
  ↓
ARE YOU INTERESTED IN SWITCHING?
       ↙                    ↘
     YES                     NO
      ↓                       ↓
UNIVERSE TRANSFER       UNIVERSE REJECTED
      ↓                       ↓
LOADING ANIMATION       BACK TO UNIVERSE LIST
      ↓
ENTER THE UNIVERSE
      ↓
NEW REALITY
# Screenshots (Add at least 3)
<img width="1278" height="617" alt="front page" src="https://github.com/user-attachments/assets/43afa747-6f64-45b8-9654-c091d0bb6998" />
front page

<img width="1342" height="600" alt="earth" src="https://github.com/user-attachments/assets/999ac8f6-1ae2-4eae-a446-5be8c322bf33" />
The camera detects the user and identifies Earth as their current universe.


<img width="1307" height="614" alt="universe selection" src="https://github.com/user-attachments/assets/1b2542be-716f-491f-9ed8-c31e3638e90d" />
The user chooses from multiple fictional universes or selects a random universe.


<img width="1313" height="564" alt="random universe" src="https://github.com/user-attachments/assets/b2ce17cc-7436-4a8a-a788-b36b5e136b89" />
The selected universe displays the user's fictional alternate identity, family, relationship, career, abilities and other life details.



# Diagrams
Software Architecture
Architecture showing communication between the camera, frontend JavaScript, Flask backend, universe data and final user interface.
For Hardware:

# Schematic & Circuit
Not Applicable
This project is a software-based interactive web application and does not require electronic circuits or FPGA hardware.

# Build Photos

No physical electronic hardware is required for the project.


### Project Demo
# Video


# Additional Demos
[Add any extra demo materials/links]

## Team Contributions
- Devapriya V -Frontend development, UI/UX design, universe-selection interface, animations and project presentation.
- Adhisree S -Python Flask backend, universe data, API integration, testing and deployment.

---
Made with ❤️ at TinkerHub Useless Projects 

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)



