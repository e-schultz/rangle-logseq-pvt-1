- Vuex for state management, however some challenges with the implementation
	- v-model directly mutating the store
	- one main "update everything" action - no granularity
	- tight coupling between the JSON schema, the store, and the components using them
		- we did do some work on having a mapping layer to make the schema easier to work with in Vue