## Bridge activity: “Getting ready for GPIO with Python”

### 0. Purpose (2–3 minutes)

By the end of this activity, you will:

- Know what GPIO pins are and what they are used for.  
- See examples of how Python can control LEDs and buttons through GPIO.  
- Understand basic safety ideas so you do not damage a Raspberry Pi when using GPIO later. 

You do **not** need a Raspberry Pi for this activity—just internet access.

***

### 1. Learn what GPIO is (10 minutes)

1. In a browser, search for “Raspberry Pi GPIO basics” and open one introductory article or video. 
2. In your notes (Google Doc or paper), answer these questions in your own words:

   - What does **GPIO** stand for?  
   - What is the difference between a **power pin** (3.3 V or 5 V), a **GND pin**, and a **GPIO pin**?  
   - Why is 3.3 V important for Raspberry Pi GPIO pins?  

3. Find a labeled **pinout diagram** for your model of Raspberry Pi (search “Raspberry Pi [model] pinout”). 

   - Paste or sketch the diagram into your notes.  
   - Highlight or circle:
     - One 3.3 V pin.  
     - One 5 V pin.  
     - At least two GPIO pins you might use for an LED and a button.  
     - At least one GND pin.  

***

### 2. Watch/skim a GPIO + Python example (10 minutes)

1. Find a short tutorial or video where someone uses **Python** to blink an LED on a Raspberry Pi. 
   - Search terms: “Raspberry Pi GPIO Python blink LED” or “Raspberry Pi LED Python tutorial”. 

2. In your notes, briefly describe:

   - What hardware is used.  
   - How the LED is connected.  
   - What the Python program does in plain language.
     
3. Copy (by typing, not copy–paste) the **core idea** of the Python code into your notes, in your own words:

   - One line that sets the pin mode.  
   - One line that sets a pin as **output**.  
   - One or two lines that turn the LED on and off.  

You do not need the exact code to be perfect; focus on understanding the *steps*.

***

### 3. Safety preview: how to avoid frying the Pi (5–7 minutes)

Using what you’ve read/watched, plus the notes from class, answer these in your own words:

1. Why is it dangerous to connect a GPIO pin directly to **5 V**?  
2. Why should an LED almost always have a **resistor** in series when connected to the Pi? 
3. What are two mistakes that can damage or stress the Pi’s GPIO pins?  

Then write a **3–4 bullet “safety pledge”** you will follow next week, such as:

- I will not connect any wire from 5 V to a GPIO pin.  
- I will always use a resistor with an LED.  
- I will ask for a wiring check if I’m unsure.  

***

### 4. Connecting this to Python (5–8 minutes)

Finally, tie this to the Python you just practiced in class:

In your notes or a short text file:

1. Explain how `print()`, `variables`, and simple `while` loops from this week’s Python warmup might be used with GPIO next week. For example:

   - `print()` to show status messages (“LED on”, “button pressed”).  
   - variables to store pin numbers or blink times.  
   - a `while True:` loop to blink an LED or repeatedly read a button.  

2. Write a **pseudo-code outline** (not full code) for a program that will:

   - Turn an LED on.  
   - Wait 1 second.  
   - Turn it off.  
   - Repeat forever until the user stops the program.  

Example pseudo-code:

- set pin numbering mode  
- set LED pin as output  
- loop forever:  
  - turn LED on  
  - wait 1 second  
  - turn LED off  
  - wait 1 second  

This will prepare you to write the real code on the Pi in the upcoming GPIO assignment.
You can skim this quickly to see who is conceptually ready for the physical GPIO work.

Would you like me to turn this into a polished `bridge_activity.md` file that you can drop into the same GitHub repo as the GPIO assignment, with clear headings and teacher-facing notes at the top?  
