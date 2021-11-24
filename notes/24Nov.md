# ICT Lesson Notes, 24 November 2021 #

## 1. Quick recap ##
- What is interaction?
	- Interaction = Human and machine interact
	- Even an non-function button is also considered interactive
	- As long as something happens after user action, it will be considered as interaction.
	- Video that starts to play once website loads is only a multimedia element.
	- Pretty dumb but memorize it :)
- Refer to textbook for more dumb info
- For presentation we have:
	- Slide
	- Multimedia (Pretty much everything else except text, e.g. Audio Video Animation etc etc etc)
	- Transition & Animation effects
		- Transition = Different slides
		- Animation = Within the same slide
- Separation of information 
	- Separate into title, text, and annotations. Add images if necessary.

## 2. OLE ##
- OLE = Object linking / Object Embeddings
- What is an object?
	- Everything can be an object.
	- e.g. text, image, excel spreadsheets.
- How to do OLE? 
	- Powerpoint ribbon -> Insert -> Object -> Follow on-screen instructions
	- Tick checkbox `Link` if you want to do Object link. If you want to do object embed, don't select the checkbox.
- Object links VS Object Embeddings
	- Object link - Shortcut (preview) of the file to the powerpoint slide.
		- Changes will be synced real-time.
		- A symbolic link will be created for the file in the slide.
		- Powerpoint will crash if the linked file is deleted. It will only save the last known version of the file.
		- Object Linking is basically creating a symlink (`ln -s`)of an file to a powerpoint.
	- Object Embedding - Embed (include) file to the slide / Powerpoint presentation.
		- Changes will not be synced real-time.
		- The whole file now exists in the slide. 
		- User will be warned that a potential security concern exists if the embedded file on drive has been edited.
- Usages in real life
	- Object embedding
		-The file needs to be widely shared.
		- Use object embedding if you want to play safe.
		- All files will be included in the powerpoint, no matter how the file changes on the hard drive.
	- Object linking
		- When you're running low on disk space
		- When you want to show real-time changes on files.

## 3. Conclusion ##
- Object linking
	- File size increase less
	- Location of included files needs to be fixed
	- File changes affect each other
- Object embedding
	- File size increase more
	- Location of included files does not matter
	- Files are independent
