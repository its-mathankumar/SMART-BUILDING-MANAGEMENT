# SMART-BUILDING-MANAGEMENT
Procedure to Upload the File "SMART BUILDING MANAGEMENT" Using Git

1.Open the terminal or Git Bash on your computer.

2,Navigate to the directory where the file "SMART BUILDING MANAGEMENT" is located.

3.Initialize a Git repository by running the following command:
git init

4.Add the file to the staging area:
git add "SMART BUILDING MANAGEMENT"

5.Commit the file with a commit message:
git commit -m "Added SMART BUILDING MANAGEMENT file"

6.Create a repository on GitHub (if not already created).

7.Link the local repository to the GitHub repository:
    git remote add origin https://github.com/your-username/your-repo-name.git

8.Push the committed file to the GitHub repository:
    git push -u origin master




Procedure for Smart Street Light System Using IoT

Component Setup:
      Collect all required components: NodeMCU (or Arduino), PIR sensor, LDR sensor, LEDs or streetlight model, resistors, jumper wires, breadboard, and optionally 
      solar panels and batteries.
      Connect the LDR sensor to the analog input pin of the NodeMCU to detect ambient light levels.
      Connect the PIR sensor to a digital pin to detect motion.

Circuit Assembly:
     Integrate the LDR and PIR sensors with the NodeMCU.
     Connect the output pin of the NodeMCU to an LED or relay controlling the streetlight model.
     Ensure common ground and proper voltage levels are maintained.

Programming the Controller:
     Use the Arduino IDE to write a code that:
         Reads values from LDR and PIR sensors.
         Turns on the light when motion is detected in low-light conditions.
         Keeps the light off or dim when no motion is detected.
         Include Wi-Fi credentials to connect the NodeMCU to the internet.

Cloud Communication:
     Integrate with a cloud platform like Blynk or ThingsBoard.
     Implement MQTT protocol to transmit sensor data and receive control commands.
     Configure a real-time dashboard to display light status, energy usage, and fault alerts.

Energy Management:
    Add logic to dim the lights during low-traffic hours.
    If applicable, connect the system to a solar charging unit for off-grid deployment.

Security and Data Logging:
    Ensure secure (encrypted) communication between device and cloud.
    Log data for uptime, power usage, and error reports for later analysis.

System Testing:
    Test the responsiveness of sensors under various lighting and movement conditions.
    Simulate urban load with multiple device nodes to test scalability and stability.
    Monitor system performance via the cloud dashboard.

Final Optimization:
    Calibrate sensor thresholds to avoid false triggers.
    Optimize code for energy efficiency and faster execution.
    Validate the overall system reliability through repeated tests.

Documentation and Screenshots:
    Include real-time dashboard screenshots showing:
    Light status updates
    Motion detection logs
    Power consumption analytics
    Fault alerts

