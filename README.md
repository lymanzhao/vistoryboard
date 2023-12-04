# Python Extension Example [omni.kit.storyboard.7DVision]



# Tell Captivating Stories with Generative AI

ViStoryboard is a creative tool that is developed using our proprietary generative AI technology. By converting scripts and other text descriptions into visual storyboards, ViStoryboard can help you to convey your story ideas with freedom and ease.  

ViStoryboard can generates storyboards that are compatible with timeline sequences and project files. This feature is highly convenient for the post-production department to work with the content.

With ViStoryboard, you can just simply input your script or outline, and our AI model will analyze the full text and automatically generate a visualizable storyboard with panel by panel.

This tool unleashes your creativity to tell compelling stories with the power of AI.



## Product advantages:

- No drawing skills required, just simple prompt words to get professional-grade storyboards.
- Custom model specially trained for storyboarding. Weightage adjustments are available to make the final images fit with your creative vision.  

- Works well with various Stable Diffusion XL refinement models.

- Model has been tuned to generate storyboards using well-established painting techniques. There are no infringement concerns.
- ViStoryboard reduces the barriers to the process of creating storyboards, no matter if you are an assistant, editor, or photographer.
- Base on Stable Diffusion XL model with 2.6B parameters. Provides excellent natural language processing ability to understand scripts and localized elements.




### Rapid iteration

Generate images in batches with varied scenes and angles to explore additional possibilities.



### Costs and time saving  

More manageable timeline in comparison to traditional storyboarding.



### Made for professionals

Seamlessly integrate into your workflow by generating timeline format files that can be imported into Adobe Premiere, DaVinci Resolve, and other video and audio editing software.



### Nvidia Omniverse extension integration

An Nvidia Omniverse Extension App is available, offering partners of the Omniverse Ecosystem a visualization tool for pre-production scripts.



# Get started

## Add extension to Omniverse

1. **[Open extension manager]** After opening Omniverse Code, go to `Menu` -> `Window` -> `Extension`
2. **[Add this extension to Omniverse]** Click the Extension Serch Path Setting button and add absolute extension path to `Extension Search Paths`


![image](README.assets\01.png)

Finally, you can search vistoryboard and enable this extension.


## Usage

![image](README.assets\02.png)

1.load or new project.

2.logine or register user.

3.Enter the required prompt in the textbox,such as:

a cat on table.

onclick "Genereate" button, please wait.

4.You can modify the duration of the picture you want to play in the list, seconds


![image](README.assets\03.png)





5.You can load the USD scene we made and use it. Load Sample Scene in the menu in the upper right corner and it will be loaded automatically.

![image](README.assets\05.png)

Display a theater scene in the viewport:

![image](README.assets\06.png)



6.Select the picture you want, click the ToViewport button in the lower right corner and create USD, switch to Viewport window and Top view, call up the timeline window to play.

![image](README.assets\04.png)

You can also select the Mesh in the scene and assign the picture to be played as a texture to the mesh, such as a movie curtain or a TV set in the scene.

![image](README.assets\06.png)

![image](README.assets\07.png)

[^]: The problem found is that sometimes there is a delay. The USDtoViewport button is delayed. You can wait or click more.
[^]: Modify the specular attribute of the material and reduce it to 0

![image](README.assets\08.png)




5. The Save as mp4 File button will generate mp4 video files to the omni.kit.storyboard.7DVision\resources\asset folder, Pay attention to setting the timerange of Movie Capture.


## Parameter

  Prompt: Shot content, using Stable diffusion XL style prompt words.
  Prompt: Troubleshoot incorrect picture content or picture quality.
  Width: image width, 1024 pixels or so.
  Height: image height, 1024 pixels or so.
  Sampler: Different Samplers have different sensitivities to prompt words.
  Weight： the artistic weight of Storyboard art style, default 0.8,0 means none, 1.8 means very heavy.
  Count： the number of images generated in batches at one time.
  Seed： random value, default -1 is a random number.
  Step： the number of sampling steps, higher numbers may have more real details.



