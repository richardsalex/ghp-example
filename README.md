# JNL 221 - Example repository

__You're on the main page for a repository called `pages-example`.__

Think of this repository like a folder on your computer. In JNL 221, you're frequently organizing our HTML, CSS and content files for different projects in one folder. Once everything is working the way you want it to locally (meaning on your own machine), you can upload those files to a Github repository and maintain the organizational structure you used there.

### How this example repository is organized:

```
├── images/
│   ├── Armorysquaresyr.jpg
│   ├── Destiny_USA.png
│   └── Syrcityhall2.jpg
├── index.html
├── other.html
└── README.md (the file you're reading)
```

## Things to keep in mind:
* __File names matter.__ Even a slight difference will throw things off. `index.html` is different than `index(3).html` and `INDex.HTML`

* __Paths to files matter.__ If I want to show the image `Armorysquaresyr.jpg` in my HTML file, I have to point toward `images/Armorysquaresyr.jpg` because it's located inside a folder. (More on [file paths](https://www.w3schools.com/html/html_filepaths.asp).)

* __Your core HTML file should be named "index.html".__ The URL for this repository is [https://richardsalex.github.io/pages-example/](https://richardsalex.github.io/pages-example/) and will go directly to `index.html`.

* __Changes may not be instantaneously reflected online.__ If I'm getting a 404 page when I go to the above URL, I can try visiting the pages individually: [https://richardsalex.github.io/pages-example/index.html](https://richardsalex.github.io/pages-example/index.html) or [https://richardsalex.github.io/pages-example/other.html](https://richardsalex.github.io/pages-example/other.html). If it's not working, see "__File names matter__" or "__Paths to files matter__" above.

## I want to:
### Create a new repository from scratch.
Go check out the instructions you've been given and video I recorded for you, both posted on Blackboard. Alternatively, read [Github's own documentation](https://docs.github.com/en/get-started/quickstart/create-a-repo) on the subject.

### Upload all my files to a repository. 
1. From the main repository page, click the `Add file` button, selecting `Upload files` from the drop-down menu.

2. Drag and drop the _contents_ of the project folder on your computer where indicated. __Don't drag the folder itself, but the files and folders inside of it.__

3. Click the green `Commit changes` button.

### Upload an individual file _OR_ replace an existing file with a new version.
1. From the main repository page, click the `Add file` button, selecting `Upload files` from the drop-down menu.

2. Drag and drop the file from your computer where indicated. Or: follow the `choose your files` link and navigate to the file you want to select.

3. Click the green `Commit changes` button.

### Edit a file here.
1. From the main repository page, click on the name of the file you want to edit.

2. Click the pencil icon with the `Edit this file` tooltip. 

3. Make changes to the file name or file content.

4. Click the green `Commit changes` button.

### Remove a file.
1. From the main repository page, click on the name of the file you want to remove.

2. Click the trashcan icon with the `Delete this file` tooltip.

3. Click the green `Commit changes` button.

### Publish my repository to Github Pages.
1. From the main repository page, click `Settings`, which has a gear icon next to it.

2. On the left rail, click `Pages`.

3. Click on the button that says `None` and select `main`.

4. Click the `Save` button.

5. You repository should now be published at the link shown. The URL format is generally `https://[your username].github.io/[your repository name]/`. If it's not showing up or you're getting a 404 webpage, go look at "__Changes may not be instantaneously reflected online__" above.
