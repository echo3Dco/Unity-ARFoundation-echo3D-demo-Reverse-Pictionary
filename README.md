# Unity-ARFoundation-echo3D-demo-Reverse-Pictionary
An AR Reverse Pictionary app demo built with echo3D.

## Game loop
The display tells you what to draw (for example, "Draw a boat!" and a time counter ticking down from 20 seconds starts.  
The controls to move the pen are the four buttons on your screen, which are to turn left/right and move forward/back. You should see a black line be drawn as you move forward/back. 
When the time runs out, the board will clear, and you will be given a new item/goal to draw, and the timer will be reset. Hand the device to the next person, and good luck to them as they try to draw the object before the time runs out!

## Changing the metadata in echo3D
You can add or delete the "drawing goals" and their time (in seconds) in the metadata for the notepad object.
To do so, simply add an entry with the key being the drawing goal (e.g., "house"), and its value being the time allocated to draw it before the timer runs out (e.g., "20"). 

## Register
If you don't have an echo3D API key yet, make sure to register for FREE at [echo3D](https://console.echo3D.co/#/auth/register).

## Setup
* [Add the 3D model](https://docs.echo3D.co/quickstart/add-a-3d-model) from the [models](./Models) folder to the console.
* [Add the metadata](https://docs.echo3D.co/web-console/manage-pages/data-page/how-to-add-data#adding-metadata) found in the [metadata](./metadata) folder.

## Run
* [Build and run the AR application](https://docs.echo3D.co/unity/adding-ar-capabilities#4-build-and-run-the-ar-application).

## Real-time updates
Add/remove/edit models in the console and notice that the interactive models in the AR scene changes automatically.

## Learn more
Refer to our [documentation](https://docs.echo3D.co/unity/) to learn more about how to use Unity, AR Foundation, and echo3D.

## Support
Feel free to reach out at [support@echo3D.co](mailto:support@echo3D.co) or join our [support channel on Slack](https://go.echo3D.co/join). 

## Screenshots
<img src="/Screenshots/Screenshot-one.jpg" width="450">
<img src="/Screenshots/Screenshot-two.jpg" width="450">
<img src="/Screenshots/console.png">
<img src="/Screenshots/metadata.png">
