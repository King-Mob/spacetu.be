# Current Matrix User

Spacetube assumes you have a group that uses matrix and you want to talk to another group that uses matrix.

You're going to use spacetube to send messages back and forth from your group to another.

## Simple Set-Up

There are 3 steps to using space tube:

Create your group user.
Connect to another group.
Send messages.

All 3 steps can be done either on the spacetube web app ([spacetube.spacetu.be](spacetube.spacetu.be) is the default instance) or through matrix ([app.element.io](app.element.io) if you're coming from the [previous doc](./new.html)). You can also switch from one to the other later on, so don't worry about being locked in to one approach.

The [web instructions](./current.html#spacetubewebapp) are first and then the [matrix instructions](./current.html#matrixclient) are below.

## Spacetube Web App

Open the [spacetube web interface](https://spacetube.spacetu.be). 

### Creating A Group User

This is the first step. Your group user represents and speaks on behalf of your group.

1. Enter your group name under Create Group User ![group name](./content/images/web-1.jpg)
2. Click "Create". ![group creation](./content/images/web-2.jpg)

The group user has been created! 

Now you can either continue on the web, or take the group user id to the matrix instructions.

### Connect With Other Groups

Here we use the group user created in the previous step to connect with another group.

1. After creating your group user, enter your name to get an invite link ![enter your name](./content/images/web-3.jpg)
![invite link created](./content/images/web-4.jpg)
2. Share the invite link with your contact
3. Click the link to your room and wait for it to be open ![waiting to open](./content/images/web-13.jpg)

Your contact now needs to:

1. Follow the link ![follow invite link](./content/images/web-5.jpg)
2. Enter their name and their group's name ![enter invite details](./content/images/web-6.jpg)
3. Click Accept Invite ![accept invite](./content/images/web-7.jpg)
 ![see messaging screen](./content/images/web-8.jpg)

### Send A Message

You should be looking at a messaging screen.

1. Type a message in the field and press send.  ![see messaging screen](./content/images/web-8.jpg)
2. Click on the message to forward it. ![see messaging screen](./content/images/web-9.jpg)

The message will be forwarded.

### Changing Group Display Name and Picture

1. Click on the mask icon to go to the page that changes your group user's profile ![profile edit](./content/images/web-12.jpg)
2. Enter a new name and/or upload a new profile pic
3. Press save

### Going from web to matrix client

1. Get your matrix id from your client, by clicking on your profile, then settings ![get matrix id](./content/images/matrix-14.jpg)
2. Click the (🧍+) invite button on the web messaging screen 
3. Enter the id you want to invite ![invite matrix id](./content/images/web-11.jpg)
4. Go on the client and accept the invite

You're in.

## Matrix client

Open your matrix client

### Creating A Group User

0. Ensure your room is not end-to-end encrypted when creating it ![room creation](./content/images/matrix-3.jpg)
1. Invite @space-tube-bot:spacetu.be to your chat ![invite space tube bot](./content/images/matrix-5.jpg)
![space tube bot joins](./content/images/matrix-6.jpg)
2. Send "@space-tube-bot create" to create a group user ![space tube bot create](./content/images/matrix-7.jpg)
3. Invite the user id that spacetube gave you, or the matrix id you got from the web app in the web instructions above. ![invite group user](./content/images/matrix-8.jpg)
 ![group user joins](./content/images/matrix-9.jpg)

The group user has joined the chat! It will share with you another matrix id, that we call the invite id. This is what you give to other groups to create the connections. They don't invite your group user directly, they invite this invite id.

### Connect With Other Groups

Here we use the group user created in the previous step to connect with another group.

1. After inviting the group user, it will give you an invite id to share with your contact ![group user joins](./content/images/matrix-9.jpg)
2. Send your contact this id. When they invite it and send a message, the connection will open

Your contact now needs to:

1. Invite the id they received from you ![invite the user](./content/images/matrix-10.jpg)

### Send A Message

1. Send a message with @other-group-name at the start ![send a message](./content/images/matrix-11.jpg)

The message will show up in your chat and theirs as being from your group.

### Changing Group Display Name and Picture

1. Send a message that says `@my-group profile` to get the link for editing the profile ![request edit profile link](./content/images/matrix-13.jpg)
2. Click the link.
3. Enter a new name and/or upload a new profile pic ![profile edit](./content/images/web-12.jpg)
4. Press save

### Going from matrix client to web

1. Send `@my-group link` to get a link to the web app ![request group link](./content/images/matrix-12.jpg)
2. Click the link

You're in.

## What Next?

You have just done group to group communication!

Realistically, this is as far as most people need to go. You're using spacetube to send messages. Your group is already light years into the future!

Say hello and talk about possible improvements on [the spacetube public chat](https://matrix.to/#/#spacetube-public:spacetu.be).

[Learn more](./why.html) about the motivations behind creating spacetube.
