# mealtray_dataset
Photos took in the restaurant of my former compagny.\
*Disclaimer: all the photos in my dataset are NOT under licence or NDA. They were given to me by the restaurant adminitration after a lawyer approval.*


Each photo contains a meal tray with various objects on it. Each photo was taken from the same point of view four times : when the "photo kiosk" detects a meal tray, it captures 4 photos to cover the time spent by the employee to place his meal tray correctly.

Each meal tray contains various objects that I labelised with www.cvat.org (www.cvat.ai now). Since the labelisation process is time-consumming, I labelised only about 480 images, feel free to increase this number!

Objects are boxed with rectangles, discribe by relative coordinates (relative to the photo sizes). Each rectangle belongs to a specific class among 8 categories : 
* Plate (the main dish)
* Starter
* Dessert
* Bread
* Yogurt
* Fruit
* Drink (soda can, juice can, water bottle...)
* Cheese (yes, it's a french meal tray, what did you expect ?)

