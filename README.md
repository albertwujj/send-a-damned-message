# Send A Damn Message

To play:
```
python send_a_damned_message.py
```

You can type `SKIP` or `BACK` at any time to browse through levels.

Don't look at the source, it can spoil gameplay.

# Development

For now just read the code, there are no dependencies really.

WIP: porting to Reason-React at `send-a-damn-message`

# Game ideas

I was originally thinking to have a two player game, in which the two players can't communicate except through a chat room.  But the chat room is a noisy channel f and you see f(x) for incoming messages.

# Front End Version (WIP)

## Install

```
npm install
```

## Run

```
npm run server
# in a new tab
npm start
```

Open a new web page to `http://localhost:8000/`. Change any `.re` file in `src` to see the page auto-reload.

# Bundle for Production

```sh
npm run buildprod
open build/index.html
```
