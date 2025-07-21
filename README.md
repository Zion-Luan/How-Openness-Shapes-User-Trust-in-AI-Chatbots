## Research topic
**The Role of Openness Similarity in Shaping User Trust in AI Assistants**

### 🧠 1. Research Objective
Does similarity in openness between the user and the AI lead to higher levels of trust?

### 🧪 2. Method Overview
Using an experimental approach, this study builds three AI assistants with different levels of openness (high = 0.9, medium = 0.5, low = 0.1), 

while keeping the other four Big Five personality traits — _(conscientiousness, extraversion, agreeableness, and neuroticism)_ — fixed at a medium level (0.5).

Users interact with all three AI assistants using the same set of questions. 

After each interaction, they complete a trust questionnaire, so that we can use quantitative comparison of how different personality styles affect users’ perceived trust.

### 💻 3. Model Setup and Implementation

This project uses the Qwen language model through Alibaba Cloud DashScope.

Why Qwen: Qwen has a neutral style, which makes it easier to control personality using system prompts and the temperature setting.

Personality control: Only the Openness trait is changed (high = 0.9, medium = 0.5, low = 0.1). The other four Big Five traits (Conscientiousness, Extraversion, Agreeableness, Neuroticism) stay at a medium level (0.5) to keep them the same.

high:
<img width="996" height="417" alt="image" src="https://github.com/user-attachments/assets/47e4886a-162c-4755-89c0-81adc0ff1933" />

medium: 
<img width="1000" height="402" alt="image" src="https://github.com/user-attachments/assets/7bef9e91-47b3-4c0e-9b87-dc571f47015d" />

Low:
<img width="1033" height="388" alt="image" src="https://github.com/user-attachments/assets/6c47f9c2-3c16-4ed4-aca8-ed907d0f3205" />


Natural conversation: The chatbot uses stream to give responses in real time and keeps the conversation context with conversation_history so that the dialogue feels smooth and connected.


### 🗣️ 4. Question setting for asking AI 
Design Principles:
This study designs seven unified tasks, which are carried out from seven aspects: advice, emotional support, story generation, philosophical judgment, real - world decision - making, language creation, and value preference. These tasks comprehensively cover the typical behavioral characteristics of the "open - minded personality" at the cognitive, expressive, emotional, and value levels.
This design can not only fully stimulate the personality style of the AI assistant but also provide stable and perceivable clues for users' trust judgment, which is conducive to the subsequent accurate analysis of the personality - trust relationship.

**📋 Appendix tables：**

| Question No. | Question                                                                                  | Design Purpose                                                           | Related Openness Sub-dimension           |
| ------------ | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------------------------------------- |
| Q1           | Can you recommend a book that can boost creativity? Why?                                          | _To observe the AI's ability to give creative and imaginative suggestions_ | Creativity / Imagination                 |
| Q2           | I've been feeling lost lately and don't know what to do next. What would you suggest?             | _To test emotional understanding and practical advice-giving_              | Emotional depth / Empathy                |
| Q3           | If you were an artist, how would you describe "loneliness"?                                       | _To assess the AI's abstract thinking and aesthetic expression_            | Artistic sensitivity / Abstract language |
| Q4           | To what extent do you think humans should rely on artificial intelligence?                        | _To explore philosophical and reflective thinking_                         | Philosophical thinking / Curiosity       |
| Q5           | I'm torn between pursuing graduate school or starting a job. Can you help me analyze the options? | _To test multi-perspective reasoning and decision support_                 | Rational thinking / Cognitive complexity |
| Q6           | Can you tell me an original story with a twist?                                                   | _To trigger language creativity and storytelling ability_                  | Creative expression / Story construction |
| Q7           | In teamwork, do you think innovation or stability is more important? Why?                         | _To explore the AI's value preference between change and tradition_        | Innovation vs. Structure Preference      |


### 👥 5、Participants
Use a Big Five personality test to get each user's scores on all five traits.

Then, select users whose scores on the other four traits _(Conscientiousness, Extraversion, Agreeableness, Neuroticism)_ are around the middle level,

and only keep users who have different levels of Openness (high, medium, or low).

_Multiple countries to cover different cultural backgrounds and language habits as much as possible._

### 🧾 6、Trust Questionnaire
Source of the Trust Questionnaire：
The trust questionnaire is from Jian et al. (2000) —— Foundations for an Empirically Determined Scale of Trust in Automated Systems. 

This scale is the most widely used standard scale in human-computer trust research at present.

**📋 questionnaire：**

<img width="496" height="739" alt="image" src="https://github.com/user-attachments/assets/eadf4ecd-4406-4523-adfb-f08c706d8b25" />

**🕒 Timing of filling：**

After completing the conversation task with each AI personality assistant, users should fill out this questionnaire immediately.

Each user is required to fill out three questionnaires (corresponding to AI with high, medium, and low openness respectively).

### 7. Structure of the referenced papers:
(Sharan and Romano, “The Effects of Personality and Locus of Control on Trust in Humans versus Artificial Intelligence”)

Because this paper also discusses the exploration of the Big Five personality traits and the trust in AI. 
I think I can refer to the structure of this paper and some process for finding participants.

