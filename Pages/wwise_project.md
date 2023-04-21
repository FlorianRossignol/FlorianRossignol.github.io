# Wwise
## Context
For the Aer Racer specialization project, the entire audio part was implemented via the WWise software, as it too is widely used in the video game industry. The software, like Perforce, was imposed as part of the third-year project.

## WWise Integration
### WWise software
After installing the software, I had to make the link between it and Unreal to do this in the launcher of WWise we have directly the option to integrate it into the project.

[![](http://FlorianRossignol.github.io/Images/Perforce/wwise_launcher_unreal.png)](http://FlorianRossignol.github.io/Images/Perforce/wwise_launcher_unreal.png)

![](http://FlorianRossignol.github.io/Images/Perforce/wwise_integration.png)

After that, you have to compile the c++ code in unreal to finally get the full integration.

### WWise audio file

Concerning the audio implementation in the software for this project, we had more than six collaborative audios for everything that is music, SFX and UI. Because of this, we had to import the sounds produced on different audio production software directly into WWise, we use the audio part of the software which is entirely dedicated to the raw implementation of the audio.

*Example of the final audios in the Aer Racer project:*

![](http://FlorianRossignol.github.io/Images/wwise/WWise_audio.png)

On this example of a part of the final audios present in the project, we can see different subparts. To be more precise, each sound is grouped in containers in order to have several sounds played at the same time or different ways to play each sound separately.

*Example of a container contained in the audio part of WWise:*

![](https://FlorianRossignol.github.io/Images/wwise/wwise_audio_containers.png)

## Event Wwise

Now that we have the audio part implemented, we need to synchronize it in Unreal, for this we will use what we call events.

*Example of an event in the final project:*

![](http://FlorianRossignol.github.io/Images/wwise/event_wwise.png)

We can see here an event that can contain several actions, launches a sound, pause it or start it again.

*An example of the possible action:*

![](https://FlorianRossignol.github.io/Images/wwise/wwise_event_action.png)

## Game settings
For the sounds of the pods in general we wanted the sound to evolve according to the speed of the ship, to do this WWise proposes parameters of game or we can retranscribe the maximum speed of the ship and apply a curve on our sound of pod which will evolve according to the speed of this one.

*Example of the game parameter concerning the speed of the ship:*

![](http://FlorianRossignol.github.io/Images/wwise/Game_parameters_wwise.png)

*And the curve created on the engine noise :*

![](http://FlorianRossignol.github.io/Images/wwise/wwise_courbe.png)

## SoundBank
When we have all our audio available and the events created, we can build our sound bank, to be able to import everything into our game. To do this we go directly to the sound bank section and take the events to generate them.
Example of the sound bank created for Aer Racer:


*We take all our events:*



*And finally we generate our sound bank:*




All the setup is made to create soundbanks that in a triple A game for example, we can divide the soundbank to load the soundbank or soundbanks to optimize the sound because of large projects, we can have up to five GB of data just for the audio data.

## Unreal integration
Now that everything is set up for the audio part, we have to integrate our events and our game parameters directly into Unreal.

Following the integration of WWise we have a new window available to generate our sound bank and have access to the WWise project.

*WWise Picker available in Unreal:*

By clicking on Generate SoundBanks you can synchronize sounds, events and game settings in Unreal.

## Event and game parameter in Unreal
Now you have to take the events and integrate them by hand in Unreal. Be careful, you have to have exactly the same name as the one in WWise.

After that we have our events directly available in Unreal and we can use them in our code or blueprint!

## Problems encountered
For WWise, the problems encountered were rather the communication and the reception of the audio assets because the audio team had very late specific courses on WWise and thus started the delivery of the sounds late. The delivery of all the validated and imported assets in WWise took place the second week before the end of the rendering.

## To go further

Wwise is a very complete software that allows you to do a lot of things on the audio level, so I haven't seen the full capacity of the software, on other personal projects, I will reuse WWise for the realization of the audio and thus have more control over all this part.

## Conclusion
I really enjoyed using WWise for the audio part and was able to get a good overview of how to use the software with Unreal, especially by participating in the audio course with a person from Ubisoft in charge of teaching it.

------------



