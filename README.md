## Find the Missing Pet

### Instructions

<img src="http://www.blogcdn.com/blog.moviefone.com/media/2010/11/misterbisson.jpg" alt="Missing pet" height="200" align="right" hspace="20"> 

You just began your job as Web Developer at the Animal Sanctuary, and they aren't very good at organizing the photos of their favorite alumni animals. Somehow all photos ended up in the wrong folders! It's your job to move through their directory structure and put the animals in their right place. The photos have been named really well, so figuring out their correct location shouldn't be too tricky.

Because you're a legit programmer, you know the most efficient way is to navigate the directories in the command line. Use your bash command line skills to move the photos into their correct folders!

As a refresher, here's a list of commands to help you with this task:

`pwd` print working directory - shows you where yrs
```

BUT WOW that's a lot of steps. Programming is all about making things simple, so there has to be a better way. In fact, we can actually combine all the steps into one short line:

```bash
mv cats/indoor/back-alley/painting-elephants.jpg elephants/painters
```

For this, we're using `relative paths`. We're inside of the "lab root" directory, and we're not going to use `cd` to move ourselves anywhere.Because `painting-elephants.jpg` doesn't exist inside the "lab root" directory, we have to tell the computer follow path to go to find that image, which is through the `cats` directory, and then `indoor` and then finally `back-alley`.

Next, we have to tell the computer where to move the image. Because we're inside lab root and so is the `elephants` directory, we can just go straight there, and then into `painters`.

<p data-visibility='hidden'>KWK-L1 Find the Missing Pet</p>