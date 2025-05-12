# ee2003-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [EE2003 # Assignment 2 Solved](https://www.ankitcodinghub.com/product/ee2003-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90775&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE2003 # Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
# Assignment 2

Simple assembly language programming for the RISC-V

## Goals

– Demonstrate basic working knowledge of RISC-V assembly

## Given

– Test bench assembly code for Fibonacci number

– Some test cases

– Template code that you can use to fill in

## Details on the assignment

### Fibonacci series

The Fibonacci series is a well known sequence of numbers that follows the pattern that the *n*th number is the sum of the previous two numbers. This is usually represented in a recursive manner as follows (shown below for Python, similar representations for other languages):

“`python

def fib(n):

if (n==1) or (n==2):

return 1

else:

return fib(n-1) + fib(n-2)

“`

For coding this in Assembly language, you may want to think about how to rewrite this without recursion, since writing recursive programs in Assembly, while not impossible, is not very pleasant.

### Test cases

You are given a test bench that will call a function written by you with different input values. The parameter *n* (number in the sequence to compute) is given in the register `a0`, and you are required to return the computed value also in `a0`. It is up to you how you handle saving intermediate values in your function, or whether you even retain them at all.

## HowTo

Fork this repostiry (`EE2003/a2`) into your namespace so that you can edit and push changes.

The `run.sh` script performs all the steps required to compile and test your code. It assumes the RISCV toolchain is installed in a certain path as set up on the Jupyter server for the course. If you install on your own system you need to make the appropriate settings.

**IMPORTANT**: do not rename files or create new files – otherwise the auto-grader will not recognize it. Even if you change the `.drone.yml` file, the system will repeat the tests with different configuration files, and your changes will most likely not be recognized then.

0
