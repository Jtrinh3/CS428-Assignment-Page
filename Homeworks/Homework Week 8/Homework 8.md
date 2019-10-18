# Homework Week 8

Imagine in the future, where we can identify almost everything on the fly on an eyewear app or on the phone. If so, how would we even display all of this information? We wouldn’t want them all to be displayed at once like the [YOLOv3 Application]( https://www.youtube.com/watch?v=MPU2HistivI). We also probably don’t want to literally label everything. Thus, the following are a few implementations I feel would be necessary for such an app.

## Focus Detection
We don’t want the app to create too many clutters, so I propose having a focus detection to alleviate this issue. With an app like this, eye tracking can likely be implemented to see what the user is focusing on in their field of view. When the user train their eye on an object for a notable amount of time such as half a second (which would be changeable base on the user’s preferences), then the identification would then show up but would be limited to whatever they are focusing on. Not everybody would want everything to be identified.

## But What About Audio?
In the case that it is audio detection, it’d be quite interesting to see how it would be implemented for a deaf person. Minecraft, for example, has an audio subtitle that list essentially every sound the user can hear and a direction of whether its to their left or right of their vision.

<figure>
    <img src='https://gamepedia.cursecdn.com/minecraft_gamepedia/a/a8/Subtitles.png?version=91972d0496baf18c92fa1926558ad829' />
    <font size="2">
    <figcaption> A snippet of *Minecraft's* audio display. <a href= "https://minecraft.gamepedia.com">Image taken from Minecraft Gamepedia </a> 
    </figcaption>
    </font>
</figure>


Similarly to the game, such a system would need to limit the amount of sound to visualize at a single moment as well as give priority. A reasonable solution is to prioritize the loudest one, or the closest. Perhaps a more cooler solution is to turn the world into a comic book where we see every sounds like POP! and BANG!

## Closing Remark
My overall feel about the future, is that once we reach a certain point where it's less about getting more information, perhaps sometime, it's better to not know. A common phase often thrown around is that "less is more". Perhaps we don't need all these informations. There's only so much one's mind can handle, it becomes about figuring out what information to filter out, rather than what information we can obtain.
