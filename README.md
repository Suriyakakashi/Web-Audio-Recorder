# Web-Audio-Recorder 
Audio Recorder widget is used to record the audio and convert the audio to base64value.

# Configuration-
Place this widget inside the data view and create object to the Chosen Entity for data view.
Add one Attribute with string (unlimited) in that Entity.
Use Onchange microflow to save Audio to file Object.

# screenshots
# Create entity like this below
![image](https://github.com/Suriyakakashi/Web-Audio-Recorder/assets/141641988/19ba3000-8910-40c4-ab33-45b7e4eda90b)

# Place this inside data view to use widget .
Create Data source Microflow to store Base64 value coming from widget in to the String Attribute of that Entity.
![image](https://github.com/Suriyakakashi/Web-Audio-Recorder/assets/141641988/2947442f-ff5e-4250-8be2-1b2c4e2014c0)

<img width="493" alt="Configuration" src="https://github.com/Suriyakakashi/Web-Audio-Recorder/assets/141641988/57a4f7e3-5b88-4a31-bf28-4bd406bcdc03">

# OCH Microfow below to convert base64 to file 
Converting Base64 String value to File using Community commons Java Action.
<img width="561" alt="OCH Audio" src="https://github.com/Suriyakakashi/Web-Audio-Recorder/assets/141641988/246c2829-bbb9-4225-9190-ed37e381814e">

# Decode 
<img width="522" alt="Decode" src="https://github.com/Suriyakakashi/Web-Audio-Recorder/assets/141641988/616437a9-2992-4bf4-904a-e97f5873ca50">

# onclick to start record
<img width="82" alt="Mic" src="https://github.com/Suriyakakashi/Web-Audio-Recorder/assets/141641988/ec647990-f118-4229-af11-bbecdbffe285">

# Again onclick to Stop record
<img width="82" alt="stop" src="https://github.com/Suriyakakashi/Web-Audio-Recorder/assets/141641988/9f7466b8-2983-437e-89f1-2816d07f421a">





