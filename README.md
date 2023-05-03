# beatsbyishan

## Intro
This project is a web application that lets one play different drum beats and control the tempo using their hands.

## How to use
Go this link https://ishan710.github.io/beatsbyishan/ then right click and inspect element and open console.
Now if see this, you are good to go.
<img width="1788" alt="Screen Shot 2023-04-17 at 1 42 26 PM" src="https://user-images.githubusercontent.com/12728004/232581209-2e844760-5646-4fd5-9127-969944431eab.png">

If not, please refresh the page again and wait till the time the hand gesture detector is ready. 

After that. Press start.

Press keys 1,2,3 to add beats. You can enter beats in any order and in any quantity. 

Press key 0 to stop.

Raise right hand to increase tempo
Raise left hand to decrease tempo

## Troubleshooting
Sometimes the hand-gesture tempo control doesn't work, for that please reload the page for the Tensorflow API to load. 

## Reflection!
Creating a website that allows users to play their beats and adjust tempo using computer vision was an interesting and challenging project. The creative process involved identifying the key requirements for the project and figuring out how to implement them using the available tools and technologies. One of the major technical challenges was experimenting with different hand gesture poses to figure out what works best. I had to test various hand gestures and decide on the ones that are easy to recognize and perform. This process required a lot of trial and error, and it was essential to have a good understanding of computer vision algorithms and techniques to get the best results.

Another challenge I faced during the development process was the time it took for the hand gesture model to load. Initially, the website was taking too long to respond, which could lead to a poor user experience. To address this issue, I had to add a "hack" by adding a wait statement to give the model enough time to load before it starts recognizing hand gestures. This approach worked well, and it significantly improved the performance of the website.

Overall, creating a website that lets users play their beats and adjust tempo using computer vision required a combination of creativity, technical skills, and problem-solving abilities. It was satisfying to see the project come together, and it was rewarding to see users engage with the website and enjoy the experience. This project taught me a lot about the potential of computer vision technologies and the importance of paying attention to user experience and performance when developing web applications.

