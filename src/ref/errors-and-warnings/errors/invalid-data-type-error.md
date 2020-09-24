# Invalid Data Type Error

Message
:   `Incompatible data types in <operator> operator`

Cause
:   You have data types that aren't compatible with the operator you are using.

Recommendation
:       Check the allowed data types for that operator and use only those.

---
  
Message
:   `<data type> data type required instead of <data type>`

Cause
:   You have the wrong data type in a property or in the operator you are using.

Recommendation
:      Check the allowed data types for the property or operator and use only those.

---

Message
:  `Invalid 'Null Value' data type for specified variable`

Cause
:   You have specified an invalid null value for a the variable data type.

---

Message
:   `Cannot send a 'Binary Data' parameter in the request '<send in>' of a method with '<request format>' request format. Change the parameter data type or the method request format.`

Cause
:    In a REST API method, the request format doesn't allow you to send Binary Data in the place that is set for the parameter.

Recommendation 
:    Change the parameter data type or the method request format