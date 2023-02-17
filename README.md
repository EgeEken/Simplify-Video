# Simplify-Video
The video version of my Simplify program.

I had the idea of making this for a long time since it's only the natural progression of the original program but what really made me finally do it was that i needed a way to turn frames of videos into simplified versions for easier AI training, and then i realised "oh wait i literally already have a program that does this"

UPDATE: Decided to release this as part of the [ImageProcessing_Ege library](https://github.com/EgeEken/ImageProcessing_Ege) instead of a seperate program just for itself. The library includes updated and improved versions of all my image processing projects as well as some other useful functions. Unfortunately, what was a relatively small time loss on single images quickly becomes a major issue when you apply it to hundreds of frames in a video, as well as having to account for the time to process the video itself, so this program is practically unusable for anything. 

<details><summary>Results: (click here to open)</summary>
<p>

https://user-images.githubusercontent.com/96302110/219777169-1e0886b1-8798-4a9f-ae56-e73374245a9d.mp4

https://user-images.githubusercontent.com/96302110/219777411-b4f4500c-7b06-471e-ada9-8f7428c0c719.mp4

Just to illustrate how slow this program is, this 3 second long 180p video took a full minute to process and return a result on my computer 

</p>
</details>
