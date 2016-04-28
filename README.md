# Unity-WebVR-Template
Built by the <a href="http://boondogl.com/">Boondogl</a> team - if you have a great WebVR game you'd like to bring to Boondogl, contact us!

To get up and running in WebVR, follow these steps:
<ul>
<li>Get your hands on an Oculus Rift DK2, and install <a href="https://developer.oculus.com/downloads/pc/0.8.0.0-beta/Oculus_Runtime_for_Windows/">Oculus Runtime 0.8</a> (newer versions won’t work yet)
<li>Download and install <a href="https://nightly.mozilla.org/">Firefox Nightly</a>
<li>Follow <a href="http://mozvr.com/#start">these instructions</a> to enable WebVR in Nightly
<li>Grab either the entire sample project or just the UnityPackage from this repo
<li>Open Unity (either the sample project or your own project with the UnityPackage added) and replace your MainCamera with the WebVRCameraSet prefab
<li>Make sure StereoCamera.cs is attached to the parent node of the prefab
<li>Go to File > Build Settings and change your Platform to WebGL - Leave Development Build unchecked
<li>Go to Edit > Project Settings > Player, then under the Resolution and Presentation section, select WebVR as your WebGL template
<li>In the same Project Settings under Publishing Settings section, make sure your WebGL Memory Size is set to a minimum of 512MB to avoid out of memory errors
<li>Depending on the complexity of your game, you may want to set it to 1024MB
<li>Build to WebGL and give it a shot in Firefox Nightly! 
</ul>
