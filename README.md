# cs305-programming-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CS305 Programming Assignment 2 Solved](https://www.ankitcodinghub.com/product/cs305-programming-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116225&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS305 Programming Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Use python to implement a simple だんま(danmaku) system.

Introduction

Danmaku is a popular form of comment. When watching videos or live shows, you can send a danmaku on the certain timestamp or in real-time. Generally, you will see your danmaku flying from one side of the screen to the other side (e.g., right to left).

In this assignment, you will need to implement a simple danmaku system of TWO VERSIONS, using HTTP protocol and WebSocket protocol (WS in short). respectively. You will also need to compare the two protocols.

For more details, click www.bilibili.com/video/BV1GJ411x7h7 to find more.

NOTES

(1) We have provided a skeleton for both versions. You can complete your codes based on them. However, you are free to design your own frameworks.

(3) In HTTP version, we recommend to run your server on ‘127.0.0.1’ and port is 8765, so that you can connect to the server by accessing “127.0.0.1:8765” on your web browser.

(4) You MUST provide sufficient comments for us to understand your programs.

(5) Please upload your programs together with a REPORT that describes your designs, running result screenshots, and analysis conclusions.

Environment

Python 3.8

Recommended extra libraries are HTTP and websockets

Implementation details

1. In WS version, the danmaku server runs on port 8765 and IP address is 127.0.0.1 as recommended, and it should be able to:

Listen and accept WS messages.

Receive danmakus from clients, and send them to all clients and display them on their screens. We will test your program with at least 3 clients, i.e., on at least 3 browser tabs.

2. In HTTP version，the danmaku server also runs on port 8765 and IP address is 127.0.0.1 as recommended, it should:

Listen on 8765 and accept HTTP requests, including POST and GET requests. Please see the skeleton we provide.

Receive danmakus from POST requests. Your clients should send GET requests at regular intervals to get new danmakus and show them on the screen. Make sure that all danmakus not retrieved are sent correctly to each clients.

3. In the given demo, we use a python file as a server and a html file as a client for WS. You can run server.py and open html file in a browser to see the base part and create your code on it. For HTTP version, a Python skeleton is given and you can run it and open

‘127.0.0.1:8765′ on your browser to see the constructed page. Just focus on the codes which handle GET and POST requests. You are allowed to implement the systems without using the skeletons, as long as you describe it clearly in your report.

4. Danmakus on videos and live stream (20 as bonus).

Design a better system which can fit videos and live stream. For the bonus points, you can implement it with either WS or HTTP protocol.

For videos, you need to record the timestamp so that next we watch the video we can find our danmakus again.

Figure 1 Videos mode (example)

For live stream, you need to implement a danmaku list to see what is talking about now. You don’t need to focus much on users’ name and live contents, just distinguish different sockets.

Figure 2 Live mode (example)

5. For videos, using a list to record received danmakus, a local file is recommended.

Grading policy

1. Tasks

Basic part (90, 50% for HTTP version and 50% for WS version)

Report (10)

Danmakus on videos and live stream (20 as bonus)

2. Report contents

The designs of your system, a system diagram is encouraged.

The running results, not limited to screenshots.

Analytical conclusions about the difference of the two protocols. You can analyze from the design diagram, network traffic, upgrade efficiency, and any other aspects.

Test details

1. Correctness: we will test your program to see:

Whether danmakus are correctly sent and appear simultaneously on each client. Whether HTTP and WS messages are captured.

2. Validity: we will look through your program to make sure that you use the corresponding protocols.

3. For bonus points, we will check whether all danmakus were stored. If you implement video and live mode, show them clearly so that we can recognize them.

What to submit

You should submit your programs and report. Any other files needed should also be zipped for submission. Put the two versions of systems in two separated file folders.

Please comment in your code to explain different parts of your code. You need to at least illustrate in your implementation about every part.
