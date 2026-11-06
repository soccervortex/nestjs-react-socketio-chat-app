# NestJS + React + Socket.IO chat app in production

A real-world example of a real-time chat application running these technologies together in
production, not just a tutorial repo.

**Live example: [Dislite](https://dislite.xyz)**, a chat and community app with groups, DMs,
voice chat, and presence, serving real users right now.

## Stack

- **Backend**: NestJS, MongoDB, Socket.IO for real-time events
- **Frontend**: React, Vite
- **Realtime features**: presence, typing indicators, live message delivery, friend request
  notifications
- **Voice**: real-time voice chat alongside text

## Why this matters for people learning the stack

A lot of NestJS + Socket.IO tutorials stop at "hello world" chat rooms. Dislite handles the
harder, less-documented parts: reconnect handling, channel switching without stale state,
presence across many simultaneous users, and DM access control between blocked users.

## Try it

[dislite.xyz](https://dislite.xyz), free, no install required.
