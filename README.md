# checkpoint_charlie

Once upon a time, a team tried to work on the same file without causing any issues. Like the McDonald's ice cream machine, this never worked. What you're seeing here is the culmination of blood, sweat and tears.... mostly tears.

![a git meme](./git_merge.gif)

<div style="position: relative;">
    <h2 style="text-align: center;">Glitter Effect</h2>
    <div style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; overflow: hidden;">
        <div style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; background-image: linear-gradient(to right, #ff0000, #00ff00, #0000ff); background-size: 200% 100%; animation: glitter 2s linear infinite;"></div>
    </div>
</div>

<div style="position: relative;">
    <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);">
        <div style="width: 200px; height: 10px; border-radius: 50%; background-color: #ff00ff; animation: pulsate 2s ease-in-out infinite;"></div>
    </div>
</div>

<style>
@keyframes glitter {
    0% { background-position: 0% 50%; }
    100% { background-position: 100% 50%; }
}

@keyframes pulsate {
    0% { transform: scale(1); }
    50% { transform: scale(1.2); }
    100% { transform: scale(1); }
}

h2 {
    position: relative;
    z-index: 1;
}
</style>

## Power Rangers

![power rangers gif](https://i.pinimg.com/originals/01/e6/fa/01e6fa9cea757c01e79039b0d12d4bc8.gif)

Are you ready to morph into a Power Ranger and save the world?


##How to NOT push to a shared repository

- Do not push while someone else is pushing.
- Always pull before you push. Unless someone else is pushing after you pulled.
- Live dangerously: use merge. It's not going to work. Try again. The conflict manager opens. It's still not working. Rage reverse to 6 commits in the past. All your work from the last 2 hours is lost. Go for a walk.
- Turn on your computer again.
- Why are you logged out of GitHub? GitHub sends a code to your email address to log in. Your email provider sends a code on your phone to log in. You suddenly have no phone network for no apparent reason.
- You are finally back in. Pull again. There is a conflict.
- You try to force push anyway. Turns out you pushed from a even earlier commit. Your repository now only contains an empty README.md file.
- Maybe do not actually push anything to GitHub. It's not worth it. You're thinking abour starting a new career as a gardener once you have recovered from your mental breakdown.