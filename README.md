# LimpDB

A minimal web interface for searching and downloading game files from the LimpDatabase repository.

## What it does

LimpDB lets you search for a game by name or Steam App ID and download its associated ZIP file if one is available.
It pulls game metadata directly from the Steam store API and checks file availability against the LimpDatabase GitHub repository.

## Features

- Search by game name or Steam App ID
- Live autocomplete powered by the Steam store search API
- Instant availability check — download link only appears if the file exists
- Blob-based downloads — source URL is never exposed to the user
- ZIP count in the top left, refreshed every minute using the GitHub Git Trees API (no 1000-file cap)
- Clean minimal dark UI, fast on both desktop and mobile
