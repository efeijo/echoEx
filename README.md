# Challenge #1: Echo

A series of distributed systems challenges brought to you by Fly.io.

Our first challenge is more of a “getting started” guide" to get the hang of working with Maelstrom in Go. In Maelstrom, we create a node which is a binary that receives JSON messages from STDIN and sends JSON messages to STDOUT. You can find a full protocol specification on the Maelstrom project.

We’ve created a Maelstrom Go library which provides maelstrom.Node that handles all this boilerplate for you. It lets you register handler functions for each message type—similar to how http.Handler works in the standard library.
