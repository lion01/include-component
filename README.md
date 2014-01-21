This plugin is to include a component in an article without an iframe. So the links will work like in an normal page and styling of the site will be used and also the style of the component.

The following features are added, changed or solved in the latest version:
* Option to remove the print parameter in the url
* Adapted plugin for Joomla 2.5 and 3.0
* Remove special javascript content type around scripts to prevent problems with IE
* Support for https

The syntax is {component url='' }
Replace with the url to your component and include index.php?

For example:
{component url='index.php?option=com_component&Itemid=73&parameters....' }
