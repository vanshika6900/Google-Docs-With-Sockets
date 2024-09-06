# Google Docs with Sockets

## Overview

"Google Docs with Sockets" is a collaborative document editing platform inspired by Google Docs. This project uses WebSocket technology to enable real-time communication and collaboration among multiple users. It allows users to edit a document simultaneously, with changes being instantly reflected across all connected users' screens.

## Features

- **Real-Time Collaboration**: Multiple users can work on the same document at the same time.
- **Instant Updates**: Edits made by one user are instantly updated for all other users connected to the document.
- **WebSocket Technology**: Leveraging WebSocket for continuous, bi-directional communication between the client and server.
  
## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Real-time Communication**: WebSocket using the `socket.io` library

## Usage

1. Open the app in a web browser at `http://localhost:3000`.
2. Users can start typing in the document area.
3. Any changes made will be updated in real time across all users connected to the same document.

## WebSocket Communication

This project uses WebSocket, powered by the `socket.io` library, to handle real-time, bi-directional communication between the server and connected clients. When one user makes changes to the document, those changes are broadcast to all connected clients, ensuring that everyone sees the same content instantly.

## Future Enhancements

- **User Authentication**: Implementing user authentication to allow users to save their documents.
- **Document Persistence**: Adding database integration to store documents permanently.
- **Rich Text Editing**: Expanding the editor to support rich text features such as bold, italics, and headers.
- **Concurrent Document Editing**: Allowing users to work on multiple documents concurrently.

## Contributing

Feel free to fork the repository and submit pull requests to improve the system. Contributions are welcome!
