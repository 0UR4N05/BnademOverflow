# BnademOverFlow Website

This repository contains the assets required to build the [BnademOverFlow](https://bnademoverflow.com). We're glad that you want to contribute!

# Add your Self:

If you are a member and you wanna add yourself to the Official community try this :

- Add a new object to this [Speakers.json](https://github.com/BnademOverflow/BnademOverflow/blob/main/speakers.json).

```json
[
	{
		"name": "",
		"github": "",
		"twitter": "",
		"avatar": ""
	}
]
```
- And contribute to the repository 😴.
# Using this repository

You can run the website locally, or you can run it in a container runtime. We strongly recommend using the container runtime, as it gives deployment consistency with the live website.

## Prerequisites

To use this repository, you need the following installed locally:

- [npm](https://www.npmjs.com/)
- A container runtime, like [Docker](https://www.docker.com/).

Before you start, install the dependencies. Clone the repository and navigate to the directory:

```
git clone https://github.com/BnademOverflow/BnademOverflow.git
cd BnademOverflow
```

## Running the website using a container

To build the site in a container, run the following to build the container image and run it:

```
make container-image
make container-serve
```

Open up your browser to http://localhost:1313 to view the website. As you make changes to the source files, the website updates and forces a browser refresh.

# Code of conduct

Participation in the BnademOverFlow community is governed by the [Code of Conduct](https://github.com/BnademOverflow/BnademOverflow/blob/main/Code_of_Conduct.md).

# Thank you!

BnademOverFlow Thanks the community , and appreciate your contributions to our website!
