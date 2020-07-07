# Simple Input Settings
	A simple, yet elegant solution for implementing a modular input binding widget in your project.
	
## FEATURES

	• Entirely done in blueprints!
		- Just in case you need to make changes, the entire system is made using blueprints to make it easy!
	
	• No programming required!
		- The entire system is built with data tables, so you don't have to touch a single widget or blueprint!
	
	• Multiple Lists
		- This can help you separate input to be less confusing for your user.
		- For example, on list can contain character input settings, and another can contain vehicle input settings.

	• Multiple Categories
		- This gives you the ability to filter your input bind keys.

	• Modifier key support
		- The system supports built in engine modifiers (Shift, Alt, Ctrl, Cmd)
		- The system can handle multiple modifiers at once.

	• Add new bindings
		- If desired, your user can add new action or axis mappings. They can even adjust the scale of the axis value!
		
## Documentation

	• Integrating the system is extremely easy!
		
		1. Fill out your category and input list tables.
		2. Add WBP_InputBindParent to your menu.
		3. Select your desired category tables from the class defaults.
		
		That's it, you're good to go! The system will auto generate all of the lists, categories, etc... based on your data table entries. 
	
## Input Lists
	
	Creating input lists should be simple!
	First you will want to create a table for each category.
		For example, if you have a walking character and a car, you can create a table for your character input and a table for your car input.
	Next you will want to fill the category map with an action or axis mapping and link a friendly name. The key value should be the same value as your ProjectSettings's input category!

## List Categories 
	For list categories, you will want to give each category a name and id, then you will want to set a series of list tables to link to the category.
	    For example:
	    	I want to create two categories, one for my character input and one for my vehicle input.
		I have already created x number of unique tables for each category using the steps above.
		First, I would create a table row named 'Character' and link my unique tables for character inputs.
		Next, I would create a table row named 'Vehicle' and link my unique tables for vehicle inputs.
		The system will handle the rest!
	
# If you have any questions please contact me at the support email!
   
