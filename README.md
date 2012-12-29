Spacing
=======

CSS to make life easiar by spacing things out. 
Use Spacing and avoid the trouble of having to go back and forth to your CSS file to space out objects in different directions.
With Spacing, you just import the file into your HTML document and you are ready to go!

How to use on an element:    <div class="spaceleft">Hello </div>

Doing this will move the words hello to the left 20px from its original position. Its very simple.
Spacing has spaceleft, spaceright, spacetop, and spacebottom. Each has a level of space, for example, if you want more space
on the Hello text, you simple add a 2 on 'spaceleft'. This would increase the amount of space to +20px.
The numbers go all the way up to 10. After 5, the spacing begins to increase by +50px.

Examples:  <div class="spaceleft4">Hello </div>     // Left space 20px.
           <div class="spacetop6">Hello </div>     // Left space 150px.

There is also space mini and space-x. Space mini provides a little smaller space, and space-x provides a very large space.
To use simple add mini in front of the space direction (BUT dont include a number)!

Ex: <div class="spaceright-mini">Hello </div>     // Right space mini.
    <div class="spaceright-x">Hello </div>     // Large Right Space.

It might sound like a stupid useless idea, you can probably make your own, but, It could prove worthy.

Some boring legal stuff:

Unless otherwise specified, all content, including all source code files and documentation files in this repository are:

Copyright (c) 2012 Gabriel Rosa.

Unless otherwise specified or set forth in the NOTICE file, all content, including all source code files and documentation files in this repository are: Licensed under the MIT License,  (the "License"); you may not use this content except in compliance with the License. You may obtain a copy of the License at

http://opensource.org/licenses/MIT

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
