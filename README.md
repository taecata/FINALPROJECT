Final Project- Interactive Graphics and Critical Code

Name: Tae Markey 

Date: April 18th 2018 

Project: ... tbd

Conceptual Description
For my final project, I'd love to further explore the concepts of the last two projects: social media and ideas about the Self. I want to expand my fourth project in which I wanted to mimic the way in which we perform online especially on social media platforms like Facebook. We are both required (socially) to act on Facebook in relation to the 'social' aspect of it (performing under the gaze of other people) and the 'media' aspect which is to become algorithmically recognizable. In both instances, our actions and posts online can become misinterpreted and, at least in my experience, I feel like it is better to not post anything at all. Hence, the theatre of constraint in which you would rather stand still and observe in order to not create a commotion. 

Interaction Description

The interactive part of my project is the entire project: an exchange between the person "performing", the sounds and visual reactions, and the audience. I would like users to be able to look into the camera and see themselves projected onto a screen, with the emojis and sounds. In its setup, my piece will hopefully have a computer that can run the programs necessary, or a camera and projector screen that could execute the same actions. The intended audience is anyone who participates within online social media because the piece intends to create a sensation within the user's body and their actions. Hopefully they will have to feel constrained in a certain way through their bodily movements in order to amplify the project's concepts. 

Extension
Another aspect of the project that I wanted to add was a loud applause that would play once there is no face detected. The concept behind this would be that at that moment the user would want to stay in order to experience the applause, but as soon as they turn back to face the 'public' the applause would stop - this sound acts like a luring back into the theatre of constraint. I would also like to add some more sounds and make the emojis display in a different and more interesting way. I would also like to use the data that I have downloaded from my Facebook account in a way that allows me to re-appropriate that data, and make it 'mine' again by using it to reveal something to myself that I perhaps did not know before. I am still trying to find how I could combine these two concepts together…

Technical details

Libraries used: 

p5.js
p5.sound 
FaceOSC

Snippets of code:

if(eyebrowLeft>8 && !cry.isPlaying()){
		cry.play();	
	}

	if(eyebrowLeft<=8 && cry.isPlaying()){
		cry.pause();
	}

	if (eyebrowLeft>8){
		image(imgCry, 150, 150, 100, 100);
		image(imgCry, 450, 150, 100, 100);	
		image(imgCry, 750, 150, 100, 100);	
		image(imgCry, 150, 450, 100, 100);	
		image(imgCry, 150, 750, 100, 100);	
		image(imgCry, 750, 450, 100, 100);
		image(imgCry, 450, 750, 100, 100);	
		image(imgCry, 750, 750, 100, 100);	
		image(imgCry, 450, 450, 100, 100);
	}

	//if(NOFACEDETECTED == 0 && !applause.isPlaying()){
		//applause.play();
	//}

	//if(NOFACEDETECTED>0 && applause.isPlaying()){
	//	applause.pause();
	//}

link to sketch: 