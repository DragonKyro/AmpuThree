# AmpuThree

<p>A cheap prosthetic targeted towards wounded veterans, AmpuThree (it has three motors!) is effective and light. </p>
<div style="text-align: center;"><IMG SRC="https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/000/563/055/datas/gallery.jpg" ALT="image"></div>
<div style="text-align: center;"><IMG SRC="https://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/000/563/053/datas/gallery.jpg" ALT="image"></div>
<h3>Features</h3>

<p>AmpuThree allows wounded veterans to take control of their life with its response technology. The Myo armband tracks the movement of the right arm and uses this data to control the behavior of the mechanical left arm. Amputee veterans are a big problem in the US. According to the National Center for Veteran Statistics, over 1000 veterans are now amputees due to Iraq and Afghanistan alone. These brave men have risked their lives for their journey and many are without prostheses: in fact, many just abandon the devices, which cost over $100000! Several practical examples of everyday tasks have been implemented using the AmpuThree. </p>

<p>For example, the AmpuThree can be used to pick up boxes. Bulky boxes cannot be picked up with one hand but when the AmpuThree senses the right hand go into position to pick up a box, it will move the left hand to aid in picking up the box as well. </p>

<p>The AmpuThree is also used in order to open water bottles-- when the right hand closes into a fist, the left hand also closes into a fist. This allows the prosthetic hand to grasp onto the water bottle while using the right hand to unscrew the cap. This is not only useful for unscrewing water bottles, but also other containers.</p>

<p>The AmpuThree also boasts rotatable joints at both the elbow and wrist joints. Motors power these joint rotations for quick and responsive reactions to the movements of the right arm. The left arm will always mirror the movements of the right arm so the user can have an intuitive experience adapting to it. </p>

<p>Plus, it's purple! We all love purple!</p>

<h3>How we built it</h3>

<p>The AmpuThree was difficult to build. We started by brainstorming ideas. Our decision to build the AmpuThree was made after we made a decision matrix and eliminated the other ideas we came up with. </p>

<p>After we decided to build a prosthetic limb, we had to decide what aspects of the limb we would focus on. We decided to stress the economic and efficiency aspects for this, as many people can not afford prostheses, especially wounded veterans. To this end, we decided to try to use low-cost materials and began to design our prosthesis. Several sketches were made in order to get ideas flowing. In the end we selected the below drawing as the best.</p>

<p>This drawing was quite close to the final design. We made only one significant change (changing the stick in the middle to a water bottle in order to decrease costs even more while decreasing the weight and maintaining similar strength). This meant that it would not only be cheaper but also easier to assemble. </p>

<p>We began building the final design as soon as we all agreed upon it, knowing we would be on a time crunch. Each member took a different part of the build. First the 3-D parts for the hand part of the arm had to be printed. The files were painstakingly designed-- each had to be perfectly aligned or the hand would not fit together. We had to print it twice since the first one was not precise enough. After this the </p>

<h3>Challenges we ran into</h3>

<p>The biggest challenge we ran into was the actual assembly of the hardware, as with so many hardware hacks. We ran into many small bugs that were easily solved but we did have one very big challenge. This was that after we successfully assembled and tested the entire AmpuThree. We quickly discovered that some of the soldering connections were loose because the soldering was badly done in a few places. This caused a lot of time to be wasted on troubleshooting-- for example, some of the soldering connections worked only some of the time so the multimeter gave varied readings. It was very difficult to figure out which soldering connections were broken. It was even more difficult to fix them-- we had to go back and resolder many of the connections. Many of the connections nearly burned out but luckily after a few hours all the connections were working correctly. However, we then discovered that some of the wires were broken as well. We had to get new wires while some of our team members worked on the software in order to make the deadline. The MPU6050 (a 9 degree of freedom sensor with a MEMS accelerometer and a MEMS gyro) also presented itself as a problem. Although it was very well-made and very easy to move around with its 9 degrees of freedom, it was difficult to position completely accurately due to the fact that we had to do a lot of complicated trigonometry in order to discover the correct angular offsets for each of the different functions of the AmpuThree. Every function of the AmpuThree had different angular offsets and needed different calculations. We had to carefully check to make sure each calculation was correct-- small errors would cause the entire AmpuTHree to be very far off from the target positions. All these problems took us a lot of collective time to fix and we finished with little time to spare. </p>

<p>The jumper wires were not very sturdy. This meant they had to be replaced every so often until we had an array of all completely stable wires. </p>

<p>The 3D printing also produced a lot of problems. </p>

<p>We had some more trouble with troubleshooting the software as well. The Arduino library we used, MyoDuino, came with a exe binary interface to allow easier troubleshooting while coding. We did not have many problems while coding, although at the end we ran into a few issues with noise. We had to implement a Kalman filter in order to cancel out some of the noise while testing our program. This implementation took a bit of time because we had to edit the filter in order to fit our needs. Eventually we were able to implement the filter successfully and prevent noise from corrupting our data, allowing the arm to move more accurately and stay calibrated throughout the entire user session.</p>

<h3>Accomplishments that we're proud of</h3>

<p>We were mostly just proud of finishing our project! It was very ambitious and we did not think we would be able to finish. Thankfully we did! We were especially proud of our troubleshooting skills. It was nice that we were able to successfully solve all the problems that first manifested in our initial test run. I would give specific examples, but everything was just so great! The hardware and software were both impressive-- we got to use 3D printing, circuits, and software code! It was lots of fun and very beneficial to us!</p>

<h3>What we learned</h3>

<p>We learned a lot about hardware. Our 3D printing skills definitely increased a lot. We also learned about the MyoDuino library and its applications. We had to adapt it for our project and it taught us about adapting code for our own use! Overall the project was very educational and entertaining!</p>

<h3>What's next for AmpuThree</h3>

<p>We might make the AmpuThree have more user configured options. As of now the AmpuThree only mirrors the movements of the right arm. However, we could change it so the left arm responds to the right arm based on preferences set by the user-- for example, the user might tap twice with his or her right hand to get the AmpuThree to reach behind him or her to reach an object. We could also make it with a sturdier but less dense material and with a stronger motor to allow heavier materials to be picked up. AmpuThree has a bright future ahead of it!</p>

</div>
