The five steps to transfer data from parent to child
![[setting_up_input.png]]
1) Parent component = app.component & Child Component = card.component 
	 ![[child-component_inside-parent-component.png]]
 ![[Data-in-parent-component.png]]
![[parent_to_child.png]]

2) Decide on a property name that we want to use: imageUrl, title, username, content
![[property_component.png]]
3) Add the new binding in the child component -- specify the data we want to pass down
	![[property-binding.png]]

 4. add an Input property in the child class
 ![[input_prop_in_class.png]]

5) In child template file, reference the input property
 ![[referencing_input_props.png]]
 


