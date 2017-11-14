# Best practices for Telegram bots

1. Use Telegram's command system. Do not register your own "command activator" such as `!`.
2. If you do not recognize a command, don't throw an error. Group chats are likely to have multiple bots, simply fail silently.
3. Implement the start command. Let people using your bot know what you're using it for.
4. If you're listening on all chat messages, it is preferable if you opensource your project.
5. Do not send advertisements or any type of unsolicited messages
6. Implement inline features as much as possible. Users might want to use your bot while not allowing it to be in their chat all the time.