# IR-Player
This is a WPF project for infrared thermal imaging and processing.
This is also my first complete WPF project. I want to set up a player for infrared thermal imaging. It's like any other imaging procedure only add some infrared thermal process method(you can find the methods in the class InfraredImagePrcess). It uses UDP protocol to transport the image data. 
It tested just ok I thought. But there are still several problems I need to point out. If you had glanced over the codes, I used the Task class to execute image receiveing, processing and displaying. I found asynchronous programming is little difficute for me. Is there any preferable and more efficiency ways to accomplish procedure? 
Due to the image processing of infrared thermal images, I took use of EmguCV library. Well, it's really consuming memory enormously. When I employed the ColorMap, it matters performance somewhat. Retaining existing functions and as well promoting efficiency, decreasing memory is what i need.
Thanks for reading!
