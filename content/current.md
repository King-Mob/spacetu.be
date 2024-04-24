# Current Matrix User

Spacetube assumes you have a group that uses matrix and you want to talk to another group that uses matrix.

You're going to use spacetube to send messages back and forth from your group to another.

There are two ways to do this:

1. Using the spacetube web app ([spacetube.spacetu.be](spacetube.spacetu.be) is the default instance)
2. Using your matrix client ([app.element.io](app.element.io) if you're coming from the previous doc)

The web app is more visual, and the matrix client method uses bot commands. If you want to use spacetube in an existing room then you need to use the matrix client.

## Spacetube Web App

Open the [spacetube web interface](https://spacetube.spacetu.be). 

1. Enter your matrix id and the name of your group. If you know the recipient's matrix user id, then include that as well. ![creating a tube](./content/spacetube-create.jpg)

2. Copy the link and share it with your contact. ![spacetube link](./content/spacetube-copy.jpg)

3. When they've accepted the link, the tube will show up as available on the home page and going on the link will show the messaging interface.

From the contact point of view:

1. This is what they'll see when they go on it. ![spacetube contact creating](./content/spacetube-other-create.jpg)

2. When they click, it'll ask them to wait. ![spactube contact creating and waiting](./content/spacetube-other-create-wait.jpg)

3. Then take them to the messaging screen ![spacetube messaging](./content/spacetube-other-message-new.jpg)

The messaging interface:

1. Invite your other group members using the (🧍+) button ![spacetube invites](./content/spacetube-other-message-invite.jpg)

2. Send a message to your group using the input at the bottom ![spacetube send a message](./content/spacetube-other-message-sent.jpg)

3. Forward a message to the other group by clicking on the message you want to forward ![spacetube forward message](./content/spacetube-other-message-forward.jpg)

4. It should appear in a few seconds. ![spacetube forward message](./content/spacetube-other-message-forward-sent.jpg)

5. See a reply from the other group ![spacetube reply](./content/spacetube-other-message-reply.jpg)

You are now doing group to group communication!

## Matrix Client

Open your matrix client e.g. [Element](https://app.element.io)

1. Select or create the matrix room you want to use spacetube in. A spacetube room CAN'T be end-to-end encrypted, but it can be private. ![element room creation](./content/element-newroom.jpg)
2. Change the name of the matrix room to the name of your group. This is how spacetube knows what to call the user representing your group. You can change it to something else after you've forwarded your first message. ![element room options](./content/element-room-options.jpg)
![element room settings](./content/element-room-settings.jpg)
3. Invite spacetube-bot, by entering the user id @space-tube-bot:spacetu.be. If it says "user may not exist" click invite anyway. ![invite spacetube bot](./content/element-invite-spacetubebot.jpg)
4. Send "!spacetube create" ![spacetube create command](./content/element-spacetube-create.jpg)
5. Copy the connection code and send it to your contact. In the picture above the connection code is "9380bd37-1a78-4a8d-8e90-a5d5d6080c1d~@space-tube-bot:spacetu.be"
6. Have your contact send "!spacetube connect insert-connection-code-here"  ![spacetube connect command](./content/element-spacetube-connect.jpg)
7. Spacetubebot says the tube is open
8. Send "!spacetube forward hello" ![spacetube forward command](./content/element-spacetube-forward.jpg)

You are now doing group to group communication!

## From Client to Web App

If you want to use the web app to see your matrix room and have a more visual experience, then this is possible, by using the "!spacetube link" command.

![spacetube link command](./content/element-spacetube-link.jpg)

The link will have a token a nickname in it. The nickname is set when you first join.

This is what you see if you follow the link:

![spacetube follow link](./content/element-spacetube-link-followed.jpg)

On the left is the conversation in your matrix room and on the right is the conversation that's being forwarded through spacetube.

## What Next?

Realistically, this is as far as most people need to go. You're using spacetube to send messages. Your group is already light years into the future!

Say hello on #spacetube-public:spacetu.be

[Learn more](./why.html) about the motivations behind creating spacetube.
