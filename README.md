## No updates/fixes until October 2025 

# m3u8-proxy

Join the [discord](https://discord.gg/88ArBFRcY8) for support

`m3u8-proxy` is a TypeScript-based proxy server that serves M3U8 playlist files. It is designed to be lightweight, easy to deploy, and efficient for streaming purposes.

# List of free instances

I run a few free instances of this proxy server. You can use them for free. Here are the links:

[Koyeb](https://renewed-georgeanne-nekonode-1aa70c0c.koyeb.app/), You can also deploy your own instance on Koyeb by clicking the button below.

## Note

This proxy will work for most M3U8 files, but it may not work for all. If you encounter any issues, please open an issue on this repository.

## Features

- **Serve M3U8 files**: Acts as a proxy server to handle and serve M3U8 files, ensuring smooth streaming experiences.
- **Easy Deployment**: Quickly deployable to cloud platforms such as Koyeb.
- **TypeScript**: Written in TypeScript for robust type safety and maintainability.
- **Lightweight**: Minimal dependencies to keep the project fast and responsive.
- **Efficient**: Designed to be efficient for streaming purposes.

## Try it out

You can try out the proxy by making a request to the following URL:

```
https://renewed-georgeanne-nekonode-1aa70c0c.koyeb.app/fetch/?url=https://example.com/playlist.m3u8
```

Using this for Images:

```
https://renewed-georgeanne-nekonode-1aa70c0c.koyeb.app/fetch/image?url=https://upload.wikimedia.org/wikipedia/commons/b/b6/Image_created_with_a_mobile_phone.png
```

# Note

You can use it to view website but you will not be able to view the js, css, svg, etc. files within the website.

## Deployment 

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=simple-proxy&type=git&repository=DeveloperJosh/m3u8-proxy&branch=main&env[PORT]=3000&ports=3000;http;/&builder=dockerfile)
