# Unity ChatGPT Assistant Experiments
Few examples with ChatGPT API where we create a ChatGPT Assistant in Unity. This is all based on [my 🤖 ChatGPT with Unity video series on YouTube](https://www.youtube.com/watch?v=6pWoVRYNWws&list=PLQMQNmwN3Fvxec05vELA3D05-Y93LzFt_&index=6)

🔔 *Support all my work by [Subscribing to YouTube](https://www.youtube.com/@dilmerv?sub_confirmation=1)* thank you !

## ChatGPT Assistant Demo Scenes

|Scenes||
|---|---|
|**ChatGPTAssistant.unity**: a ChatGPT assistant scene that shows you how to use ChatGPT API in Unity to create an AI assistant which explains how source generated source code works||
|<img src="https://github.com/dilmerv/UnityChatGPTAssistant/blob/master/docs/images/ChatGPTAssistant_1.gif" width="300">|<img src="https://github.com/dilmerv/UnityChatGPTAssistant/blob/master/docs/images/ChatGPTAssistant_2.gif" width="300">|

## Unity Requirements:
1. Unity 2021.3.8f or greater
2. [Roslyn C# - Runtime DLLs](https://github.com/dilmerv/UnityRoslynDemos) which you can get from the Resources folder. I'm also planning to add the Class Library project to GitHub which should allow you to generate these DLLs yourself.
3. Open any of the available scenes
4. Create an account in [OpenAI](https://platform.openai.com/signup)
5. Get a new [API Key](https://platform.openai.com/account/api-keys) and your [API Organization](https://platform.openai.com/account/org-settings)
6. Update ChatGPTSettings file located under Assets/Settings/ChatGPT/
   
   <img src="https://github.com/dilmerv/UnityChatGPTAssistant/blob/master/docs/images/ChatGPTSettings.png" width="300">

7. Each scene has a ChatGPTTester game object & script in the hierarchy, feel free to associate a new ChatGPTQuestion scriptable object as a reference as shown below:

   <img src="https://github.com/dilmerv/UnityChatGPTAssistant/blob/master/docs/images/ChatGPTQuestion.png" width="300">
