title:: TIAA/TIAA - 2022/spikes/Angular Material
notion:: [TIAA - Angular Spike](https://www.notion.so/rangle/Angular-Material-Spike-6101a88d9df64b178f8769215dbca853)

-
- # Meeting Notes
	- ## 2022-08-07 - TIAA - Angualr Spike Standup Notes
	  notion:: https://www.notion.so/rangle/7-8-2022-Spike-stand-up-notes-7aae5bf52c664e4896298e2f3bd7b2d4
		- Some items Bob had brought up
			- TIAA also has a spike implementing angular web components
			- Material 3 introduced tokens, bob wants to future proof when angular material implements
			- Concerned with bundle size of web components as angular element bundles can start to get larger and larger especially when angular material is implemented.
			  id:: 27688e09-05ed-4e1c-b77e-b5b24006bcdc
				- Not too bad for small components but with larger ones the bundles will increase fast ex. Button vs. Table
			- What is the best way to implement tokens, css variables?
			- Wants to explore lazy loading of the web component.
			- Pattern library : How important is it? What toolkit? Css grid, custom elements.
			- ds naming convention would be ethos with version number as they update over the years. ex. ethos1 for version 1, ethos2 for version 2
			- Naming convention would only use the major version as they make updates to a version, such as 1.0.1, 1.0.2 would still use ethos1.
			- For now they suggested we use tiaa-ethos