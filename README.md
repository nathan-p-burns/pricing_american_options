# Pricing American Options - Erdös Institute Quantative Finance Project
### **Nathan Burns**
*The use of AI in the project is entirely restricted to in-line suggestions provided by copilot set to 'low' eagerness (this is a feature of VS studio). Any code that taken from another source is referenced.*

In this project, we will investigate the various procedures on the pricing of American-style options.
American-style options differ from European-style options in that they can be exercised at any time prior to the expiration date, in this notebook we will investigate various different methods of pricing these kinds of options. Of course the main difficulty in doing so is taking the benefit of early exercise into account. The methods we shall look at are the 
1. The Binomial Tree Model
2. The Longstaff-Schwartz Monte-Carlo Method.
3. The Bjerksund and Stensland Approximation.

We will finally look at the so-called *perpetual put option*, which behaves somewhat more nicely than its finite time counter-part.
