![68747470733a2f2f696d672e736869656c64732e696f2f646973636f72642f3232323037383130383937373539343336383f636f6c6f723d353836354632266c6f676f3d646973636f7264266c6f676f436f6c6f723d7768697465](https://user-images.githubusercontent.com/97564562/194720915-b8ea165f-f39e-4fb6-a67a-d3aa6ab2ef24.svg)
![68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f646973636f72642e6a732e7376673f6d61784167653d33363030](https://user-images.githubusercontent.com/97564562/194720919-2b9be53e-6cb1-4803-b07f-69f30a0b2705.svg)
# Discord-RPC
# Run command **node ./src/f2q.js**
![F2q](https://user-images.githubusercontent.com/97564562/209447416-6a6f385f-2858-43e5-a0a4-69e3df1b960f.png)
```javascript
async function setActivity() {
    if(!RPC) return;
    RPC.setActivity({
        details: ``,
        state: ``,
        startTimestamp: Date.now(),
        largeImageKey: ``,
        largeImageText: ``,
        smallImageKey: ``,
        smallImageText: ``,
        instance: false,
        buttons: [
            {
                label: ``, //First Button
                url: ``, //Url
            }
        ]
    });
};
```
![F2q2](https://user-images.githubusercontent.com/97564562/194639848-9bdb5873-04e3-4f6a-ae73-5e11c73f282b.png)
<p><a href="https://nodei.co/npm/discord-rpc/"><img src="https://nodei.co/npm/discord-rpc.png?downloads=true&stars=true" alt="NPM info" /></a></p>
