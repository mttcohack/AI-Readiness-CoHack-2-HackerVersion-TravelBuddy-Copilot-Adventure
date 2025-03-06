# MTT CoHack Challenge : AI Readiness Team: CoHack #2: TravelBuddy Copilot Adventure

## Objective
Develop a Copilot agent that acts as a travel assistant, providing information about any city across the globe.
<img width="602" alt="image" src="https://github.com/user-attachments/assets/a47f9013-fad3-43ef-a075-ac80a8851779" />


## Task 1: Configure System Topics
1. **Conversation Start**: Set up the initial greeting and introduction for the travel assistant.
2. **End of Conversation**: Define how the conversation will be gracefully ended.
3. **Fallback**: Configure responses for when the agent doesn't understand the user's input.

## Task 2: Create Prompt Action
1. **Input**: City name.
2. **Output**: A prompt that provides the following details:
   - Place of travel: City
   - Best time to travel:
   - Top 5 places to visit:
   - Activities that can be done:
   - Food:

## Task 3: Create Custom Topic
1. **User Input**: Get the city name from the user.
2. **Call Prompt Action**: Use the prompt action created in Task 2 to fetch travel information.
3. **Display Result**: Show the travel information to the user.

## Task 4: Add Email Option
<img width="610" alt="image" src="https://github.com/user-attachments/assets/86ae2ecf-3f01-495c-9135-a1d49d153fac" />


1. **Question Node**: Ask the user, "Would you like to get this information emailed to you?"
2. If Yes:
   - Get the user's email address.
   - Use a flow action to send the travel information to the provided email address.

## Task 5: Deploy the Agent
1. **Teams Deployment**: Deploy the travel assistant agent to Microsoft Teams for team members to use.

## Reference Resources
- [Use system topics - Microsoft Copilot Studio ](https://learn.microsoft.com/en-us/microsoft-copilot-studio/authoring-system-topics?tabs=webApp)
- [Create and edit topics - Microsoft Copilot Studio ](https://learn.microsoft.com/en-us/microsoft-copilot-studio/authoring-create-edit-topics?tabs=webApp)
- [Extend Microsoft 365 Copilot or Copilot agent with prompt actions (preview) - Microsoft Copilot Studio ](https://learn.microsoft.com/en-us/microsoft-copilot-studio/microsoft-copilot-extend-action-prompt)
- [Call a flow as an action - Microsoft Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/advanced-use-flow)
