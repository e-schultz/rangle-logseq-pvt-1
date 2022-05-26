parent:: [[Molex Overview]]

- Libraries & Tools
	- Vue 2 - https://v2.vuejs.org/
	  collapsed:: true
		- Project had already been started using Vue 2, and was using Vuetify for the component library, which does not support Vue 3 yet.
	- Vuex - https://v3.vuex.vuejs.org/
	  collapsed:: true
		- Vuex for state management, however some challenges with the implementation
			- v-model directly mutating the store
			- one main "update everything" action - no granularity
			- tight coupling between the JSON schema, the store, and the components using them
				- we did do some work on having a mapping layer to make the schema easier to work with in Vue
	- Vue Router - https://v3.router.vuejs.org/
	  collapsed:: true
		- Use of Vue router was iffy - when the application is actually in use, it's run as an embeded web view in a desktop application and has no "browser controls", so the PO had not thought about forward / back / reload / etc type of navigation.
		- at one point they had mentioned possibly wanting to remove the router since they "don't need it"
			- technical-risk:: Removing the router is a a bad idea
			  Effective use of the router can greatly simplify the application, data loading, managing the "where am I in the application state", even if the end-user does not see the URL
				- impact:: Developer Productivity - Dev Experience
					- Developers would mention that when working on the application, if they had to reload the page they had to
						- to navigate back to the first screen of the application
						- select the module
						- select the sub module
						- a few more steps
						- and back at their previous screen
					- this was a point of frustration, lead to needing to repeat a lot of steps.
						- the core issue was how the router was being used, and replicating some of what could have been kept track of through the URL, via updating the vuex state instead.
						- other considerations: storybook for an isolated development enviornment
						-
					-
				-
			-
	- Vuetify - https://vuetifyjs.com/en/
	  collapsed:: true
		- Doesn't support Vue 3 yet
		- was ok to work with
		- main pattern in the application - "creating wrappers around veutify to work with our dynamic components"
	- JSON Schema - https://json-schema.org/
	  collapsed:: true
		- [[molex-challenge - The role of JSON Schema was not apparent, nore made clear early on]]
		-
	- Ajv JSON schema validator - https://ajv.js.org/
	- .NET Blazor
	- StackBlitz
	- CodeSandbox