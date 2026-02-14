# YouTube API & MCP Sandbox
This is an API sandbox for the YouTube API & MCP Sandbox, using an OpenAPI specification with examples, Microcks and Bruno as the sandbox interface, and this GitHub repository as the vehicle for delivering a localized sandbox.

## APIs.json
There is an APIs.yml file in the root of this repository, providing an index of all the artifacts used as part of this API sandbox, providing a machine-readable way to read, manage, and execute the sandbox available here.

## OpenAPI
This sandbox uses OpenAPI as the definition, providing [a complete definition of all available paths for the YouTube API & MCP Sandbox. The OpenAPI for this sandnbox uses examples and Microcks extensions to mock the requests and responses for each API operation, something we will iterate and expand upon with richer examples as we move forward.

## Microcks
This sandbox uses Microcks to deliver the mock API. [You just install Microcks, with the Docker extension being the easiest](https://microcks.io/documentation/guides/installation/docker-desktop-extension/), [import the OpenAPI as a service](openapi/notion-openapi.yml), and you have a mocked API for all APIs, available via REST and MCP APIs--providing a multi-protocol sandbox.

## Bruno
This sandbox [uses Bruno as the client](https://www.usebruno.com/), leveraging Bruno Collections pre-generated from the OpenAPI and Bruno environments that uses the localhost and port of Microcks to work with the mocked API. You just have to install Microcks, then open the collection provided in this repository, select the available environment, and begin calling the YouTube API & MCP Sandbox via the sandbox.

## Summary
This is a summary of this sandbox, breaking down the available paths, operations, and other relevant detail regarding the scope of this sandbox, designed to support development and testing against the YouTube API & MCP Sandbox.

- Number of Paths: 17
- Number of Operations: 27
- Number of Read Operations: 12
- Number of Write Operations: 15
- Number of Schemas: 64
- Number of Responses: 0
- Number of Parameters: 52
- Number of Examples: 36
- Number of Request Bodies: 0
- Number of Headers: 0

## OpenAPIs
These are the OpenAPIs available for the YouTube API & MCP Sandbox, which are made available via this sandbox API, which can be imported into Microcks and deployed as a sandbox using their mock feature.

  - [Youtube Analytics Api](openapi/youtube-analytics-openapi-original.yml)
  - [Youtube Data Api](openapi/youtube-data-openapi-original.yml)

## Resources
These are the resources available via the YouTube API & MCP Sandbox, which are made available via this sandbox API, which are applied as tags to each operation in the OpenAPI.

  - Analytics Groups
  - Analytics Reports
  - Captions
  - Channels
  - Comments
  - Group Items
  - Playlist Items
  - Playlists
  - Search
  - Subscriptions
  - Videos

## Operations
These are all of the available operations in this sandbox, providing a complete view of what you can do within this sandbox using the mocked YouTube API & MCP Sandbox.

  - Add Item To Group
  - Add Item To Playlist
  - Create Analytics Group
  - Create Playlist
  - Delete Analytics Group
  - Delete Playlist
  - Delete Video
  - Get Analytics Group
  - List Analytics Groups
  - List Channel Resources
  - List Comment Threads
  - List Group Items
  - List Playlist Items
  - List Playlists
  - List Subscriptions
  - List Video Captions
  - List Video Resources
  - Remove Item From Group
  - Remove Item From Playlist
  - Retrieve Youtube Analytics Reports
  - Search Youtube Content
  - Subscribe To Channel
  - Unsubscribe From Channel
  - Update Analytics Group
  - Update Playlist
  - Update Video Metadata
  - Upload Video

## Backstage
We provide a Backstage software catalog entity for the YouTube API & MCP Sandbox, allowing this sandbox to be registered with any catalog, making it discoverable by team and across an organization--allowing anyone to fork and deploy locally within the enterprise.

  - [Youtube Analytics API](backstage/youtube-analytics-backstage-original.yml)
  - [Youtube Data API](backstage/youtube-data-backstage-original.yml)
## Support
Please provide any questions or feedback via GitHub issues, or just email kinlane@naftiko.io with feedback. The goal is to keep iterating upon this sandbox using existing OpenAPI, Microcks, and Bruno features, offering value out of the box via this forkable third-party YouTube API & MCP Sandbox.

