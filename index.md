2. ##
```$ grep -v '[a-zA-z]' biomed/*.txt | head -10```
```

```

```$ grep -r -v 'police' 911report/*.txt | head -10```
```
911report/chapter-1.txt:
911report/chapter-1.txt:
911report/chapter-1.txt:
911report/chapter-1.txt:"WE HAVE SOME PLANES"
911report/chapter-1.txt:
911report/chapter-1.txt:    Tuesday, September 11, 2001, dawned temperate and nearly cloudless in the eastern United States. Millions of men and women readied themselves for work. Some made their way to the Twin Towers, the signature structures of the World Trade Center complex in New York City. Others went to Arlington, Virginia, to the Pentagon. Across the Potomac River, the United States Congress was back in session. At the other end of Pennsylvania Avenue, people began to line up for a White House tour. In Sarasota, Florida, President George W. Bush went for an early morning run.
911report/chapter-1.txt:
911report/chapter-1.txt:    For those heading to an airport, weather conditions could not have been better for a safe and pleasant journey. Among the travelers were Mohamed Atta and Abdul Aziz al Omari, who arrived at the airport in Portland, Maine.
911report/chapter-1.txt:
911report/chapter-1.txt:INSIDE THE FOUR FLIGHTS
```

```$ grep -A 2 "police" 911report/*.txt | head -5```
```
911report/chapter-10.txt:                of a military police lead vehicle and a van; the proposed briefing theater had no
911report/chapter-10.txt-                phones or electrical outlets. Staff scrambled to prepare another room for the
911report/chapter-10.txt-                President's remarks, while the lead Secret Service agent reviewed the security
--
911report/chapter-11.txt:                officials-local airport managers and local police departments- who had not seen such
```
```$ grep -A 1 "CIA" 911report/*.txt | head -5```
```
911report/chapter-1.txt:    At the White House, the video teleconference was conducted from the Situation Room by Richard Clarke, a special assistant to the president long involved in counterterrorism. Logs indicate that it began at 9:25 and included the CIA; the FBI; the departments of State, Justice, and Defense; the FAA; and the White House shelter. The FAA and CIA joined at 9:40. The first topic addressed in the White House video teleconference-at about 9:40-was the physical security of the President, the White House, and federal agencies. Immediately thereafter it was reported that a plane had hit the Pentagon. We found no evidence that video teleconference participants had any prior information that American 77 had been hijacked and was heading directly toward Washington. Indeed, it is not clear to us that the video teleconference was fully under way before 9:37, when the Pentagon was struck.
911report/chapter-1.txt-
--
911report/chapter-10.txt:                proposed inserting CIA teams into Afghanistan to work with Afghan warlords who would
911report/chapter-10.txt:                join the fight against al Qaeda.46These CIA teams would act jointly with the
```


```$ grep -E "Flight [0-9]{2}" 911report/*.txt | head -5```
```
911report/chapter-1.txt:    Between 6:45 and 7:40, Atta and Omari, along with Satam al Suqami, Wail al Shehri, and Waleed al Shehri, checked in and boarded American Airlines Flight 11, bound for Los Angeles. The flight was scheduled to depart at 7:45.
911report/chapter-1.txt:    In another Logan terminal, Shehhi, joined by Fayez Banihammad, Mohand al Shehri, Ahmed al Ghamdi, and Hamza al Ghamdi, checked in for United Airlines Flight 175, also bound for Los Angeles. A couple of Shehhi's colleagues were obviously unused to travel; according to the United ticket agent, they had trouble understanding the standard security questions, and she had to go over them slowly until they gave the routine, reassuring answers.
911report/chapter-1.txt:    Washington Dulles: American 77. Hundreds of miles southwest of Boston, at Dulles International Airport in the Virginia suburbs of Washington, D.C., five more men were preparing to take their early morning flight. At 7:15, a pair of them, Khalid al Mihdhar and Majed Moqed, checked in at the American Airlines ticket counter for Flight 77, bound for Los Angeles. Within the next 20 minutes, they would be followed by Hani Hanjour and two brothers, Nawaf al Hazmi and Salem al Hazmi.
911report/chapter-1.txt:    About 20 minutes later, at 7:35, another passenger for Flight 77, Hani Hanjour, placed two carry-on bags on the X-ray belt in the Main Terminal's west checkpoint, and proceeded, without alarm, through the metal detector. A short time later, Nawaf and Salem al Hazmi entered the same checkpoint. Salem al Hazmi cleared the metal detector and was permitted through; Nawaf al Hazmi set off the alarms for both the first and second metal detectors and was then hand-wanded before being passed. In addition, his over-the-shoulder carry-on bag was swiped by an explosive trace detector and then passed. The video footage indicates that he was carrying an unidentified item in his back pocket, clipped to its rim.
911report/chapter-1.txt:    Newark: United 93. Between 7:03 and 7:39, Saeed al Ghamdi, Ahmed al Nami, Ahmad al Haznawi, and Ziad Jarrah checked in at the United Airlines ticket counter for Flight 93, going to Los Angeles. Two checked bags; two did not. Haznawi was selected by CAPPS. His checked bag was screened for explosives and then loaded on the plane.
```

```$ grep -E "([A-Z][a-z]{2,})-[0-9]{3,}" biomed/*.txt | head -5```
```
biomed/1471-2091-2-10.txt:          mAb directly conjugated to Alexa-488 revealed that α3β1
biomed/1471-2091-2-10.txt:          anti-α4-Alexa-488 mAb revealed a diffuse pattern of
biomed/1471-2091-2-10.txt:          no Alexa-488-conjugated antibodies were added, no
biomed/1471-2091-4-1.txt:          Microcon-100 (Amicon). The reaction mixtures were diluted
biomed/1471-2121-3-8.txt:        sequences are Gly-247, Gly-284 and Cys-450 in our Hyal-1
```

```$ grep -r -hc "CIA" government | sum```
```
22786     1
```
```$ grep -hc "3-2" biomed/*.txt | sum```
```
32610     2
```

