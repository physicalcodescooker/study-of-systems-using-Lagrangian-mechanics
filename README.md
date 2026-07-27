# Study of Systems using Lagrangian mechanics
Basic behavioral analysis of a few physical systems using classical techniques of Lagrangian mechanics. This includes deriving the equations of motion with a symbolic manipulation library, solving the resulting differential equations using different numerical methods and then visualizing the results using graphs and simple animations.
The use of an alternative expression of the Lagrangian as proposed by Keith Zengel in his paper '*An alternative Lagrangian approach*' [refrence] is adopted in order to develop a new conceptual insight on the physical systems diverging from the traditional approaches in undergraduate classes. This is done for purely exploratory reasons. A hint of novelty to induce excitement in the seemingly dull subject.

## Traditional ways
According to Hamilton's principle, the path $$x(t)$$ that a physical particle with a single degree of freedom will follow in configuration space is known as the stationary path of the action. Where action is given by
$$ s = \int L(x,x^.,t) dt = \int (T-U) dt$$,
 
This path that describes the evolution of the state of particle is given by the Euler-Largrange equation,
                      
  $$\frac{d}{dt} \frac{\partial L}{\partial x^.} - {\partial L}{\partial x} = 0$$.

Another fact relevant is that for any twice differentiable function $$\phi(x,t)$$ only a function of x and t, there can be a function $$\psi(x,x^.,t)$$ defined as,

$$\psi(x,x^.,t) = \frac{d\phi}{dt} = \frac{\partial \phi}{\partial t} + x^.\frac{\partial \phi}{\partial x}$$

such that the action for both *L* and *L +$$\psi$$* is the same. This is because the term $$\int_{t_1}^{t^2} \psi(x,x^.,t) dt$$ depends only on the endpoints of the path it will not affect the path between these points. Because the variation of these endpoint values vanishes under the Hamilton's principle, the Euler-Lagrange equation is still satisfied and the additional function acts as a constant.

Above statements open the door for an infinite alternative Lagrangians. NOte that these have been under study by mathematical physicists for a long time.

The alternate Lagrangian is taken in the form of,
$$L_{\alpha} = (\sqrt T \pm \iota \sqrt U)^2$$
