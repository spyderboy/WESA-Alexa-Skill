# WESA-Alexa-Skill
WESA FM skill branched from the WYEP code. Just plays the live AAC radio stream

In my experience the Beta editor for Alexa Skills does not work.  You may need to opt out of the Beta and use this in your Skill Intents:

{
  "intents": [
    {
      "intent": "AMAZON.PauseIntent"
    },
    {
      "intent": "AMAZON.ResumeIntent"
    },
    {
      "intent": "play"
    },
    {
      "intent": "stop"
    }
  ]
}
