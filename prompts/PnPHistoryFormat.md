---
PromptInfo:
  author: pheelwell
  description: null
  id: PnPHistoryFormat
  name: "\U0001F9D9 Rewrite as 📅History Template"
  version: 0.0.1
---
Additional information for Context
(DONT INCLUDE INTO PROMPT! THIS IS JUST CONTEXT!):
{{title}} ({{type}}): 
{{#each sum}}
- {{this}}
{{/each}}

{{#each children}}
{{this.basename}}:
{{#each frontmatter.sum}}
- {{this}}
{{/each}}

{{/each}}

Additional connections that MIGHT be useful: 
{{#each mentions.linked}}
Connection to: {{basename}}
{{#each results}}
- {{this}}
{{/each}}
{{/each}}

The above text is just lore information, use it for context on how characters behave or facts about citys to build uppon, but don't reiterate the bullet points above.
When writing text you can these callouts:

> [!info] Info
> The Information you want to convey 

> [!tip] GM Tip, Hint, Important
> Something useful could stand here
    
> [!warning] Warning, Caution, Attention
> Something Important to be reminded of
  
> [!quote] Quote
> The actual Quote or thing that should be 

>[!read] Read to the Player
>This is Prose that is read
>ONLY USE THIS IN PLOTS AND SCENES, NOT IN WORLDBUILDING ARTICLES

>[!seed] Seed, Adventure Hook
>This is something you could use to build your adventure upon

>[!secret]- 
> This should not be directly revealed to a player

Only use the Callouts if it is important to do so, do not try to use them all the time.
When talking about topics listed above, use the [[Topic]] annotation to link to Article: [[ ]]

Add creative and unique flavor that makes the text to rewrite Intresting.
Don't let out Details mentioned about the text when rewriting.
Always add the Quick Refference!
When writing use this template:
TEMPLATE START

Start with a flavor text (for example a simple scene) that hooks in the reader, give a first impression (don't reveal secrets)
## Overview
two paragraphs with most important facts about the History
## Timeline:
- [[Event 1]]: Brief description...
- [[Event 2]]: Brief description...
## Major Events:
### Event 1
- Description...
### Event 2
- Description...
## Key Figures:
- [[Figure 1]]: Context to History
- etc
## Impact on Present Day:
## Campaign Connections:



TEMPLATE END


CONTENT TO REWRITE START
{{selection}}
CONTENT TO REWRITE END

Rewrite the above CONTENT TO REWRITE in the style of a dungeons and dragons campaign guide using the exact template above. always include the quick reference (formatting is important)
Keep every detail of the CONTENT TO REWRITE while rewriting.

