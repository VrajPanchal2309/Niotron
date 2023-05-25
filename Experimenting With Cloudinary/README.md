<div class="cooked"><p>So this topic is quite interesting , you have to post the ways / possibilities  to edit Cloudinary images , video etc. <a href="https://cloudinary.com/console/transformations" rel="noopener nofollow ugc">Cloudinary Cookbook</a> helps you to edit.</p>
<p>Eg :-</p>
<details>
<summary>
1) Height , Width , Gravity of image</summary>
<p><img src="https://community.niotron.com/uploads/default/original/2X/6/68bb56edc128fa77c2b65d7e2d3fd62493a03b32.png" alt="image" data-base62-sha1="eWv1RGk7lXbYr7dDrRHWpQm2zYe" style="aspect-ratio: 150 / 300;" loading="lazy" width="150" height="300"></p>
<pre class="codeblock-buttons"><div class="codeblock-button-wrapper" style="right: 0px;"><button class="btn nohighlight copy-cmd"><svg class="fa d-icon d-icon-copy svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use href="#copy"></use></svg></button></div><code class="lang-auto">https://res.cloudinary.com/demo/image/upload/w_500,h_150,c_fill,g_south/boulder.jpg
</code></pre>
<p>Here <strong><code>w_150</code></strong> allows to to set width of image. eg <code>w_300</code></p>
<p>sameway <strong>h_300</strong> allows to set height of image. ex <code>h_150</code></p>
<p>sameway <strong>g_south</strong> allows to set gravity of image. ex <code>g_north</code></p>
<p>sameway <strong>c_fill</strong> allows to set canter filled image.</p>
</details>
<details>
<summary>
2) End offset, Gravity, Radius, Quality, Audio codec of video</summary>
<p></p>
<div class="video-container">
    <video preload="metadata" controls="" width="100%" height="100%">
      <source src="/uploads/default/original/2X/3/3daaba71d419fa1211da4c376b7fd2b10baf4c48.mp4">
      <a href="https://community.niotron.com/uploads/default/original/2X/3/3daaba71d419fa1211da4c376b7fd2b10baf4c48.mp4">/uploads/default/original/2X/3/3daaba71d419fa1211da4c376b7fd2b10baf4c48.mp4</a>
    </video>
  </div>
<p></p>
<pre class="codeblock-buttons"><div class="codeblock-button-wrapper" style="right: 0px;"><button class="btn nohighlight copy-cmd"><svg class="fa d-icon d-icon-copy svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use href="#copy"></use></svg></button></div><code class="lang-auto">https://res.cloudinary.com/yakir/video/upload/g_auto/eo_7/w_250,h_250,c_fill,r_max/q_auto:eco/ac_none/video/user_video.mp4
</code></pre>
<p><code>end_offset</code> (<code>eo</code> in URLs) - To specify the end of the video.</p>
<p><code>gravity</code> (<code>g_auto</code> in URLs) - To keep the main subject (the face) in view at all times, even as it moves across the frame in the original video.</p>
<p><code>radius</code> (<code>r</code> in URLs) - To make the video look like a headshot profile image.</p>
<p><code>quality</code> (<code>q_auto</code> in URLs) - In order to perform automatic quality encoding.</p>
<p><code>audio_codec</code> (<code>ac</code> in URLs) - To control the audio codec or remove the audio channel.</p>
</details>
<details>
<summary>
3) Video Profile View</summary>
<p></p>
<div class="video-container">
    <video preload="metadata" controls="" width="100%" height="100%">
      <source src="/uploads/default/original/2X/8/8eeae6c47bea393af58b256dc00ad75b76aa294b.mp4">
      <a href="https://community.niotron.com/uploads/default/original/2X/8/8eeae6c47bea393af58b256dc00ad75b76aa294b.mp4">/uploads/default/original/2X/8/8eeae6c47bea393af58b256dc00ad75b76aa294b.mp4</a>
    </video>
  </div>
