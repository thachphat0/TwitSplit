# TwitSplit

## Screens
- [x] Messages

## Features
- [x] Post message
- [x] View old messages
- [x] Split message if needed
- [x] Test split message

## Split message logic:
- [x] If a user's input is less than or equal to 50 characters, post it as is.
- [x] If a user's input is greater than 50 characters, split it into chunks that each is less than or equal to 50 characters and post each chunk as a separate message.
- [x] Messages will only be split on whitespace.
- [x] If the message contains a span of non-whitespace characters longer than 50 characters, display an error. 
- [x] Split messages will have a "part indicator" appended to the beginning of each section. In the example above, the message was split into two chunks, so the part indicators read "1/2" and "2/2". Be aware that these count toward the character limit.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details