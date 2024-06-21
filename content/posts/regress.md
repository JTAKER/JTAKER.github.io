+++
title = 'Elden Ring Patch Rollback'
date = 2024-06-20T21:22:29-04:00
+++
![Elden Ring Banner](/elden.jpg)

# Step 1

Type this in your browser.

```
steam://nav/console
```

A prompt will pop-up and open with steam.

# Step 2

Copy & paste each thing 1 by 1 into the console that opens in the steam client:

```
download_depot 1245620 1245624 4173907165901381087
```

```
download_depot 1245620 1245621 4586391483365949586
```

That second one is redownloading the game, so it'll take some time. You might be able to check the download in the Downloads tab of Steam but sometimes it doesn't show up.

# Step 3

After it's done...

1. Go to your Elden Ring install folder: "[your_path]\steamapps\content\app_1245620"
2. Merge the two "depot" folders into one.
3. Remove all the files from the original Elden Ring folder, **EXCEPT** for the seamlesscoop files.
4. Copy the files from your merged depot folder into the now *nearly* empty Elden Ring folder.

# Step 4

Launch the game using the seamlesscoop launcher.