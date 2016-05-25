# Unity-WebVR-Template
Built by the <a href="http://boondogl.com/">Boondogl</a> team - if you have a great WebVR game you'd like to bring to Boondogl, contact us!

To get up and running in WebVR, follow these steps:
<ul>
<li>Get your hands on an Oculus Rift DK2 or CV1, and install <a href="https://www.oculus.com/en-us/setup/">Oculus Runtime 1.3.2</a> 
<li>Download and install <a href="https://nightly.mozilla.org/">Firefox Nightly</a> or a <a href="https://drive.google.com/folderview?id=0BzudLt22BqGRbW9WTHMtOWMzNjQ">Chromium WebVR Build</a>
<li>Follow <a href="http://mozvr.com/#start">these instructions</a> to enable WebVR in Nightly, or follow the readme instructions on the Chromium page.
<li>Grab either the entire sample project or just the UnityPackage from this repo
<li>Open Unity (either the sample project or your own project with the UnityPackage added) and replace your MainCamera with the WebVRCameraSet prefab
<li>Make sure StereoCamera.cs is attached to the parent node of the prefab
<li>Go to File > Build Settings and change your Platform to WebGL - Leave Development Build unchecked
<li>Go to Edit > Project Settings > Player, then under the Resolution and Presentation section, select WebVR as your WebGL template
<li>In the same Project Settings under Publishing Settings section, make sure your WebGL Memory Size is set to a minimum of 768MB to avoid out of memory errors
<li>Depending on the complexity of your game, you may want to set it to 1024MB. This causes an array allocation error in the current Chromium build, but is fine in Firefox for more complex games
<li>Build to WebGL and give it a shot in Firefox Nightly or Chromium! 
</ul>

**This template was created using an original code drop from GitHub user gtk2k. You can find the original project, with updates from the Mozilla team to bring it up to WebVR 1.0 standards, here: https://github.com/gtk2k/Unity-WebVR-Assets**
