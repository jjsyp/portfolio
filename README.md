# Portfolio

**About Me**:
I am a recent college graduate with a Bachelor’s of Science in Applied Computer Science.  I am actively looking for a career 
in software where I can further my passions and knowledge of this field.  I love the complex puzzle that comes with 
dealing with large scale applications and genuinely want to push and expand my abilities to tackle any coding and 
development challenges that come my way.

Below you will find descriptions of and links to the various projects I have worked on that showcase
my personal talents and skills.


**Project**: Text to speech benchmarking tool

**Github repo link**: https://github.com/jjsyp/deepgram

**Description**: Designed and built a benchmarking tool for use at Deepgram, an industry leading company in AI text to 
speech.  The tool utilizes Google's OAuth API to authentic users and provide security.  Once a user is logged in, they
will be able to choose from a list of the company's audio models and listen to various audio clips.  Users can then
assign various tags and scores to the model's audio to generate and organize data for later analysis.  The data is
submitted by the analysts and is saved in a database for easy storage, access, and analysis.

**Languages, tools, libraries, or skills used**: Development included building the backend server in Python on a Flask 
framework utilizing an MVC pattern along with flask blueprints. A frontend user interface primarily in JavaScript 
on a React framework and CSS for styling. An accompanying database scheme designed in PostgreSQL, and a user 
authentication system through Google’s OAuth2 API. 

I also met several times with Deepgram's CTO to ensure the program's architecture would allow for easy
integration with the company's existing systems.  I also met with the Head of Data Opertations, who would have direct
oversight of those using the tool, to collect customer stories in order to build an ideal tool for the company. 
I also designed and presented several wireframes to showcase the user interface before beginning development.


**Project**: Combat Tracker Application

**Github repo link**: https://github.com/jjsyp/combat_tracker

Description: Developed a desktop application for tracking combat encounters in tabletop role-playing games. The application 
features a dynamic initiative tracking system that automatically sorts characters by their initiative rolls, maintains round 
count, and allows for quick health and status modifications during combat. Users can create, copy, and manage multiple 
characters with custom fields for flexibility. The application includes session management capabilities, allowing users to 
save and load combat states, making it perfect for long-running campaigns or recurring encounters. The interface is designed 
with quick-edit functionality for rapid updates during fast-paced combat scenarios.

**Languages, tools, libraries, or skills used**: Built using Python with Tkinter for the GUI implementation, following a modular
component-based architecture. The application utilizes object-oriented programming principles with clear separation of concerns 
through component isolation. Key technical features include: Custom GUI components built on Tkinter/ttk for a native look and feel,
Session management system with auto-save functionality, Modular architecture using Python's import system, JSON-based data 
persistence for character and session storage


**Project**: Screen capture and object detection

**Github repo link**: https://github.com/jjsyp/dbd-imagerec

**Description**: A personal project I did to gain an understanding of object detection and recognition as well as 
optimization methods. The program functions by constantly reading from the screen buffer, attempting to detect both 
red lines and white boxes that could appear in the center of the screen.  Once both of these are detected, the program 
will check for any overlap of the two and, when said overlap occurs, sends a command to perform certain keyboard inputs.

**Languages, tools, libraries, or skills used**: The program is written mostly in Python, utilizes numpy for computation, the 
mss library for screen capture, opencv for object detection, ctype library for utilizing C compatiable types (used for 
faster keyboard input then python modules provided), cProile for profiling, tkinter for a rudemantary GUI, and 
multi-threading for running the GUI and application similtaniously and for compatiblity with the mss library. 
