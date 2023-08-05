# AI 
## AI's Assignments and Exams in Sesssion Sp-2023 

## 1. The Minimax algorithm
The Minimax algorithm is a relatively simple algorithm used for optimal decision-making in game theory and artificial intelligence. Again, since these algorithms heavily rely on being efficient, the vanilla algorithm's performance can be heavily improved by using alpha-beta pruning.

## 2.  Alpha-Beta Pruning

Alpha–beta is an improved minimax using a heuristic. It stops evaluating a move when it makes sure that it's worse than previously examined move. Such moves need not to be evaluated further.

When added to a simple minimax algorithm, it gives the same output, but cuts off certain branches that can't possibly affect the final decision - dramatically improving the performance.

The main concept is to maintain two values through whole search:

* Alpha: Best already explored option for player Max
* Beta: Best already explored option for player Min

Initially, alpha is negative infinity and beta is positive infinity, i.e. in our code we'll be using the worst possible scores for both players.

This method allows us to ignore many branches that lead to values that won't be of any help for our decision, nor they would affect it in any way.

With that in mind, let's modify the min() and max() methods from before in a derived class inherited from the previous Game class 
 
## Comsats University Islamabad, Abbottabad Campus


#### Feel Free to Use :)