# Spotify_API_Testing

## Introduction
In the following project, I create and execute a suite of test scripts that interact with Spotify's API. These scripts encompass a range of testing scenarios, including data validation, authentication, and performance testing.

## Purpose
My goal is to ensure that the API functions seamlessly, adheres to Spotify's documentation, and meets the high standards of data integrity and security.

## Project Structure
In this repository you will find a ".json" file which can be run using POSTMAN or NEWMAN.
Further I will explain how it is structured.

This project is organized as follows:
- "artists" directory: contains requests regarding Artists (i.e. "get artist" , " follow artist" , "get artist albums", etc);
  - equivalence partioning directory: which contains two directories: - positive testing: conducting tests using valid data and following specific API instructions;
                                                                      - negative testing: conducting tests using invalid data;
- "playlists" directory: contains requests regarding Playlists (i.e. "get playlist" , " follow playlist" , "create playlist", etc);
  - equivalence partioning directory: which contains two directories: - positive testing: conducting tests using valid data and following specific API instructions;
                                                                      - negative testing: conducting tests using invalid data;

## Testing Software Used:
- Postman;
- Newman.

## Installation
For postman you have two options:
- install the Postman application;
- use https://www.postman.com/ website to run the tests.

To install postman:
- go to https://www.postman.com/ ;
- choose your platform;
- download the app, then install it.

## Running the Project
!! SEE IMPORTANT FOR THE TOKEN.
  - log in;
  - import the ".json" file from this repo;
  - click on the "SPOTIFY_API" collection, then click on "Run";
  - on the newly opened "Runner" tab, click "Run Spotify_API";
  - now all the tests are being ran and you can see the results.

## IMPORTANT
If running the project using Postman, you will need to generate a token:
- go to "Spotify_API" collection;
- click on "Authorization";
- scroll all the way down until you see "Get New Access Token";
- click on "Get New Access Token";
- a pop up will appear;
- if you are asked for credetials, use the following e-mail "andreispotifytest8@gmail.com" and the following password "Spotifypassword#1"
- use this token now;
- refresh the token when needed.
