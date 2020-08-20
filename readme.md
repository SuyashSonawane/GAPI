# GAPI - Simplified Github API

Lets you query api.github.com easily

## Getting Started

Add this script to your html file 

```
<script src="https://cdn.jsdelivr.net/gh/suyashsonawane/gapi/main.js"></script>
```

## Usage

First initialize the GAPI object by passing the username.

```
let gp = new GAPI("suyashsonawane")
```

Getting user data

```
let userData = await gp.getUser()
```
Getting user's repository's data by passing repo name

```
let repoData = await gp.getRepo("GAPI")
```

# More functions will be added soon
