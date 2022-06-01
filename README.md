# ImageWatermarking
mage Watermarking application I made in Image Processing class

Watermark

• Watermark, also known as 'watermark', by definition, is the name given to a transparent stamp, text, signature or logo added to an image.

•Digital watermarking is the latest form of watermarking. Similar to physical watermarks on paper, digital watermarks are used to identify the owner/creator and authenticate digital media such as images, audio and video.

Why Watermark?

When Photos/Videos go viral, they fly so unwatchable from all directions. Often times, owner/creator information is lost or forgotten.

Avoid the surprise of seeing your photos, images or videos used by others on physical products, advertisements and/or the web.

Avoid intellectual property (IP) conflicts, costly lawsuits, and headaches from plagiarists who claim they didn't know you created them by adding visible and/or invisible watermarks.

Because the widespread use of social media has increased the speed at which a photo / video goes viral.



![image](https://user-images.githubusercontent.com/105684427/171412781-5cd1d392-26d7-48f5-8dd6-80454f097ed0.png)


With DWT (Discrete Wavelet Transform), gray-level image watermarking method is done. This stigma
The stamps to be added in the method are divided into four equal parts. The durability of the stamping method against attacks
Each of these parts is four separate pieces obtained as a result of DWT processing of the images to be stamped.
hidden in different sub-regions of the bands.
These bands are:
              LL1: Approximate Image Band
              HL1: Horizontal Detail Tape
              LH1: Vertical Detail Tape
              HH1: Diagonal Detail Tape

[Uy, Sy,Vy]=svd(LL2);
In the code, since LL2 is a non-invertible matrix, it is inverted by decomposition.
Smark = this.Sy + Alpha*Sw; this process embeds the watermark.
Alpha is our burial force.

