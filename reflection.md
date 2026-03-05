# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

- After I won a game and tried to start a new one, my number of attempts was stuck at 0. I was not able to start a new game. The game never reset.

- When I entered a negative number, I was continuously instructed to "Go LOWER!" even though the Secret number was positive. This does not make logical sense.

- In the "Easy" difficulty mode, the range for the secret number is listed as 1 to 20. However, I was given secret numbers that were outside of this range, like 59, for example.

- Changing the difficulty mode does not reset the game. Instead, it changes the number of attempts I have left to guess the secret number.

- When my secret number was 59, I entered "90" and was instructed to "Go HIGHER". Then, when I entered "30", I was instructed to "Go LOWER", even tho the number 59 is larger than 30. I expected that logic to be flipped.

- I expected the "Hard" difficulty mode to have the widest range of numbers to guess from. However, the range for Normal was 1 to 100, and the range for Hard was 1 to 50. That would make the "Hard" mode easier to guess the secret number than the "Normal" mode.

- My secret number in Normal mode was consistently between 1 and 100. For example, one of my secret numbers was 61. When I started to enter numbers in the 90s, I was consistently instructed to "Go HIGHER!" which does not make sense because 61 is lower than any number in the 90s. However, when I entered the number 100, it 

- MAYBE: On odd attempts, the secret number is turned into a string.

- My secret number in Normal mode was 12. I entered the number 100, and I was instructed to "Go LOWER!" Then I entered 100 again, and I was instructed to "Go HIGHER!" The logic flipped back and forth, telling me to go lower then higher repeatedly, even though I was not entering the same guess on every attempt. I expect to be told the same hint every time I guess the same number.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
