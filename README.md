# Transfer-Learining-from-EMNIST-to-Quickdraw
Quickdraw is a Google's database that contains simple drawings and it's shared publicly. 
5 to 10 of the many categories they have were taken: apple, smiley face, rabbit, bed, sun, pencil, book, bus, cell phone, moustache and pencil. <br/>
Previously, a CNN with the EMNISTdatabasewas trained, as seen in other repositories and then, as before, the weights of the firsts layers (convolutional) were frozen. The accuracy obtained in the test set was **97.38%**, so the transfer learning was successful. :+1: 
<br/>
The figures below show the improvement in the accuracy when the set of images availables is limited in number. 
<img height=400 src="https://github.com/camilo1704/Transfer-Learining-from-EMNIST-to-Quickdraw/blob/master/Figure_1.png" />
<img height=400 src="https://github.com/camilo1704/Transfer-Learining-from-EMNIST-to-Quickdraw/blob/master/Figure_2.png" />

