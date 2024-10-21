# HA_Scripts
A collection of my HA automation scripts

# Add Tasks through Alexa Actions and ChatGPT
## Prerequisites
1. You have to install & set up the following integrations:
- Todoist
- [Extended OpenAI Conversation](https://github.com/jekalmin/extended_openai_conversation) (Might work with the normal integration as well, but I never tried)
- [Alexa Actions](https://github.com/keatontaylor/alexa-actions)

2. Add conversation to your configuration.yaml and reboot
   
    conversation:
  
4. Find out your OpenAI agent ID and replace the placeholder in addtasks.yaml with it.
   To get the agent id: Add the action conversation.process to a script/automation with the visual editor, select ChatGPT as you agent from the dropdown menu, go to YAML view and copy the agent Id
5. Add the scripts from addtasks.yaml to your automations.
