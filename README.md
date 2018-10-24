# Real-time_ToyRig
Pose the model like play the toy in real time!!!  no more time waste rigging things, you can just grab the model and play it, play the model and have fun in humanize way.
##################################################################################
</br>
It sell $15 on blender market, part of in come will contribute to blender, and when there is more than 3000 people to buy it,it will apear in here,and it license will automatically become CC-zero, witch is mean it will totally open source and free like blender.

## What it does

Pose the model like playing with a toy in real time!!!  No more time waste rigging things, you can just grab the model and play with it, play with the model and have fun in a humanizing way.

## How to use it

In FK mode: you can rotate controller, and set FK chain by a set fixed controller

In IK mode: you can set IK by set fixed controller, and then move the controller, and you can set reverse FK by fixed two ends controller and select the controller you want to rotate, the front fixed controller will be pivot.

In Fix mode: you can't select the controller inside the fix controller chain, here is a place you can rotate in IK mode or move in FK mode

In Lock mode: you can't select any controller, in here you can see the animation you set and edit it use those things like Graph Editor, and you can adjust pole position by select the pole in IK mode and then entry Lock mode

Custom controller: select the controller you set you self, and click the install controller on the panel, then this tool will leave it along and will not install any controller over it, and make some deform bone's controller vanish is same thing

Keys：

Mouse click(default it right, can change in panel): select most close controller

Double click: in IK/FK mode hide or show the closest controller so it can't be select, in lock mode hide or show all deform bone with custom controller

Shift+ click: install fixed controller

Ctrl + click: uninstall fixed controller

X: switch FK/IK mode

R: switch to FK mode if in IK mode and then rotate

G: switch to IK mode if in FK mode and then move

V: set selected bone IK follow if selected bone is IK controller or pole controller

F: switch  IK FK/Fix mode

Q: switch IK FK Fix/Lock mode

I: set Visual LocRotScale to all deform bone and custom controller

Just imagine you are playing the toy, then everything will be just fun :)

## Export:

When you clean off the tool, it will only leave the deformed bone and animation, so it will have no problem export to a game engine or another 3D software.
