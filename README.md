# cs140-project-solved
**TO GET THIS SOLUTION VISIT:** [CS140 Project Solved](https://www.ankitcodinghub.com/product/cs140-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95460&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS140 Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Project Objective

The project aims at design and simulation of a mechanical converter that converts binary representation of a number into its value in the decimal numeral system. The input consists of 8 signals representing bits – 1 if a signal is recorded, and 0 – if the signal is missing. The device generates a spring oscillation the frequency of which corresponds to the magnitude of the recorded input.

Task 1

Write a class Spring that implements the concept of a 1D massless spring and, hence, encapsulates its stiffness double k with the default value equal 1. Add the following methods:

<ol>
<li>The default constructor and an overloaded constructor that specifies the stiffness.</li>
<li>The public getter and a private setter;</li>
<li>Overloaded public move() methods that return an array of coordinates of an oscillating
mass:

<ul>
<li>– &nbsp;double[] move(double t, double dt, double x0, double v0) – a body of unit mass
oscillates during a period double t starting from t = 0 with initial conditions x(0) =

x0 and v(0) = v0. The coordinate is computed per each double dt time step;
</li>
<li>– &nbsp;double[] move(double t, double dt, double x0) – a body of unit mass oscillates during a period double t starting from t = 0 with initial conditions x(0) = x0 and
v(0) = 0. The coordinate is computed per each double dt time step;
</li>
<li>– &nbsp;double[] move(double t0, double t1, double dt, double x0, double v0) – a body of unit mass oscillates from t = t0 till t = t1 with initial conditions x(t0) = x0 and v(t0)
= v0. The coordinate is computed per each double dt time step;
</li>
<li>– &nbsp;double[] move(double t0, double t1, double dt, double x0, double v0, double m) – a body of a specified mass double m oscillates from t = t0 till t = t1 with initial conditions x(t0) = x0 and v(t0) = v0. The coordinate is computed per each double
dt time step;

Task 2
</li>
</ul>
</li>
</ol>
1. Continue with the class Spring and add the following public methods:

<ul>
<li>– &nbsp;Spring inSeries(Spring that) – takes by reference a Spring that argument, connects it with this Spring in series and returns a new Spring object that represents the
equivalent spring;
</li>
<li>– &nbsp;Spring inParallel(Spring that) – takes by reference a Spring that argument,
connects it with this Spring in parallel and returns a new Spring object that represents the equivalent spring;
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. Write a class SpringArray and implement the following public static methods:

<ul>
<li>– &nbsp;Spring equivalentSpring(String springExpr) – takes a String expression that represents connections of springs of unit stiffness and returns the equivalent spring. The Spring springExpr is a valid expression of balanced braces {} and brackets []. Empty brackets without nested braces and brackets represent a single spring of unit stiffness. Brackets with nested braces and brackets represent springs connected in parallel. Braces with nested braces and brackets represent springs connected in
series.
</li>
<li>– &nbsp;Spring equivalentSpring(String springExpr, Spring[] springs) – takes a String
expression that represents connections of springs specified by a Spring array Spring[] springs and returns the equivalent spring.

Task 3

Write a class FT that implements the concept of Fourier transform / series. It transforms an array of coordinate values at different time moments into an array of the amplitudes of harmonic oscillations. Declare member variables and implement methods as needed.

Task 4

Write a class Converter that aims at conversion of a binary representation of a single byte into its decimal value. Consider a sequence of 8 bits and design a system of springs that implements each of them.
</li>
</ul>
<ul>
<li>– &nbsp;Add a method that takes as its argument a sequence of 8 binary digits and adds connects the corresponding spring systems into a general system.</li>
<li>– &nbsp;Add a method that connects to the obtained system of spring a body of unit mass and computes its oscillations.</li>
<li>– &nbsp;Add a method that calculates the frequency amplitudes of the oscillations using the implemented Fourier transform.</li>
<li>– &nbsp;Add a method that determines the decimal value of the original binary sequence using the computed frequency amplitudes.</li>
</ul>
</div>
</div>
</div>
