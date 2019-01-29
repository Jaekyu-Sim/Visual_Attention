# Visual Attention driven by Convolutional Features
---------------------------------------------------------------------------

When we see a scene, we do not see all of the scene. We just see what we interesing(Attention is here).

And, We can do many things by these attention(could reduce error, could save image process time because we don't have to see every of the scene).

For example..
when we see such a picture.

![input_img1](/images/1/input_img.png)
![input_img2](/images/2/input_img.png)
![input_img3](/images/3/input_img.png)
![input_img4](/images/4/img_input.png)
![input_img5](/images/5/img_input.png)


We don't see all of the picture. we just have attention what we interesting.
For these reasons, I read paper <Visual Attention driven by Convolutional Features>, and made network for visual attention.
The output is here.
  
![network_output1](/images/1/network_output.png)
![network_output2](/images/2/network_output.png)
![network_output3](/images/3/network_output.png)
![network_output4](/images/4/network_output.png)
![network_output5](/images/5/network_output.png)
  
  

And, We can use this output for attention like this.(channel-wise convolution or element-wise convolution).

![channel_wise_convolution1](/images/1/channel_wise_convolution.png)
![channel_wise_convolution2](/images/2/channel_wise_convolution.png)
![channel_wise_convolution3](/images/3/channel_wise_convolution.png)
![channel_wise_convolution4](/images/4/channel_wise_convolution.png)
![channel_wise_convolution5](/images/5/channel_wise_convolution.png)








