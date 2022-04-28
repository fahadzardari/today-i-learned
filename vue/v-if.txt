Today I learned about v-if in vue. 
A simple explanation :
V-if is used when we have to render specific elements for certain conditions.
For example:
I have to render status complete or incomplete for a task in a simple todo list app, if the status is provided from the database in property todo.status the simple way to achieve this is by using v-if 
	<p v-if = "todo.status == 'complete"> Complete </p>
	<p v-if = "todo.status == 'uncomplete'> Uncomplete </p>

We can also use v-if , v-else
	<p v-if = "todo.status == 'complete"> Complete </p>
	<p v-else> Uncomplete </p>
 For rendering multiple elements place them in template and add the v-if on the template. Template tag will only wrap the elements.
 
 Added on
 28/04/2022 23:07:56 
