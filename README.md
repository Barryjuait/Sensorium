Sebastián A. Barrientos
PhD in Neuroscience, Laboratory of Neural Circuits
Interdisciplinary Center for Neuroscience, UC University.
Santiago de Chile.


# Sensorium
This is the code of a modified GO/NOGO task, in which rats must learn to press a lever (it must be held for at least 300-800ms) to trigger one of two cues for 500ms(both are audiovisual) and design a proper strategy to maximize the amount of rewards. GO cues indicate that a liquid reward is available in a water trough, and NOGO cues signal a punishment as well. Both reward and punishment are released when a nosepoke is made in the water trough. Each nosepoke is sensed by an IR sensor in the entry of the water dispenser. Upon GO cues a nosepoke is counted a HIT response and activates a solenoid valve for 1000ms. GO response after 2000ms from the stimulus onset is counted as a MISS trial. On the other hand, when a nosepoke is made upon NOGO cues this is counted as a FAIL response, a bright light is turned on  and a new trial cannot be initiated during 6000ms. If nosepoke is avoided for at least 2000ms, then it is counted as a HIT response. 

As a control we included neutral trials, meaning that they are not associated with any outcome. Both neutral trials are "Neutral" and "Catch", the former is an audiovisual cue different to GO and NOGO, and the second is an empty cue (no lights nor sounds are released). Both neutral cues are in a lower proportion than GO and NOGO cues.

Times for reaction time, total lever press, inter-trial interval and time spent in nosepoke, are recorded. I suggest to copy the information from the serial monitor to store it in other format (excel maybe?).




