---
PromptInfo:
  author: pheelwell
  description: null
  id: PnPThingFormat
  name: "\U0001F9D9 Rewrite as 🔮Thing Template🔮"
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
two paragraphs with most important facts about the Thing

> [!TIP] Quick Reference 
> **Insert Name**
> One sentence description
>- **Type**: What kind of object or concept is this?
>- **Properties**: Unique characteristics or abilities of this thing.
>- **History**: A brief summary of how it came to be and its role in past events.
> ____
>- **Current Location**: Where can this thing be found now?
>- **Roleplaying Tips**: Things to keep in mind when incorporating this thing into your campaign.

## Description 
A detailed account of what this thing looks like, how it functions, and any unique features it possesses.
### Abilities 
Details on any special powers or properties that it has.
### Usage 
How might players interact with or make use of this item/concept? Are there any potential drawbacks or dangers involved?
### History 
The backstory surrounding this thing. How did it come into existence? Who created it or first discovered it? What role has it played in past events?
## Roleplaying 
Tips and advice for how to introduce this thing into your campaign or portray it during gameplay.

TEMPLATE END


CONTENT TO REWRITE START
{{selection}}
CONTENT TO REWRITE END

Rewrite the above CONTENT TO REWRITE in the style of a dungeons and dragons campaign guide using the exact template above. always include the quick reference (formatting is important)
Keep every detail of the CONTENT TO REWRITE while rewriting.

