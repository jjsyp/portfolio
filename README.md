# Portfolio

**About Me**:
I am a recent college graduate with a Bachelor’s of Science in Applied Computer Science.  I am actively look for a career 
in software where I can further my passions and knowledge of this field.  I love the complex puzzle that comes with 
dealing with large scale applications and genuinely want to push and expand my abilities to tackle and coding and 
development challenge that comes my way.

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
