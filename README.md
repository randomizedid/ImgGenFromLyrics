Hi all!

With the new explosion of open-source stable diffusion algorithms, I was curious to try something myself! 
I followed Aleksa Gordic, a research engineer at DeepMind, and learned a lot of things! 

Aleksa's Youtube channel:

https://www.youtube.com/c/TheAIEpiphany

For now, most of the code you'll find here comes from his repository, so make sure to check it out!

https://github.com/gordicaleksa/stable_diffusion_playground

I added a small script that allows to use the stable diffusion code to generate images from the lyrics of a song

If you want to generate images from lyrics of a song, just copy the lyrics in a text file and the code will generate one image
for every line found in the text using the stable diffusion code.

For people only interested in image generation from lyrics: crucial things of the code are prompt and seed. 

The prompt is the text that the algorithm reads (i.e., the line), so make sure the text is formatted correctly, every sentence to be
used has to lay on a single line. 
To change text input, just change the title in line 4 adequately.

The second important thing is the seed, an integer used to generate different images (by giving same text and different seeds you
will obtain different images), have fun experimenting with it! (right now the code assigns a random seed to every different line.

For people also interested in stable diffusion and other uses, check Aleksa's resources and the other README file.

Have fun with the algorithm, and let's all thank the open-source community for it!