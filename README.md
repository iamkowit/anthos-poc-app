# anthos-poc-app

Cloud provider POC project

## Quick Start

[![](https://mermaid.ink/img/eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gICAgcGFydGljaXBhbnQgVXNlclxuICAgIHBhcnRpY2lwYW50IEJhY2tlbmQxXG4gICAgcGFydGljaXBhbnQgQmFja2VuZDJcblxuICAgIHJlY3QgcmdiKDI1NSwyMjgsMjI1KVxuICAgIE5vdGUgb3ZlciBVc2VyLEJhY2tlbmQyOiBCYWNrZW5kMSBhcyBhIHByb3h5IHNlcnZlclxuICAgIFVzZXItPj4rQmFja2VuZDE6IEdFVCAvY2FsY3VsYXRvci9maWJvLzVcbiAgICBCYWNrZW5kMS0-PitCYWNrZW5kMjogUlBDIENhbGN1bGF0b3JTZXJ2aWNlLkZpYm9uYWNjaSg1KVxuICAgIHJlY3QgcmdiKDI1NSwyMTgsMTg1KVxuICAgIE5vdGUgb3ZlciBCYWNrZW5kMjogQ2FsY3VsYXRlIGZpYm9uYWNjaVxuICAgIGVuZFxuICAgIEJhY2tlbmQyLS0-Pi1CYWNrZW5kMTogNVxuICAgIEJhY2tlbmQxLS0-Pi1Vc2VyOiA1XG4gICAgZW5kXG5cbiAgICByZWN0IHJnYigyNTUsMjI4LDIyNSlcbiAgICBOb3RlIG92ZXIgVXNlcixCYWNrZW5kMjogRGlyZWN0bHkgc2VuZCBhIEhUVFAgcmVxdWVzdCB0byBCYWNrZW5kMlxuICAgIFVzZXItPj4rQmFja2VuZDI6IEdFVCAvY2FsY3VsYXRvci9maWJvLzVcbiAgICByZWN0IHJnYigyNTUsMjE4LDE4NSlcbiAgICBOb3RlIG92ZXIgQmFja2VuZDI6IENhbGN1bGF0ZSBmaWJvbmFjY2lcbiAgICBlbmRcbiAgICBCYWNrZW5kMi0tPj4tVXNlcjogNVxuICAgIGVuZCIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoic2VxdWVuY2VEaWFncmFtXG4gICAgcGFydGljaXBhbnQgVXNlclxuICAgIHBhcnRpY2lwYW50IEJhY2tlbmQxXG4gICAgcGFydGljaXBhbnQgQmFja2VuZDJcblxuICAgIHJlY3QgcmdiKDI1NSwyMjgsMjI1KVxuICAgIE5vdGUgb3ZlciBVc2VyLEJhY2tlbmQyOiBCYWNrZW5kMSBhcyBhIHByb3h5IHNlcnZlclxuICAgIFVzZXItPj4rQmFja2VuZDE6IEdFVCAvY2FsY3VsYXRvci9maWJvLzVcbiAgICBCYWNrZW5kMS0-PitCYWNrZW5kMjogUlBDIENhbGN1bGF0b3JTZXJ2aWNlLkZpYm9uYWNjaSg1KVxuICAgIHJlY3QgcmdiKDI1NSwyMTgsMTg1KVxuICAgIE5vdGUgb3ZlciBCYWNrZW5kMjogQ2FsY3VsYXRlIGZpYm9uYWNjaVxuICAgIGVuZFxuICAgIEJhY2tlbmQyLS0-Pi1CYWNrZW5kMTogNVxuICAgIEJhY2tlbmQxLS0-Pi1Vc2VyOiA1XG4gICAgZW5kXG5cbiAgICByZWN0IHJnYigyNTUsMjI4LDIyNSlcbiAgICBOb3RlIG92ZXIgVXNlcixCYWNrZW5kMjogRGlyZWN0bHkgc2VuZCBhIEhUVFAgcmVxdWVzdCB0byBCYWNrZW5kMlxuICAgIFVzZXItPj4rQmFja2VuZDI6IEdFVCAvY2FsY3VsYXRvci9maWJvLzVcbiAgICByZWN0IHJnYigyNTUsMjE4LDE4NSlcbiAgICBOb3RlIG92ZXIgQmFja2VuZDI6IENhbGN1bGF0ZSBmaWJvbmFjY2lcbiAgICBlbmRcbiAgICBCYWNrZW5kMi0tPj4tVXNlcjogNVxuICAgIGVuZCIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)

`backend1` serves a RESTful API, that acts as a proxy server. It forwards requests to `backend2` via gRPC protocol.

`backend2` serves both RESTful API and gRPC service. Instead of fowarding, it executes the requests.

```sh
git submodule init
git submodule update

docker-compose up
```
