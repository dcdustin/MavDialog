MavDialog
=========

MavDialog is a light-weight, easy to use and customizable replacement for system dialog windows. It contains child classes for replacing the default alert, prompt, and confirm dialog boxes as well. There are options for forcing user input (by preventing user access to the rest of the page) and the message of the dialog box can be loaded from a string, adopted from an existing DOM element, generated by a function, or retrieved by an Ajax request.

![MavDialog](http://github.com/dcdustin/MavDialog/raw/master/logo.png)

How to use
----------

*JS*

	#JS
	new MavDialog({
		'title': 'Dialog Header',
		'message': 'This is what will show up in the content of the dialog box.'
	});


Methods
-------
MavDialog.setMessage();
MavDialog.show();
MavDialog.hide();
MavDialog.close();
MavDialog.screen_center();
MavDialog.toggle_shade();
