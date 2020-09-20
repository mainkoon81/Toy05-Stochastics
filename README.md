# Toy05-Stochastics
stochastic process + 

### Basic Probability Space (`Ω`, `F`, `P`): 
 - `∩` : AND
 - `u` : OR
<img src="https://user-images.githubusercontent.com/31917400/93689207-233dad00-fac4-11ea-98a2-9500e607884b.jpg" />

1. **[Sample Space] `Ω`**: a space that includes **all possible outcomes** of an experiment...such as **{0, 1}** for binary outcomes..
2. Power_Set ![formula](https://render.githubusercontent.com/render/math?math=2^\Omega): a collection of all sebsets of Ω...including all possible combinations of the elements such as {Φ},{0},{1},**{0, 1}** for binary outcomes..we can say the Power_Set is the **largest Sigma_field**!!!
3. **[Sigma_Algebra(field)] `F`** on Ω : a bunch of subsets (we are interested in) collected from the Power_Set ![formula](https://render.githubusercontent.com/render/math?math=2^\Omega). At the end...it's just an extended sample space!! This is the space that helps calculate probabilities of different combinations (Joints) ?
   - the number of elements of `F` is 2^(![formula](https://render.githubusercontent.com/render/math?math=2^\Omega))
   - property 01. ![formula](https://render.githubusercontent.com/render/math?math=\Omega\in)`F`
   - property 02. `F` is closed under complementation ( if...![formula](https://render.githubusercontent.com/render/math?math=\Lambda\in\F), then ![formula](https://render.githubusercontent.com/render/math?math=\Lambda^c\in\F) as well )
   - property 03. `F` is closed under countable union ( if...![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{1},\Lambda_{2}\in\F), then ![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{1}) U ![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{2}\in\F) ) 
 
4. **[Probability Measure] `Ρ`**: a probability assigning space? 
   - property 01. The probability of the sample space `Ω` should be equal to one: **P(`Ω`) = 1** 
   - property 02. The probability of union of ![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{1},\Lambda_{2},..) is the sum of each probabilities of  ![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{i}): 
     - **P(**![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{1}) U ![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{2}) U ...**)** = ![formula](https://render.githubusercontent.com/render/math?math=\Sigma)**P(**![formula](https://render.githubusercontent.com/render/math?math=\Lambda_{i})**)**
     - so...in Bernoullie case, if P(0)=p, then P(1)=1-p

### Random variable with the measurable function ssai? 
<img src="https://user-images.githubusercontent.com/31917400/90989160-6291e000-e590-11ea-9f72-ef7645c65a18.jpg" />

### Random Function and Random Process
- Random Function **X(`t`)** ?

  : It is a function of an arbitrary argument `t` whose values are defined in terms of a certain experiment and may vary with the outcome of this experiment according to a given probability distribution. 
- Random Process?

  : It is simply a collection of random functions indexed by time. It is a time-varying function that assigns the outcome of a random experiment to each time instant: X(`t`). so...for a fixed `t`, it becomes a random variable! 












































































