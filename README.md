# 346-h3-threads-and-synchronization-in-java-solved
**TO GET THIS SOLUTION VISIT:** [346 H3 threads and synchronization in Java Solved](https://www.ankitcodinghub.com/product/346-h3-threads-and-synchronization-in-java-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;102139&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;346 H3  threads and synchronization in Java Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>Objective</h1>
<ul>
<li>To understand thread synchronization problems (safety)</li>
<li>To use the java framework for concurrency and understand the basic mechanisms for thread synchronization provided by it</li>
<li>To use synchronized methods to solve problems</li>
</ul>
<h1>Preparation</h1>
<ul>
<li>Download the code for the too much milk problem from moodle</li>
<li>Import the project into IntelliJ (or your framework of preference) and run</li>
<li>Eventually, you will run into the Too Much Milk! Problem</li>
<li>Read the synchronization section from the Java Tutorial <a href="https://docs.oracle.com/javase/tutorial/essential/concurrency/sync.html">https://docs.oracle.com/javase/tutorial/essential/concurrency/sync.html</a></li>
</ul>
&nbsp;

<h1>Tasks</h1>
<ol>
<li>To solve the too much milk problem you need to use the keyword synchronized. Identify whether it is the method (<a href="https://docs.oracle.com/javase/tutorial/essential/concurrency/syncmeth.html">https://docs.oracle.com/javase/tutorial/essential/concurrency/syncmeth.html </a>) or an object (<a href="https://docs.oracle.com/javase/tutorial/essential/concurrency/locksync.html">https://docs.oracle.com/javase/tutorial/essential/concurrency/locksync.html</a>) that needs to be synchronized on. When running the code, you should see that the execution continues without facing the too much milk problem.</li>
</ol>
&nbsp;

<ol start="2">
<li>Write the code to solve the following problem:</li>
</ol>
&nbsp;

You have been hired to coordinate people trying to cross a river. There is only a single boat, capable of holding at most three people. The boat will sink if more than three people board it at a time. Each person is modeled as a separate thread, executing the function below:

Person(int location)

// location is either 0 or 1;

// 0 = left bank, 1 = right bank of the river

{

ArriveAtBoat(location); BoardBoatAndCrossRiver(location); GetOffOfBoat(location);

&nbsp;

}

&nbsp;

Synchronization is to be done in the two methods ArriveAtBoat and GetOffOfBoat. Provide the code for ArriveAtBoat and GetOffOfBoat. ArriveAtBoat must not return until it safe for the person to cross the river in the given direction (it must guarantee that the boat will not sink, and that no one will step off the pier into the river when the boat is on the opposite bank). GetOffOfBoat is called to indicate that the caller has finished crossing the river; it can take steps to let other people cross the

&nbsp;

&nbsp;

river.

BoardBoatAndCrossRiver returns the location where the person gets off boat and is passed to the getOffOfBoat.

&nbsp;

Simulate 20 persons at location 1 trying to cross to location 0 at the same time and show that they are safely crossed. Use print statements to show the simulation steps.

&nbsp;

<h1>Further reading</h1>
If you want to learn about thread programming in C/C++ (POSIX Threads) <a href="https://concordiauniversity.on.worldcat.org/oclc/137284099">https://concordiauniversity.on.worldcat.org/oclc/137284099</a>
