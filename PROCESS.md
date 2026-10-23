**Starting idea**
My initial concept was nine rotating boxes that scale up and disappear on mouse hover. However, this design lacked clear, meaningful interaction feedback. Following AI suggestions, I changed the concept into a memory matching card game.

**A design or code change I made**
During coding, one pair of cards always appeared blank without any emoji. I struggled to fix this bug until I switched to another AI tool. I found that certain emojis could not render correctly in browsers. I replaced them with more widely supported, common emojis to solve the issue.

**User trial and my response to it**
In early testing, players did not notice that their score decreased for wrong matches, and there was no feedback when the score reached zero. I added a losing sound effect to notify players about score deduction and created a lose ending screen. I also added a win ending and a sound effect for correct matches. To improve tolerance for mistakes, I gave players a starting score of 40, allowing four incorrect guesses. Testing showed most players can complete the game smoothly with this setting.

**AI tools I used and for what**
I used two different AI tools to help develop and deploy the code. I also used AI to translate and polish my README and design process writing.

**One suggestion I kept**
My original idea was too simple. AI proposed the memory card matching format, which is engaging and fun and did not require a complete rewrite of my code structure. I adopted this suggestion.

**One suggestion I rejected**
AI suggested generating a custom victory audio clip for the game. Since I have limited music knowledge, all generated results sounded unnatural. I rejected this idea and downloaded a suitable sound effect from a stock audio website instead.