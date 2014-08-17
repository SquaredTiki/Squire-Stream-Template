# EZTV Squire Streams

<img src="https://s3.amazonaws.com/Squire_Contents/sites+resources/github+streamers/stream_icon.png" width="108" height="108" alt="Squire Stream Icon"/>

- [Squire Site](http://www.squireapp.com)
- [Squire Stream Site](http://squireapp.com/streams/)

## Overview
Streams is a [Squire](http://www.squireapp.com) feature that lets the user watch content available outside of their hard drive. This means a stream is an ordered collection of items that can be watched in Squire. Each stream is encapsulated in an ```stm``` file. ```stm``` files are added to the Squire Helper which then extracts, orders and organizes the contents for the stream so they can be enjoyed from any available Squire client. The format for these files is open and this document explains how to properly create them.

## What's this? 
This repository contains 2 streams which make use of the EZTV (torrent tracker) API. The first EZTV-Mythbusters loads Mythbusters episodes and displays them in Squire and the second loads all shows from EZTV and displays them in Squire. For the EZTV 'all shows' plugin, a remote server keeps track of all available episodes from shows and updates every 30 minutes. The stream on your Mac simply requests this JSON and this is passed onto Squire — this avoids performance issues. 

## Installation
Download or clone this repository and double click on the .stm of your choice. The stream will be added automatically to Squire Helper. After a few minutes, the stream’s content will be available in the 'Shows' section on Squire.app. (**NB: At present 'Shows' streams are not available in the present version of Squire, currently in beta**)