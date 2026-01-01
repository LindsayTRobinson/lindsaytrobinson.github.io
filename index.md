
~~~
<div class="Introduction">
    <p>I'm an Economics PhD student at the University of Melbourne.</p>
    <p>My research focuses on Industrial Organization & Econometrics, with application to Antitrust & Competition Policy.</p>
</div>
<div class="Papers">
    <div class="Paper">
        <div class="PaperTitle">Autonomous Algorithmic Collusion: Efficient Learning with Q-Function Approximation</div>
        <div class="PaperPublication"></div>
        <div class="PaperLinks">
            <details>
                <summary title="Show/Hide Abstract" class="PaperLink"> Abstract </summary>
                    <div class="AbstractText">
                        Autonomous algorithmic collusion occurs when firms delegate to autonomous algorithms that learn to collude with each other through repeated interaction.   
                        In this paper, I show how efficient learning algorithms can dramatically increase the speed and perfection of autonomous algorithmic collusion.
                        I consider Q-learning pricing algorithms with a parsimonious Q-function that scales linearly in the dimension of the state representation.  
                        This allows the algorithms to condition on a higher dimensional representation of the price history, and to better distinguish between temporary and sustained competitor deviation from collusive prices.  
                        The algorithms can coordinate quickly on symmetric joint-profit-maximizing collusive prices in a repeated simultaneous oligopoly pricing game.  
                        I explore the robustness of collusive prices to the algorithms' parametrization and the strategic environment, and conclude with implications for competition policy.
                    <div/>
            </details>
            <a title="Download Slides" class="PaperLink"  
                href="/assets/Slides/Algorithmic Collusion - Slides.pdf" target="_blank" rel="noopener noreferrer"> 
                Slides </a>
            <a title="View Paper on SSRN" class="PaperLink"
                href="https://doi.org/10.2139/ssrn.5981214" target="_blank" rel="noopener noreferrer"> 
                Paper </a>
        </div>
    </div>
    <div class="Paper">
        <div class="PaperTitle">Retail Demand Estimation using Public Spatial Data</div>
        <div class="PaperPublication"></div>
        <div class="PaperLinks">
            <details>
                <summary title="Show/Hide Abstract" class="PaperLink"> Abstract </summary>
                    <div class="AbstractText">
                        Demand systems describing consumer preferences over retail stores can be used to simulate the price and welfare effects of retail mergers. 
                        However, existing methods for retail demand estimation require proprietary data from non-merging firms, limiting their use by competition agencies. 
                        I propose a new methodology for estimating retail demand and simulating retail mergers using only public spatial data. 
                        The approach accomodates demographic-driven consumer preferences, endogenous store-level prices, horizontal and vertical chain differentiation and geographic store differentiation, without requiring any ex-ante ‘local market’ definition. 
                        I apply the methodology to the Australian retail grocery industry, illustrating its use in merger evaluation and remedy design.
                    </div>
            </details>
            <a title="Download Slides" class="PaperLink" 
                href="/assets/Slides/Retail Static - Slides.pdf" target="_blank" rel="noopener noreferrer"> 
                Slides </a>
        </div>
    </div>
</div>
~~~


<!---


Insert Github Repo Name
@def prepath = "reponame" 

@def title = "Lindsay Robinson"

@def hasmath = true
@def hascode = true

# Franklin syntax sandbox

This page is meant as a sandbox for Franklin Syntax so that you can quickly practice or experience things.

## Sandbox

Write whatever you want here to practice Franklin Syntax:

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```

\output{./ex1}

(yet another example that floating point arithmetics can be complicated).

$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

\newcommand{\E}{\mathbb E}

Surely some people remember the ordering, but I always forget:

$$ \varphi(\E[X]) \le \E[\varphi(X)] $$

for $\varphi$ convex. -->
