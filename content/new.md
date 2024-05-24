# New to Matrix

We're going to learn what Matrix is, and then create a Matrix user account and send our first message. This should feel pretty much the same as any other chat service.

## What is Matrix?

Matrix is a decentralised, secure protocol for exchanging events. It's a protocol like email is a protocol. So there are lots of different clients and servers, but they can all interact using the Matrix specification.

The structure Matrix provides can be used for a huge variety of tasks, but for our purposes we are going to use it as a group chat tool, similar to Slack, Discord, IRC, Teams etc.

## Creating a Matrix Account

We're going to create a new account. There are lots of places to register a matrix account because the software can be hosted anywhere.

However the simplest way is using the default instance of Element, a leading Matrix client.

1. Go to [app.element.io](https://app.element.io) ![element first page](./content/images/element-first.jpg)
2. Select "Create Account" ![element registration](./content/images/element-register.jpg)
3. Fill in details and click register. You may have to do a captcha ![element registration details fill in](./content/images/element-register-details.jpg)
4. Select why you're using matrix ![element logged in](./content/images/element-yourein.jpg)
5. This is the main element interface. You can do the steps they're presenting you with at your leisure. ![main element interface](./content/images/element-steps.jpg)

Welcome to the wonderful world of Matrix!

## Sending a Message

Matrix uses rooms to contain messages. Let's make a room and send a message

1. Let's add a room ![add a room](./content/images/element-addroom.jpg)
2. Make a new room. If you want to use this room for spacetube, the end-to-end encryption needs to be OFF, otherwise the bot can't read the messages ![make a new room](./content/images/element-newroom.jpg)
3. Send a message to the room ![send a message](./content/images/element-roommessage.jpg)

You should see your message in the room. You can also send images, and invites to other matrix users to join your room.

## Noting the Matrix User Id

Lets get your full matrix user id, because we're going to need it for spacetube.

1. In the top left you can partially see your id. You may need to click on settings to see it in full ![matrix settings](./content/images/element-matrixid.jpg)
2. Copy your id ![copy the matrix user id](./content/images/element-matrixid-settings.jpg)

The id should have the form: @yourusername:matrix.org or @yourusername:domain.tld if you used a different matrix server to create your account.

The "@" and the ":" are part of the id, make sure to include them when we use matrix ids in later instructions.

A matrix id is how you invite other users to rooms, or send them direct messages. The id is like their email address, but for matrix.

## What Next?

Congratulations, by making a matrix account and sending a message in a room you created, you have graduated to [current user of matrix](./current.html). See you on the next page!