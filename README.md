# defaultdict

defaultdict is a container like dictionaries present in the module collections. defaultdict is a sub-class of the dict class that returns a dictionary-like object. The functionality of both dictionaries and defualtdict are almost same except for the fact that defaultdict never raises a KeyError. It provides a default value for the key that does not exists.

A defaultdict works exactly like a normal dict, but it is initialized with a function (“default factory”) that takes no arguments and provides the default value for a nonexistent key.

A defaultdict will never raise a KeyError. Any key that does not exist gets the value returned by the default factory.
 
