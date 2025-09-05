# Individual-Armageddon

Cloud migration strategy

Headquartered in Sao Paulo, Balerica Inc. is looking to leverage public cloud technologies and services to expand their presence in their target markets. After an extensive search, you have been chosen as the lead consultant for their efforts. Below is information regarding their current tech stack, workflow for their engineers, and overall goals.

## Company Details

Industry = Educational services (IT education, basic computing courses, certification testing center)

Tech Stack
- 30 Lenovo M90 Gen 5 desktops purchased in 2024, with provided mouse, keyboard, webcam, headphones, and HP 24" monitor.
- 3rd party applications hosted on VMWare VMs (Linux and Windows 2016)
- homegrown secure exam browser built in Java, HTML, CSS, and VBScript
- backups hosted on premises; backups are done on a best effort basis
- 3 TP-Link unmanaged switches

Workflow
- click ops; (almost) all administration is done manually
- applications deployed via CMD scripts
- no central codebase
- factory Lenovo image used when (re)imaging desktops
- test proctor launches secure browser before applicant sits down to start the exam, and fixes the browser if applicant experiences issues


Overall goals:
- automate as much as possible
- reduce amount of click-ops
- centralize codebase
- enable remote control capabilities on desktops from administrators only
- cut down on desktop reimaging times & occurrences
- create a lightweight, scalable, secure browser for certification tests that rivals Pearson VUE. 
- testing center in 5 countries (USA, Brazil, Japan, Italy, and Thailand/Phillippines)
- have network infrastructure that connects testing centers to each other, and administrators to the testing centers. communications MUST be as secure and redundant as possible.

******************************************

# Task 1
Create one diagram of Balerica Inc.'s current network topology:
https://lucid.app/lucidchart/b86a7058-d46b-43b0-beea-4918215db2d8/edit?invitationId=inv_e6b1d5be-2af8-4a33-a8f4-fffadb41c1c1

and then create a second diagram detailing your recommendations pertaining to the expressed goals:
https://lucid.app/lucidchart/13568e32-a909-4817-b557-9380935e5aac/edit?invitationId=inv_1b8aa5ab-121b-4470-b480-88a030d88c7b
