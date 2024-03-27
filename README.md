# AI-Nose

Law enforcement has increasingly adopted electronic nose (e-nose) technology, a type of artificial "smell" detection
system, to bolster
security efforts against the illegal trafficking of explosives. While hardware advancements have received significant
attention, less focus has been placed on the development of robust classification and quantification models for these
prototypes.

This research project aims to address this gap by creating machine learning and deep learning models capable of
distinguishing explosive materials (including different types of gunpowder and TNT) from non-explosive substances.
Additionally, the models will predict the concentration of these materials. To achieve this, we
employed two linear techniques (Partial Least Squares and Logistic Regression) alongside two non-linear approaches
(Multilayer Perceptron Neural Network and Long Short-Term Memory network).
---

### Experiment Description

To assess the e-nose prototype's ability to identify and measure explosive substances, two separate databases were used.
Each database entry represents an experiment where the responses of six chemical sensors were recorded over a specific
time period.

<img src="Files\Fig1.svg" width="55%" height="10%" style="margin-left:10%">

#### Table Summary:
<table>
<thead>
  <tr>
    <th>Feature</th>
    <th>Database 1 (Low Concentration & Mixtures)</th>
    <th>Database 2 (High Concentration)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Goal</td>
    <td>Assess e-nose performance for low explosive concentrations and complex mixtures.</td>
    <td>Evaluate e-nose's ability to predict explosives at higher concentrations.</td>
  </tr>
  <tr>
    <td>Substances</td>
    <td>TNT, Gunpowder, Alcohol (2ml), Toothpaste & Soap</td>
    <td>TNT, Gunpowder, Alcohol (1ml)</td>
  </tr>
  <tr>
    <td>Concentration range</td>
    <td>0.1g to 3g</td>
    <td>3g to 5g</td>
  </tr>
  <tr>
    <td>Total experiments</td>
    <td>142</td>
    <td>63</td>
  </tr>
  <tr>
    <td>Number of samples per experiment (m)</td>
    <td>650</td>
    <td>1800</td>
  </tr>
  <tr>
    <td>Number of chemical sensors per experiment (n)</td>
    <td>6</td>
    <td>6</td>
  </tr>
  <tr>
    <td>Sampling frequency per experiment</td>
    <td>1 Hz</td>
    <td>10 Hz</td>
  </tr>
  </tbody>
</table>



