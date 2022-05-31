client:: [[Molex]] 
parent:: [[molex challenges]]

	- Patterns:
	  id:: 628fe739-3c32-482e-abc4-7a1bd0153be5
		- [Why didn't you already know this?]([[molex - pattern - why didn't you already know this]])
		  id:: 04d7f374-5f9f-4d5d-af0a-7d0dad77d9b7
		- [Thinking Out Loud - What's now, whats later?]([[molex - pattern - thinking out loud, unclear if what they are saying is for now or later]])
		  id:: 925f9771-8d8d-4a28-87a7-e3d9b4b96c48
		- [It's Obvious to me, why not you?]([["molex pattern - "it's obvious to me, why isn't it obvious to you?""]])
		  id:: 85498c99-eb82-4755-83dc-06ab73325e5f
		- [you have a good idea, they are now in scope]([["molex pattern - "you have a good idea, they are now in scope"]])
		  id:: 07d3f8e4-466c-4318-b9ae-1298980ebe56
-
- _here be dragons_
	- **"why didn't you already know this?"**
	  id:: 628eada4-dc80-4eea-ad34-1b0b4854d21a
		- pattern - a conversation pattern would start to occur when talking with one of the product owners.
		  id:: 3d27730b-317b-4ffb-9841-ce9104fe4ce4
		  
		  The questions people would be asking, were reasonable "this helps provide clarity to the thing I am being asked to do", and need to know information for completing the story.
		  
		  However, how they would answer the question / end the conversation, would be in a way of saying - "you should have known this already, and if you didn't know already - why hadn't you asked sooner?"
			- **impact** - team didn't feel as safe asking questions
			  collapsed:: true
				- **action** - I get more involved
					- more hands on with the devs
					- join meetings with them and that PO
					- play PO to team translator a bit better
	- **"thinking out loud, unclear if what they are saying is for now or later"**
		- **pattern** - When doing a code review, or walking through a user story / figma, etc and talking about the work that needs to be done.
		  id:: 628eaee2-850a-4438-a1f6-8f95dadd9357
		  
		  There are many areas in the code base that could be improved, and a number of them have been suggested / documented / shared.
		  
		  The PO though - had a walk of providing feedback where it was hard to always tell if what he was talking about was meant for a "this should be done right now", vs "this is something that could be done later"
			- **impact** - Scope creep
			  It would be easy to think that everything that we had talked about was to be done,
			  or someone would think that A and B but not C, and they were expecting B and C, and A for later.
				- at times this lead to more complex / larger PR's due to adding 'all the features'
				- duplicated work - as at times these conversations would happen with different people on different areas of the code
				- not a shared understanding of whats now vs whats later
					- **action:** Clarify in Writing at the End
						- Clarify - what are we doing now, vs later - get them to agree, and then update the ticket to reflect that
					-