<p></p>
<pre class="codeblock-buttons"><div class="codeblock-button-wrapper" style="right: 0px;"><button class="btn nohighlight copy-cmd"><svg class="fa d-icon d-icon-copy svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use href="#copy"></use></svg></button></div><code class="lang-auto">https://res.cloudinary.com/demo/video/upload/g_auto/eo_7/w_250,h_250,c_fill,r_max/q_auto:eco/v1603292662/user_video.mp4
</code></pre>
<p><code>end_offset</code> (<code>eo</code> in URLs) - To specify the end of the video.</p>
<p><code>gravity</code> (<code>g_auto</code> in URLs) - To keep the main subject (the face) in view at all times, even as it moves across the frame in the original video.</p>
<p><code>radius</code> (<code>r</code> in URLs) - To make the video look like a headshot profile image.</p>
<p><code>quality</code> (<code>q_auto</code> in URLs) - In order to perform automatic quality encoding.</p>
<p><code>audio_codec</code> (<code>ac</code> in URLs) - To control the audio codec or remove the audio channel.</p>
</details>
<details>
<summary>
3) Rounded profile picture with initials</summary>
<p><img src="https://community.niotron.com/uploads/default/original/2X/d/d7b5ad4abca59e9d212c8c9ad8920138ef360afa.png" alt="image" data-base62-sha1="uMfTCFoDUMD8BcDd8iZORfWT4zE" style="aspect-ratio: 100 / 100;" loading="lazy" width="100" height="100"></p>
<pre class="codeblock-buttons"><div class="codeblock-button-wrapper" style="right: 0px;"><button class="btn nohighlight copy-cmd"><svg class="fa d-icon d-icon-copy svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use href="#copy"></use></svg></button></div><code class="lang-auto">https://res.cloudinary.com/demo/image/facebook/w_100,h_100,c_thumb,g_face,e_blur:200,r_max/Beckham.jpg
</code></pre>
</details>
<details>
<summary>
4) Generate your photo collage online</summary>
<details>
<summary>
Type 1</summary>
<p><img src="https://community.niotron.com/uploads/default/original/2X/2/267593de997bff861d9b87b756a8606b191fe97b.jpeg" alt="image" data-base62-sha1="5ue3gNgJtSw5v4xKqfAjCT4OBp9" style="aspect-ratio: 408 / 312;" loading="lazy" width="408" height="312"></p>
<pre class="codeblock-buttons"><div class="codeblock-button-wrapper" style="right: 0px;"><button class="btn nohighlight copy-cmd"><svg class="fa d-icon d-icon-copy svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use href="#copy"></use></svg></button></div><code class="lang-auto">https://res.cloudinary.com/demo/image/upload/w_220,h_140,c_fill/l_brown_sheep,w_220,h_140,c_fill,x_220/l_horses,w_220,h_140,c_fill,y_140,x_-110/l_white_chicken,w_220,h_140,c_fill,y_70,x_110/l_butterfly.png,h_200,x_-10,a_10/w_400,h_260,c_crop,r_20/l_text:Parisienne_35_bold:Memories%20from%20our%20trip,co_rgb:990C47,y_155/e_shadow/yellow_tulip.jpg
</code></pre>
</details>
<details>
<summary>
Type 2</summary>
<p><img src="https://community.niotron.com/uploads/default/original/2X/d/dd6ce66f1cebb5f347da7e2c105a4f07f86843be.jpeg" alt="image" data-base62-sha1="vAOPYUSndXrk3wkxKGJPmaPShSC" style="aspect-ratio: 208 / 208;" loading="lazy" width="208" height="208"></p>
<pre class="codeblock-buttons"><div class="codeblock-button-wrapper" style="right: 0px;"><button class="btn nohighlight copy-cmd"><svg class="fa d-icon d-icon-copy svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use href="#copy"></use></svg></button></div><code class="lang-auto">https://res.cloudinary.com/demo/image/upload/w_100,h_100,c_fill/l_sample,w_100,h_100,c_fill,x_100/l_kitten,w_100,h_100,c_fill,y_100,x_-50/l_autumn_leaves,w_100,h_100,c_fill,y_50,x_50/r_max/e_shadow/fat_cat.jpg
</code></pre>
</details>
</details>
<details>
<summary>
5) Convert image to grayscale</summary>
<p><img src="https://community.niotron.com/uploads/default/original/2X/f/f6aa71b27b7f0e6ff92a064727e10f9dddf3e06b.jpeg" alt="image" data-base62-sha1="zc6DdGTo8TacDM0qvWFuyDp90Hp" style="aspect-ratio: 200 / 286;" loading="lazy" width="200" height="286"></p>
<pre class="codeblock-buttons"><div class="codeblock-button-wrapper" style="right: 0px;"><button class="btn nohighlight copy-cmd"><svg class="fa d-icon d-icon-copy svg-icon svg-string" xmlns="http://www.w3.org/2000/svg"><use href="#copy"></use></svg></button></div><code class="lang-auto">https://res.cloudinary.com/demo/image/upload/e_gradient_fade,x_0.9/u_happy_dog,e_grayscale/happy_dog.jpg
</code></pre>
</details>
<p>So this are some of the examples, challenge is to post all the formats as much as you can <img src="https://community.niotron.com/images/emoji/twitter/grinning.png?v=12" title=":grinning:" class="emoji" alt=":grinning:" loading="lazy" style="aspect-ratio: 20 / 20;" width="20" height="20"></p>
<p><strong>Note :- You can create your own formats too using <a href="https://cloudinary.com/console/c-f9b0d85ccd460781893ac0846773e0/transformation_editor?createNewTransformation=true" rel="noopener nofollow ugc">Cloudinary Media Transformation <span class="badge badge-notification clicks" title="1 click">1</span></a></strong></p></div>
