# NeuralStyleTransfer

Team Filtered Play: Anya Osborne, Cassandra Ravenbrook, Kyle Gonzalez

Based on the tutorial by Alexis Jacq (https://pytorch.org/tutorials/advanced/neural_style_tutorial.html) of "A Neural Algorithm of Artistic Style" by Gatys et al. (https://arxiv.org/abs/1508.06576)

Requires the packages:
- torch, torch.nn, numpy
- torch.optim
- PIL, PIL.Image, matplotlib.pyplot
- torchvision.transforms
- torchvision.models
- torchvision.utils
- copy

Run with a content image named "content.jpg" and a style image named "style.jpg" that are both the same dimensions. The output image will be produced based on the form of the content image and the colors/shapes of the style image. For good output that presents a clearly transferred style, try style images with striking lines and colors or a notable pattern or process.

<p aling="center"><img alt="Beyond Two Souls" src="http://kylegonzalez.com/FilteredPlay/image1.gif" width="500" height="500"></p>
<p aling="center"><img alt="Beyond Two Souls with Lissitzky style" src="http://kylegonzalez.com/FilteredPlay/constructivist.gif" width="500" height="500"></p>
<p aling="center"><img alt="Beyond Two Souls with Duchamp style" src="http://kylegonzalez.com/FilteredPlay/duchamp.gif" width="500" height="500"></p>
