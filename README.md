# python-web-binary
This is simply a binary for serving a web via Flask on `PORT` environment variable (default 8080).

It will serve `"The service is up"` string on `/` URL path

## Why do you need this?
There are some cases where my project needs an accessible public URL and the served content doesn't really matter. Installing some dependencies for that is exhausting, so a binary that can be easily run is a life saver.

## How to run this?
1. Give the permission to execute with `chmod +x web` (optional, only do this when it gives you `permission denied` error)
2. Run the binary with `./web` (only Linux will work)
