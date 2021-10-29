 # CS+ART
 
 For my Cinema & Media Arts Senior Seminar final project I decided to blend together my love of film and computer science to create something organic yet artificial and overall extremely expressive. 
 
 The video is hosted here: https://www.youtube.com/watch?v=sdV1Cx7J7E4
 
 I created an entropy animation algorithm (AbstractManipulation) using Python which would cause the pixels to randomly swap with their neighbors. However, this swapping was not truly random as the pixels, depending on their primary color, were biased toward different areas of the screen. After the swapping was applied, the algorithm would write these changes to a file, open said file, and repeat the process again.  The algorithm iteratively causes the image to slowly self-destruct in an almost living way. 
 
 I designed an algorithm to create all possible RGB swap permutations (RGBColorSwap)--useful for segmenting the screen into different views. 
 
 I implemented another entropy animation algorithm (StaticNoise) which created a localized static which did not grow. This is useful for animating words to "shake with anger".
