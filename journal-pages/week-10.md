---
layout: default
---

# Week 10

[← Back to Home](../index.md)

## Documentation 
**21/05/2026** 

# **Starting Experiment 3**

For this experiment, I would be using vibe coding to achieve a fast making experiment. 

I first put in the prompt first, "can you give me a experiment idea that looks like the AI is monitoring the curser? so like something is following the curser on the canvas in p5.js" 

The ai I will be using is deepseek.

![alt text](../assets/week-10/Screenshot%202026-05-25%20175751.png)

It generated a code and I went ahead and popped it into p5.js, 

<iframe src="https://editor.p5js.org/ezha440/full/DnqGQ2EDe" width="400" height= "400"></iframe>

Which gives a tracker that follows your cursor whereever it is on the canvas. I am surprised that this worked first try? Usually it takes a bit for it to get to what I want. 

![alt text](../assets/week-10/co.png)

The sketch constantly tracks your mouse position and recent movement velocities to predict where you're going next. Typically, 15 pixels ahead along your current trajectory. A red circular "eye" (the AI) moves towards this predicted location, not your actual cursor, creating the unsettling sense that something is anticipating your choices. Your path leaves a blue fading trail (your creative history), while the AI leaves a red trail (its expectations). Over time, a confidence bar rises when your movements become consistent, and if confidence stays high, ghost suggestions appear. Soft visual nudges towards the AI's predicted path. The longer you move predictably, the more the AI "thinks it knows you".

This is great, but I think It could do with more sensors, having multiple follow the cursor. I asked the Ai to add more monitors to the original code. 

<iframe src="https://editor.p5js.org/ezha440/full/GZG27sPlF"width="400" height= "400"></iframe>

![alt text](../assets/week-10/2.5.png)

The sketch creates five independent AI agents, each stored as an object with its own position, prediction strategy, confidence level, and colour. In every frame, the code records the cursor's current position and velocity, then updates each AI's prediction differently based on its strategy: Velocity-AI predicts using recent speed, History-AI averages past positions, Pattern-AI detects repeating movements, Chaos-AI adds random noise, and Meta-AI averages all other AIs' predictions. Each then moves towards its predicted location (not the cursor itself), leaving a coloured trail behind. The dashed prediction lines connect your cursor to each AI's forecast. A white consensus prediction circle shows the confidence-weighted average of all AIs. 

I think this is pretty well done? It is only the second attempt. 

## **Reflection on my experiment- overall**

I fulfilled my goals, it was fast and quick, I didn't spend too long on it and I understood why and how the code worked. 

I do think the text that the code has provided saying that I have become predictable was kinda freaky but I think that was the point of making it speculative. 

## **Reflecting on my Research Journey** 

- Where did you begin? (e.g. a technology, social issue)

I started this journey by focusing on my interests, before linking them to a social issue. (Climate justice and specificlly e-waste). I wanted to test out things within my interests, so using coding and animation the most. 

-  What were some defining moments? (e.g. discoveries, pivots)

I would say when it was the first crit lesson, I had troubles coming up with viable experiments that had both connections with my interests and social issue. And my peers offered useful advice on how I should pivot and suggested that I could start at a point making something for myself, or something that I would deem useful. 

I realized that while designing, this is a perspective I rarely consider. And I have learned that it's helpful in times rather than dedicating to making something for someone else. 

-  When did you encounter challenges?

I struggled with time management. Alot of times I am staying up super late even though with planning I could completly avoided that. This would then lead me being drained and burnt out really fast. I had no motivation to do work and struggled with coming up with ideas. 

As for the technical side, I did find it challenging just because of my lack of skills. But I would like to see it as a learning curve. 

I would admit I struggled with blogging all of my processes down. There were certain times where I would think I am not reflecting enough or I'm just doing the reflection wrong? 

- What were your failures?

I had one experiment that didn't work, although I think that's purely because I had a certain set of goals for it hence why I wouldn't work on it anymore. But everything else I think went okay.
...not including how I said I was gonna better time management but end up not anyway. 

- What surprised you? What did you learn about yourself?

That I procrustinate alot? I found myself being lazier with wanting to do work, or that I am trying to cut corners alot and wanting to get things done as soon as possible. (I wasn't like this before I swear)

- What do you think is your strongest direction? What alternatives do you see?

After being handed the stream briefs I see myself having more of a goal to work towards. For the longest time I struggled because I didn't see an aim? Work/ project wise, I would like to continue researching into the impacts of AI on today's creative industry. (the CREATE part of the emerging tech stream brief) Alternativly, I could look into CONNECT brief, which I also found interesting. 

- Where might you be heading next

I would like to just focus on planning the presentation for week 12. And if things goes well then we will see...


## **Planning Week 12 Presentation** 
