### I maintain 4 repositories to make live music; three of them depends on dsacre/mididings that I have forked

⚡⚡⚡ The most important : A fork of the abandonned by the author, dsacre/mididings, to be able to compile and run it with the very latest Python version, in a virtual environment. IT MUST NOT DIE UNDER ANY CONDITION

⚡ live-config which is my main entry point for live performance, a bash script that generate my fatty script for mididings and start the engine.

⚡ flaskdings which is an API and a HTML5 UI to communicate with mididings through the OSC protocol. It is a modern alternative to the livedings GUI included in the mididings solution.

⚡ osc-soundcraft-bridge which is a bridge between the OSC protocol and the SoundCraft UI series; I send OSC message via MIDI with mididings and the bridge convert the OSC message to a UI message and send it to the mixer via socket.

😄 I am a collaborator of the mpyg321 project which is a Python wrapper over the mpg123 player. I use this lib as a plugin in stefets/live-config

💬 Need professionnal support ? Contact me via an issue if you are a professionnal musician that want to integerate my solution in your setup.

#### I am a programmer and a mididings power user with a five years of learning curve and near, daily usage. I support users on the https://groups.google.com/g/mididings

<!--
**stefets/stefets** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
