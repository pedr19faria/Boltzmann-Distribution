# Ideal gas simulation and Maxwell-Boltzman Distribution
### Introduction
This projetct seeks to simulate the collision of molecules in a closed compartiment, in order to verify that it does get close to the Boltzmann Distribution. \
This simulation has some limitations, such as the simplification of some parts of the physics behind the simulation and the quantities of particles, for example, but it was still able to approach what we wanted to show. \
Fist of all, we will consider that there is a homogenous gas that is inside the closed compartiment, which follows the following hypothesis from the kinetic theory of gases: \
**1.** Gas is made of an extremely large number of particles. \
**2.** The molecules occupy a small fraction of the total volume filled by the gas. \
**3.** The molecules are constantly moving adn with that there are collisions with the walls of the recipient and other molecules, as a consequence, the direction of the velocity constantly chages.  \
**4.** The forces of interaction between these molecules are of short range and only have an effect during the collisions. However, as the duration of the collisions are negligeble when compared to the time between two consecutive collisions. Therefore, inbetween the collisions the molecule moves as a free particle with uniform linear motion. \
**5.** Every collision is perfectly elastic. 
Since every collision is perfectly elastic we can show that when two molecules collide their velocity will change following the rule shown above: \
$$ \overrightarrow{{v_{new}}} = \overrightarrow{v_1} - \dfrac{2m_1}{m_1 + m_2} \dfrac{<\overrightarrow{v_1} -  \overrightarrow{v_2},\overrightarrow{r_1} -\overrightarrow{r_2}>}{|\overrightarrow{r_1} - \overrightarrow{r_2}|^2}(\overrightarrow{r_1} - \overrightarrow{r_2}) $$ \
And since, all molecules have the same mass: \
``` math
\overrightarrow{{v_{new}}} = \overrightarrow{v_1} - \dfrac{<\overrightarrow{v_1} -  \overrightarrow{v_2},\overrightarrow{r_1} -\overrightarrow{r_2}>}{|\overrightarrow{r_1} - \overrightarrow{r_2}|^2}(\overrightarrow{r_1} - \overrightarrow{r_2}) 
```
 Therefore, once the molecules collide, the velocities will change following these equations. Also, if they hit the walls of the compartiment their speed will be the opposite as it was before. \
 ### The Maxwell-Boltzmann Distribution
  The Maxwell-Boltzmann Distribution is a Probability distribution that describes the distribution of velocities in a ideal gas in thermal equilibrium, where the particles move inside it freely, following the ideias set out by the kinetic theory of gases, as shown above. The simulation will seek out to approach it as best as possible this distribution. 
