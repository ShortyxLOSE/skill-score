## score
Reports latest MLB scores

## Description 
Skill-score is an application that enables Mycroft to answer user questions about Major League Baseball (MLB) scores. [Mycroft](https://mycroft.ai) is an open-source AI voice assistant. Skill-score uses [panzarino's mlbgame API](https://github.com/panzarino/mlbgame) to report an MLB team's latest final scores, including live scores. 

User input has the format:
<br />"What is the {team}'s score?"

If a game is in progress, Mycroft will respond:
<br />"The {team} are winning/losing {score} to {score} against the {opponent} in the top/middle/bottom/end of the {inning}."

If a game is not in progress, Mycroft will respond:
<br />"The {team} won/lost {score} to {score} against the {opponent} {number-of-days} ago."

### Next Goals

The next goals for skill-score are the ability to: 
* give the time of the next MLB game; and
* support more leagues (e.g., National Football League, National Basketball League), depending on available APIs.

## Examples 
* "what is the Royals score"
* "what is the Angels score"
* "what is the Yankees score"

## Getting Started

### Prerequisites
Download the following prerequisites:
1. Mycroft - see [installation details](https://mycroft.ai/get-mycroft/)
2. Mycroft Skills Manager (msm) - see [installation details](https://github.com/MycroftAI/mycroft-skills-manager)
    - msm will install skill-score in the correct directory with the necessary requirements

### Installation
In the console, install skill-score using:
~~~
msm install https://github.com/deejcunningham/skill-score
~~~


## Credits 
deejcunningham