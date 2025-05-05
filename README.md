# cs384-tutorial-6-web-series-renamer-regular-expression-solved
**TO GET THIS SOLUTION VISIT:** [CS384 Tutorial 6–Web Series Renamer & Regular Expression Solved](https://www.ankitcodinghub.com/product/cs384-tutorial-6-web-series-renamer-regular-expression-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95737&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS384 Tutorial 6–Web Series Renamer \u0026amp; Regular Expression Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
A sample set of srt+mp4 is given to you in separate folders. You need to rename mp4 + srt files. You know that in VLC/any media play will auto include the srt if the filename and srt name is same.

There shall be two folders.

wrong srt – containing pre-renamed file name

corrected srt – after rename, ensure that new filenames are placed here.

You need to ask 3 inputs from the users

<ol>
<li>Initially make a menu based program that will ask which web series to rename. The sample python code I have already given along with the variables.</li>
<li>Season Number Padding (take int input): The padding given to the season number. A padding of three digits means if the series have 20 seasons then it will be renamed as season 001, 002, 003…, 019, 020.</li>
<li>Episode Number Padding (take int input): For example, a padding of two means if the series have 30 episodes then it will be renamed as episode 01, 02, …, 30</li>
</ol>
There are 3 folders that you need to rename: 1. Breaking Bad

2. Game of Thrones

3. Lucifer

Lets say the user provides these inputs:

1. Main Title of the Web Series: 2

2. Season Number Padding (take int input): 1

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. Episode Number Padding (take int input): 2

Original:: ‘Game of Thrones – 8×05 – The Bells.WEB.REPACK.MEMENTO.en.srt”

New: “Game of Thrones – Season 8 Episode 05 – The Bells.srt”

Also look, there is an interesting case: Look at one of the names:

“Game of Thrones – 8×05 – The Bells.WEB.REPACK.MEMENTO.en.srt” Original:: ‘Game of Thrones – 8×05 – The Bells.WEB.REPACK.MEMENTO.en.srt” New: “Game of Thrones – Season 8 Episode 05 – The Bells.srt”

Here you can see that ”.WEB.REPACK.MEMENTO.en” is the string that is not required. Usually every srts have common strings towards the end that needs to be identified manually and stripped. So in case of Game of Thrones, you need to find out manually such non-useful string and strip them in the final code. A recommended approach will be regex. Like splitting on the WEB and other such string (e.g., 720p). Similar manner do it for mp4 also. So both srt and mp4 will have same name and only the extensions shall differ.

Task: Based on the received input, the filename should be seriesname season number (depending on the padding) episode number (depening on the padding) + episode name ()if any).

Following series needs to be renamed (srt+mp4) via the os module.

1. Breaking Bad

2. Game of Thrones 3. Lucifer

Spaces should be strictly one between characters and numbers.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
