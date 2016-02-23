jQuery plugin to customize the default select list

#	Plugin initialize
	1. Add "data-select-box" to a div containing <select> option list
	2. Call $(selector).customSelect(); to element containing <select> option list or to the <select> itself

#	Plugin parameters
###title
	Type: String
	This is the select menu title.
	Default - "Please choose"
	You can specify custom text - title: "My select menu title"
	You can use the text of the first select menu option - title: 'first'
	Example: $(selector).customSelect({title: 'My select menu title'});

###selected
	Type: Boolean
	Specify if the first select menu option is preselected.
	Default: false
	
###height
	Type: Boolean
	Specify the maximum height of the select menu. If the menu is larger inner scroll will appear.
	Default: false
	
###width
	Type: Boolean
	Specify the width of the select menu.
	Default: false
	
###arrow
	Type: Boolean
	Adding <div> to be used for arrow in the title box. In example.html the arrow is made with CSS and no images.
	Default: true
	
###rebuild
	Type: Boolean
	When updating the select menu with new values this parameter is needed when the update occur.
	Default: false
	
###destroy
	Type: Boolean
	Removes all generated HTML and clears javascript events.
	Default: false
	
#	Plugin Styling
	The plugin doesn't apply visual styling.
	You can use this basic CSS to get started with your customization:
