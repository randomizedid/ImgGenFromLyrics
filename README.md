I used the code gently uploaded by Aleksa Gordic and added a script to generate images for every line of text found in a text file.
If you want to generate images from lyrics of a song, just copy the lyrics in a text file and the code will generate one image
for every line found in the text using the stable diffusion code.

For people only interested in image generation from lyrics: crucial things of the code are prompt and seed. 

The prompt is the text that the algorithm reads (i.e., the line), so make sure the text is formatted correctly, every sentence to be
used has to lay on a single line. 
To change text input, just change the title in line 4 adequately.

The second important thing is the seed, an integer used to generate different images (by giving same text and different seeds you
will obtain different images), have fun experimenting with it! (right now the code assigns a random seed to every different line.

Have fun with the algorithm, and let's all thank the open-source community for it!