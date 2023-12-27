
# [Draft] The Minimal Function

In discussing the author's approach he wanted to build something
from primary concepts, and started with an analogy of the quantum action
which the author has dubbed the "Minimal Function".

For the purposes of this paper the Minimal Function is binary,
though on further exploration it has shown to be quite complex. For the
scope of this paper there is no need to dive into this complexity.

A System is where a multiple of Functions can be employed. Just as a
Function uses probability to determine its state, the same can be
applied to a System. There is no boundary between a System or a
Function, just that one defines the other, so the ``Minimal'' function
explained here can admittedly be something of a misnomer as it is
possible to reduce complex systems into simple functions as the Path
Integral famously demonstrates, this is how the minimal function was
arrived at.

The Minimal Function is a metric graph of 2 nodes with an edge
representing probability of 1. <a href="#fig1">Fig. 1</a> is a graph of the initial state:

<a name="fig1">![Initial state](./figures/fig1.svg)</a>
*Fig. 1: Initial State*

$$
\Sigma\  = \ \{ \bullet_{1}, \circ_{2}\}
$$

To represent the binary state of each node we subvert the graph
algebraic notation thus:

$$
\Sigma\  = \ \{ 1_{1},0_{2}\}\  = \ 1
$$

Once the function has operated (Figure~\ref*{fig:operated}) the system still has a total
probability of 1, but the edges have \(\frac{1}{2}\):

\begin{figure}
  \centering
  \includesvg{fig2}
  \caption{Final state}
  \label{fig:operated}
\end{figure}

$$
  {e_{a}}_{} = \ \{ 0_{1},1_{2}\}
$$
$$
  {e_{b}}_{} = \ \{ 1_{2},0_{3}\}
$$
$$
  \mu_{\bullet} = \frac{\Sigma \bullet}{n} = \frac{1}{2}
$$
$$
 \Sigma\  = \ \mu_{a} + \mu_{b} = \ 1
$$

We distribute the probability to each edge. Thus edges
\({e_{a}}_{}\) and \(e_{b}\) still account for intrinsic
probability of 1 for the function. This reflects the law of conservation
as there is no information loss performing the operation. The operation
has been separated into two for the ease of communication, no time (or
movement) is associated with the order of operation.

The dotted line is clarification that this is an enclosed system and
is effectively 0:

$$
  {e_{c}}_{} = \ \{ 0_{1},0_{3}\} = 0
$$

State A (Figure~\ref*{fig:State A}) and state B (Figure~\ref*{fig:State B}) are examples of possible iterations.

\begin{figure}
  \centering
  \includesvg{fig3}
  \caption{State A}
  \label{fig:State A}
\end{figure}

\begin{figure}
  \centering
  \includesvg{fig4}
  \caption{State B}
  \label{fig:State B}
\end{figure}

As this system is isolated, both A (Figure~\ref*{fig:State A}) and B (Figure~\ref*{fig:State B}) effectively have identical
properties, therefore no discernable comparison can be made:

\begin{equation} \label{eq:9}
  \Sigma_{A} = \{\{ 1_{1},0_{2}\},\{ 1_{1},0_{4}\}\}\  = \Sigma_{B} = \ \{\{ 1_{3},0_{1}\},\{ 1_{3},0_{2}\}\}\  = 1\ 
\end{equation}

\subsubsection{2 function system}\label{function-system}

For a system to demonstrate change it needs to include a partner
function. (Figure~\ref*{fig:2f}) is an example of such a system.

\begin{figure}
  \centering
  \includesvg{fig5}
  \caption{2 function system}
  \label{fig:2f}
\end{figure}

\begin{equation} \label{eq:10}
  \Sigma = \{\{\{ 1,0\},\{ 1,0\}\},\{\{ 1,0\},\{ 1,0\}\}\}\  = \ 2
\end{equation}

The potential probability of a system is calculated by the product
of all edge probabilities:

\begin{equation} \label{eq:11}
  \Pi = \{\{\frac{1}{2}\},\{\frac{1}{2}\},\{\frac{1}{2}\},\{\frac{1}{2}\}\}\  = \frac{1}{16}\ 
\end{equation}

Taking state C or D from (Figure~\ref*{fig:2f}) illustrates the relative change of
the partner system.

\begin{figure}
  \centering
  \includesvg{fig6}
  \caption{State C}
  \label{fig:state c}
\end{figure}

\begin{figure}
  \centering
  \includesvg{fig7}
  \caption{State D}
  \label{fig:state d}
\end{figure}

State C (Figure~\ref*{fig:state c}) effectively becomes a single isolated function so the potential
probability \(\kappa\) is reduced to 0 while state B (Figure~\ref*{fig:state d}) demonstrates a
potential \(> 0\):

\begin{equation} \label{eq:12}
  \kappa_{state\ A}\  = 0
\end{equation}

\begin{equation} \label{eq:13}
  \kappa_{state\ B} = \frac{1}{16}
\end{equation}

The intrinsic probability for both states is 2.

This shows a discernible contrast between the 2 functions which allows
for investigation.

The operation of an isolated function has been diagrammed above for
ease, a more accurate graph for a binary cycle is shown in (Figure~\ref*{fig:graph}).

\begin{figure}
  \centering
  \includesvg{fig8}
  \caption{binary cycle}
  \label{fig:graph}
\end{figure}

Though for visualisation of a function, the author has found
repeating the first node to represent a loop or repeat/continuation is
more suitable (Figure~\ref*{fig:graph2}), as the functions discussed in this paper only rely on the
sum of nodes to give rise to the kinematics.

\begin{figure}
  \centering
  \includesvg{fig9}
  \caption{binary cycle}
  \label{fig:graph2}
\end{figure}

(Figure~\ref*{fig:graph2}) demonstrates where \(\mu > 1\), determining
vectorisation of edges or locality of individual nodes is not possible
and for velocity or location to be determined a relative function has to
be present.

To normalise into real world values we can use the nodes to represent
momentum \(p\), edges to represent the speed of light \(c\) and the area
of the edges/nodes represent \(E\). Using Dirac's derivative for 1
dimensional wave function we arrive at:

\begin{equation} \label{eq:14}
  E = pc
\end{equation}

Effectively a 1+1 dimensional function is an internal momentum function.