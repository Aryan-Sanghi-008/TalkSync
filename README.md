# [TalkSync](talk-sync-ten.vercel.app/)

TalkSync is a disposable chat-room which supports multiple devices and works with real time channels for instant communication.
It has been tested for latency across the planet (using TOR network) and still works with a max latency of around `44ms`.

- **Base usage:** Initiate a chat room which can be used by over 200 people at the same time around the planet.
- **Why this:** Literally less than 5 seconds required to create a private mailing list and start texting your mates.
- **Clean UI:** The app uses [Chakra UI](https://chakra-ui.com/) for a clean interface.
- **Dispose with refresh:** To dispose a room, the last user has refresh the page once which removes chats from the network.
- **No strings attached:** Texts sent over the web app, your name, every bit of conversation, nothing is ever stored.
- **Low latency:** Less than `100ms` of total end-points connection time tested for servers across the planet.
- **Fast servers:** Hosted on scalable, lightening fast servers by [Render.com](https://render.com).

<div align="center">
  <img src="https://cdn.statically.io/gh/thatsameguyokay/images/main/fortlax.png">
</div>

## Installation

Follow the steps to get started. **You can use as little or as much React as you need**:

- Fork and clone [this](https://github.com/Aryan-Sanghi-008/TalkSync) repository to make an instant copy of the content.
- Alternatively, you can download the source and set it up with Github Desktop.
- Open the root folder in the code editor of your preference, and run the following commands:

```
 npm install
 npm start
```

The server is configured in [SocketContent.js](https://github.com/Aryan-Sanghi-008/TalkSync/blob/main/src/socketContext.js).

## to-do

Configure the `server` directory to use local proxy through the application, instead of providing an open-to-all API.

## Documentation

Check out the [Getting Started](https://reactjs.org/docs/getting-started.html) page for a quick overview of the project structure.

You can improve it by sending pull requests to [this repository](https://github.com/Aryan-Sanghi-008/TalkSync).

## Contributing

The main purpose of this repository is to continue evolving React core, making it faster and easier to use. Development of React happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements. Read below to learn how you can take part in improving React based apps.

### Code of Conduct

TalkSync has adopted a Code of Conduct that we expect project participants to adhere to. Please read [the full text](https://code.fb.com/codeofconduct) so that you can understand what actions will and will not be tolerated.

### Contributing Guide

Read the React's [contributing guide](https://reactjs.org/contributing/how-to-contribute.html) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React, or overall MERN.

Raise an issue [here](https://github.com/Aryan-Sanghi-008/TalkSync/issues).

### Good First Issues

To help you get your feet wet and get you familiar with our contribution process, we have a list of [good first issues](https://github.com/Aryan-Sanghi-008/TalkSync/labels/good%20first%20issue) that contain bugs which have a relatively limited scope. This is a great place to get started <3.

### License

TalkSync is [MIT licensed](./LICENSE).
