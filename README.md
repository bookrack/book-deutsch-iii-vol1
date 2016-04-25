# book-deutsch-iii-vol1

------------

Installation:

1. Clone the repo
2. Create media directory: ```mkdir src/media/```
3. Add book media (eg: images go into ```src/media/img/```)
Folders needed: img, audio, video
4. Go into subrepo and install dependencies: ```cd src/rack/``` + ```npm install```
5. Generate book + start server: ```gulp```

Update subrepo from github remote:

From repo root: ```git subrepo pull src/rack```
