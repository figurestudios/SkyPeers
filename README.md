# SkyGameSDK
> developed for the ENCODE and the Built to Explore hackathons.

> With SkyGameSDK, you can easily add tons of features to Unity WebGL games; multiplayer, screenshots, leaderboards, achievements, etc,,,

# Inner workings
The cross-communication between the browser and Unity works through the WebGLPluginJS.jslib file in Unity's Assets/Plugins/WebGL file and the SendMessage() function in the game instance.

# Setup
Clone this project, install WebGL for Unity, switch platform to WebGL, press "Build and Run" in Unity, swap out the generated .html file to the one provided in the project.

# Done
* [Early P2P Demo - SkyDB testing](https://100ccrtto8qqedqa84kb6sjcl609kbqirbevn2rv79avqu1fq5iikko.account.siasky.net/)
* [Working "Color-Sharing" Demo - completed Unity<>SkyDB](https://60061g6oprj2pi50jku6el64c81f94r10kfgmtkqp5pij6sch8jfk00.siasky.net/)

# Potential additions // TODO(partly)
* Real-time connections(might require websockets, as not everyone can connect with P2P without TURN/STUN servers)
* MySky for communication instead of 
* Screenshots (possible in Unity, and can then communicate to the browser with the WebGLPluginJS library)
* Lobbies(done via mysky, host whitelists friends, friends posts publickey to skydb,,,)
* Working chess example
* Extrapolation parameters in networking to simulate sync? (inclusion of time on send)
