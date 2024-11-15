# Web_Application-_Gilmore
In Innovation and Complexity Management, we will learn about and work on real-time web applications and data visualisation. In Media Management, you will work on the hardware and the data analytics to acquire biomedical sensor data. In groups of 5 your challenge will be in building an end-to-end sensor-based real-time web application using medical grade sensors and Arduino, collecting this data, developing a well functioning app using frontend and backend.

Here are the dos:
…focus on a very specific user group and their core job to get done. Understand or imagine every little detail.
…think about the ways your user needs to receive, transform and send data. Try to automate or simplify their lives.
…optimise on all little details and behaviour in your frontend. Make it a joy to use the app.
…use an iterative and cloud-enabled development process. Make it easy to build everywhere, again and again.

Here are the Don'ts:
…try to make the app targeted at too many users and too many of their tasks. One user with one task is enough.
…use a visualisation framework other than D3.js. High-level frameworks (Plotly, Charts,js, etc.) do not allow for enough customization. You can use frameworks like React, Vue or Svelte for state management though.
…submit a jupyter notebook. Build a Backend suitable for real-time data transmission from a sensor and have it produce a good selection of aggregated data for you to use in the frontend in addition.
…use an exotic or complicated build processes. I will try to automatically get data from Github Codespaces. If your app does not automatically build there, I cannot look at it.

Important Considerations: 
Ensure data privacy and security, adhering to HIPAA regulations.
Focus on user experience for both patients and healthcare providers.
Implement error handling and data validation to ensure accuracy.
Consider scalability in your architecture design.
Plan for regular testing and validation of sensor accuracy.
Provide summary insights (e.g., weekly trends) to give users context for daily readings and long-term goals.
Let the app learn user patterns to provide more accurate recommendations.

Remote Patient Monitoring for Heart Failure Patients: 
The app would focus on monitoring heart failure patients at home; providing real-time data to healthcare providers and patients. Using Arduino with the specified medica-grade sensors will help us collect vital signs. This data will be transmitted to a computer app via bluetooth which will be sent to the cloud backend. 
Sensor Measurements: 
Heart rate 
Use medical-grade sensor MAX30102 for heart monitoring 
Blood pressure 
Use medical-grade sensor OMRON D6T for non-contact temperature sensing 
Weight 
Load cell for weight measurement
Activity Level (steps)
Use medical-grade sensor MPU-6050 accelerometer for activity tracking 
Backend Development: 
Use Node.js with Express for the server
Implement WebSocket for real-time data transmission
Use MongoDB for data storage
MongoDB offers a community version 
Frontend Development: 
Develop a React-based web application
Use D3.js for custom data visualisations
Implement responsive design for mobile and desktop use
Data Analysis: 
Develop algorithms to detect anomalies in vital signs
Create trend analysis for patient health metrics
Implement predictive models for early intervention

