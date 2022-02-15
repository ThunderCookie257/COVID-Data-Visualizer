# COVID-Data-Visualizer
This is my COVID-19 data visualizer, done as part of NW Hacks 2022

Seeing as this is built in Java, I used JPanels and JFrames to construct the different parts of the animation.
The goal is to generate a spiral chart animation of given COVID data.
What I decided to do is to generate a static image of a graph and lay that as the background of the JFrame.
Then, I used an additional JPanel overlayed on top of it that animates an expanding transparent circle from the center.
By far the most difficut part of this project was to get the circle to expand correctly from the center and reveal the JPanel below.
The resulting effect is a spiral chart animation... but the way it works under the hood is quite different than one would expect. 
