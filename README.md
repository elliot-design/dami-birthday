# For Dami

A birthday site. Plain HTML, CSS and JavaScript, so there is nothing to install or build.

## Add your files

```
index.html
photos/   1.jpg ... 11.jpg   (png, jpeg and webp also work)
audio/    birthday.mp3  fireworks.mp3  siu.mp3
```

- Photo 1 to 11 match the captions in the Memories page, in order. Keep each photo under about 300 KB so it loads fast on a phone.
- A missing photo shows "Photo coming soon". A missing sound falls back to a built-in stand-in.
- To change a caption, a file name or the Siuuu timing, edit the "EDIT ME" block at the top of the script in `index.html`.

## When each sound plays

| Sound | Plays |
| --- | --- |
| `birthday.mp3` | After she taps "Come in". Loops, and dips while the Siuuu plays |
| `fireworks.mp3` | When the fireworks launch in the opening, on the last page, and on "More fireworks" |
| `siu.mp3` | When the player lands. If it is early or late, change `SIU_DELAY` (milliseconds) |

## Test it

Open the folder in VS Code and run it with the Live Server extension, then check it on your phone too.

## Put it online

1. Create a new repository on GitHub, then in the project folder run:
   `git init`, `git add .`, `git commit -m "birthday site"`, `git branch -M main`, `git remote add origin <your repo url>`, `git push -u origin main`
2. On vercel.com choose Add New, then Project, and import the repository. Leave every setting as it is and press Deploy.
3. In the project settings on Vercel, rename the project to something like `dami-turns-18` to get a clean link.
