# Visual Attention driven by Convolutional Features
---------------------------------------------------------------------------

When we see a scene, we do not see all of the scene. We just see what we interesing(Attention is here).

And, We can do many things by these attention(could reduce error, could save image process time because we don't have to see every of the scene).

For example..
when we see such a picture
![input_img]



We don't see all of the picture. we just have attention what we interesting.
For these reasons, I read paper <Visual Attention driven by Convolutional Features>, and made network for visual attention.
The output is here.
![network_output]
  
  

And, We can use this output for attention like this.(channel-wise convolution or element-wise convolution)
![channel_wise_convolution]








