# D2Etal_PoD
Custom D2Etal bot working on Path of Diablo private server (Javascript)

Same functionalities as the original D2Etal bot and more, for example :
 - team botting for early ladders with multiple classes, autofollow ... with NTHelper
 - Bot can teleport with necro / druid too
 - Map script (not working well)
 - Take custom mod items (OOCs, map keys ...)



Current issues:
  - Sometimes after ~5000 runs, the bot delete his merc
  - Map script : the bot doesn't attack monsters
  - Countess script doesn't work (NT_TakeStair(6) failed when the bot reach black moor)
  - Map hack crash act 2
  - few issues with stash, the bot doesn't fill the whole cube
  - Crash when char got chaos keys sometimes ?
  
  
  
How to make this bot work :
This solution is a bit tricky, maybe won't work for you but it worked for me, don't hesitate to ask me if you got any problems.
So i just took Fog.dll from original diablo 2 folder and replace PoD Fog.dll that's it ...


Improvement to do in importance order :
 - Fix stash problems
 - Make countess script works
 - Find why the bot delete his merc sometimes(very strange bug btw ...)
 - Any other ideas ?
