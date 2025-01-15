Project Goal:
   - Automatically sends you am email when the ISS Space Station is above your coordinates

Flow of Execution:
	1.	Retrieve ISS Position:
	•	The ISS’s current position is fetched, and its proximity to your location is determined.
	2.	Check Nighttime:
	•	The script checks whether it is dark at your location.
	3.	Send Email If Conditions Are Met:
	•	If both the ISS is nearby and it is nighttime, an email is sent.
	4.	Repeat Every Minute:
	•	The script waits for 60 seconds and checks the conditions again.
