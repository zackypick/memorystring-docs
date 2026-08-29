# MCP Server

Control MemoryString from an MCP-capable agent **while the app is open**. The server does not start until you enable it. It listens only on this Mac (`127.0.0.1`).

**MemoryString → MCP Server** (**⌘,**).

![Enable MCP Server, Port, Copy Client Config, access token](../.gitbook/assets/mcp-settings.png)

## Turn it on

1. Launch MemoryString.
2. Open **MCP Server**.
3. Turn on **Enable MCP Server**.
4. Click **Copy Client Config**.
5. Paste the snippet into Claude, Cursor, or a similar client as a Streamable HTTP server.

Closing MemoryString disconnects the client.

Default **Port** is **18765**. If status shows the port is already in use, pick another number.

## Token

Every request needs the Bearer token shown here. MemoryString creates one on first launch so **Show** / **Copy** work even before you enable the server.

**Regenerate Token…** replaces the secret — existing client configs stop working until you paste the new snippet. The token is stored on this Mac (Application Support), not in the project file.

**MemoryString → Reset All Settings…** turns the MCP server **off**. The token file is kept.

## What the client can do

Call **get_state** first. Then, among other tools: **help**, **document**, **library**, **groups**, **transitions**, **style**, **media_edit**, **captions**, **intro**, **timing**, **audio**, **output**, **export_movie**, **playback**.

Help and About windows are not exposed as UI; use the **help** tool to read topics.

Destructive **delete** requires confirmation. Untitled work is not thrown away unless you save first or discard unsaved.

In-app Help topic **MCP Server** lists the same tools in more detail.
