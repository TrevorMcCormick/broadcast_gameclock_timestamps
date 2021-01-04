# broadcast_gameclock_timestamps
Uses OCR to provide exact broadcast timestamps given on-screen game-clock times.

## Status
This project is not yet complete.

## Background
This project is the beginning of a product that aims to solve a broad problem in sports, concerning coaches, scouts, video coordinators, analysts, journalists, and avid fans. These experts spend a massive amount of time after each game doing three things: watching recordings of the game's broadcast, segmenting the broadcast video into smaller clips, and organizing those clips into meaningful categories that can be shared with others. Millions of dollars is spent each year executing those three tasks. 

There are certainly successful companies that build tools to simplify these three tasks: Second Spectrum and Playsight, to name two of the market leaders. These companies have built groundbreaking solutions for sports with motion-tracking cameras. It may seem like a daunting task to enter this market, which is guarded by a significant barrier of entry with commercial hardware. However, this project is built upon the belief that expensive hardware is not required to meet the needs of most of the market. We believe that simple broadcast video, combined with an easy-to-use web application, can eliminate nearly all of the manual hours spent wathing, editing, and organizing broadcast game film. 

## What this project does
This repo focuses on the first step of building a web app to automatically break down game film. Simply put, it takes an input of a broadcast video from any sport, and it outputs a two-column table that correlates the time on the game clock with the timestamp of the broadcast. 

## How this project works
Currently testing with Keras.
