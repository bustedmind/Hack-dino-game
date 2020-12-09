# Welcome to Google chrome dino game hacks!

![enter image description here](https://raw.githubusercontent.com/mabhaymaurya/Hack-dino-game/main/hack%20t-rex%20game.jpeg?token=AI6B4PFRA427TLSMBUITIPK72BHII)

Hi welcome, here you will learn how to hack google chrome **dinosaur game** ( **t-rex** game ). You only need to follow the below steps. With this you can acheive max score **999999**.  for more please visit below link.
	
[Dino game hack Tutorial](https://youtu.be/j4_kvBsOKXc)

- Dino game will automatically open in the chrome when there is no internet if you still not getting you just go to URL bar and enter 

    ``chrome://dino``
    
 - Open console panel using **right mouse click -> Inspect > console** or enter **F12** 
 ![enter image description here](https://raw.githubusercontent.com/mabhaymaurya/Hack-dino-game/main/console.png?token=AI6B4PCJ7VH6Y2BXAFFFYGK72BHOQ)
 - Now you only need to copy and paste the below JS code according to the need what you want to hack into console panel. then enjoy the party ... 


# JS Scripts

Please copy and paste the given code into console and enjoy the hacks. Play while changing the values. 

## -- Hack Acceleration

    // Starting speed
    Runner.config.ACCELERATION = 1.2
## -- Hack Initial Speed
	// Starting speedR
	Runner.config.SPEED = 100

## -- Hack speed at any time 

    Runner.instance.setSpeed();
   
## -- Hack Game score

    Runner.instance_.distanceRan = 1222900
## -- Change dino character
You need one image URL like [https://i.imgur.com/7BuRkS9.png ](https://i.imgur.com/7BuRkS9.png) and replace with image src of offline resources.

![Image should be in this format](https://i.imgur.com/7BuRkS9.png)

You copy the image URL and replace the image URL as per below SS 

![enter image description here](https://raw.githubusercontent.com/mabhaymaurya/Hack-dino-game/c62213eff7d52a638514a706a1f1e3d517bc69a5/trex-resouce-replace.png?token=AI6B4PBDQKO3LYY5QDAWCMS72BGQW)

Now you are donw with changing Avatar. 
## -- Bot Play the game
Run the below code to let the JS play the game.

    const autoPlay = function () { 
	    const JUMP_SPEED = 50; 
	    const DISTANCE_BEFORE_JUMP = 120; 
	    const instance = window.Runner.instance_; 
	    const tRex = instance.tRex; 
	    if (tRex.jumping) { 
		    requestAnimationFrame(autoPlay); 
		    return; 
		} 
		const tRexPos = tRex.xPos; 
		const obstacles = instance.horizon.obstacles; 
		const nextObstacle = obstacles.find(o => o.xPos > tRexPos); 
		if (nextObstacle && nextObstacle.typeConfig.type == "PTERODACTYL" && tRex.yPos > (nextObstacle.yPos + nextObstacle.typeConfig.height) && tRex.jumping && !tRex.ducking) {
			tRex.setDuck(true); 
			obsDist = nextObstacle; 
		} 
		else if ( tRex.ducking && nextObstacle && ( nextObstacle.typeConfig.type == "PTERODACTYL" && (tRex.yPos < (nextObstacle.yPos + nextObstacle.typeConfig.height)) || nextObstacle.typeConfig.type != "PTERODACTYL")) { 
			tRex.setDuck(false); 
			obsDist = nextObstacle; 
		} 
		else if (nextObstacle && (nextObstacle.xPos - tRexPos) <= DISTANCE_BEFORE_JUMP) { 
			tRex.startJump(JUMP_SPEED) 
		} 
		requestAnimationFrame(autoPlay); 
	} 
	autoPlay();

# You can play with the code to hack more. 
![enter image description here](https://raw.githubusercontent.com/mabhaymaurya/Hack-dino-game/main/t-rex-game.png?token=AI6B4PABCH5MF2VBVOUQMNK72BHWK)

Thanks for watching. 
follow us on [Youtube](https://www.youtube.com/channel/UCb00xaR27QrZtwQypbIpphA/)
