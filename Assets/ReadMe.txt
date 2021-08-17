* Visual Shader Graph
	- Auto: Recompile automatically when adding new blocks to the context
	- Contexts: Each box is defined as a context. They are running from top to bottom
		* Spawn Context - let you determine how many particles should be created in the current frame
		* Initialize Particle Context - the initial values for particles
		* Update Particle Context - runs every frame. This is great for when running simulations, physics, collisions etc
		* Output Particle Quad Context - determines how particles are being rendered on the screen
	- Blackboard: whenever we create a property, it will be stored in the blackboard and can be dragged from there to the graph. The properties in the blackboard
				  are exposed in the Unity inspector 