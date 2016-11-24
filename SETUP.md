# You're nearly done.

If you came to this page already - you now have the `silex-boilerplate` for [storyblok](https://storyblok.com) up and running on your system - or opened the `SETUP.md` in your editor. All what's now left for you - if you didn't open it in your editor - is to create your space & a story. Let me guide you through this.

# 1. Creating the space

### Creating a new space
By pressing the *new* button on the upper right corner of the [storyblok](https://storyblok.com) dashboard you can easily create a new space.
![Creating a new space](//a.storyblok.com/f/125362e8dc/newspace.jpg)

### Uncheck *start with a boilerplate*
This will allow you to create a space from scratch without the components from the [starter-template](https://github.com/storyblok/starter-template).
![Uncheck start with boilerplate](//a.storyblok.com/f/108b582e1e/uncheck-start-with-boilerplate.jpg)

###  Add a space title 
Add a space title so you can find it later in the dashboard/sidebar by your name.
![Add space title](//a.storyblok.com/f/6222641b52/add-space-title.jpg)

### Finally creating the space
After adding a *title* and unchecking the *start with a boilerplate* checkbox just click the *save* button.
![press the save button](//a.storyblok.com/f/5951362e56/create-space.jpg)

### Edit space
Directly after creating the space we're going to configurate it by pressing the *edit* button.
![edit space](//a.storyblok.com/f/81c75bfdf1/edit-space.jpg)

### Configure
For the `silex-boilerplate` the default location (domain) on your local maschine will be `http://localhost:4040/`. To configurate the `silex-boilerplate` client with the *private token* you can create one using the dropdown in the *access tokens* area. If you feel like you also need the *space id* here is also the place where you can find it.
![configure](//a.storyblok.com/f/b83fb5c018/configure.jpg)

# 2. Creating your first story
### Creating a new story
After you're done setting up your space you can now press the *new story* button in the upper right corner - if it's not there you need to select your space in the left sidebar.
![add a new story](//a.storyblok.com/f/5d09fd048a/creating-a-new-story.jpg)

### Adding a name & a slug
Configure the story by giving it a *name* and a *slug*. The *name* will be used in storyblok and also will be send as the `name` property in the story json. The *slug* on the other hand will be the identifier for the API - so you can load the story. This *slug* will also be the one string you will have to add in your `config.php` to define the *home* url.
![adding a name & a slug](//a.storyblok.com/f/af33b8e415/add-a-space-name.jpg)

### Confirm and create the story
By pressing the *save* button the new story will be created & you will be forwarded to the storylist of your space.
![adding a name & a slug](//a.storyblok.com/f/c8923bc32c/create-a-story.jpg)

# That's it!
you're now done setting up your space & also already created your first story. Start now creating your own components and build you website.

