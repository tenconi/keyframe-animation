In this example, we are going to animate a SVG (Scalable Vector Graphics)in CSS with "@keyframes" technology.
For employing this property we must define the "keyframes" by means of percentages or employing "from" and "to". Then we're gonna call the keyframe with the "animation" property, for example:

.className{
	animation: 3s exampleAnima infinite;
		/* duration  name  iteration */
}

@keyframes exampleAnima {
	from{
		opacity: 0;
	}
	to{
		opacity: 1;
	}
}