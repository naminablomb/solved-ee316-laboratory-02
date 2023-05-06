Download Link: https://assignmentchef.com/product/solved-ee316-laboratory-02
<br>



<strong>Inverting and Noninverting OP-Amp Circuits</strong>




<h1>Purpose</h1>

The goal of this laboratory is to examine inverting and noninverting Op-Amp configurations for both DC and AC inputs. You will also examine the closed loop voltage gain and study the effect of load resistance on the output voltage.

<h1>Theoretical Background</h1>

<h2>Operational Amplifier</h2>

An operational amplifier is designed such that the output voltage v<sub>out</sub> at terminal 3, as defined by Figure 2.1, is equal to the input voltage difference, v<sub>2</sub> – v<sub>1</sub>, multiplied by a constant A, called the open-loop gain.




<h3>Vout = A (v2 – v1)</h3>

For an ideal operational amplifier the signal input currents at terminals 1 and 2, are both equal to zero. This means that the input impedance of an ideal Op-amp is infinite.

The output voltage, v<sub>out</sub>, is always equal to A (v<sub>2</sub> – v<sub>1</sub>) and independent of the current that is drawn by a load impedance. This means output impedance of an ideal Op-amp is zero. Referring to Figure 2.1, terminal 1, denoted by a minus sign, is called inverting input terminal. Terminal 2, denoted by a plus sign, is called non-inverting input terminal. This comes from the fact that the output signal will be inverted with respect to a signal at the inverting input, and the output signal will not be inverted with respect to a signal at the noninverting input.







<h3>Figure 2.1</h3>

From the definition of the operational amplifier gain, notice that after some rearranging it can also be written as:




Because A is infinite for an ideal amplifier, the following must be true.







Which verifies that the differential voltage between the inputs for an ideal Op-amp is zero.

To summarize, for an ideal op-amp: i<sub>1</sub> = 0 at the inverting input terminal. i<sub>2</sub> = 0 at the noninverting input terminal.

The differential input is governed by.

The input impedance of an ideal op-amp is infinite.The output impedance of an ideal op-amp is zero.

<h2>Inverting Amplifier</h2>

Refer to Figure 2.2. A basic inverting amplifier configuration is realized by placing a resistor R<sub>IN</sub> at the inverting input terminal and a feedback resistor R<sub>F</sub> between the inverting and output terminal. The closed-loop gain of this op-amp configuration is defined to be:




<h3>Figure 2.2</h3>

Note that even though terminal V<sub>1</sub> is not connected to the ground its voltage is zero. This must be true because by design V<sub>2</sub> –V<sub>1</sub> = 0 and V<sub>2</sub> = 0 because it is connected to the ground. We say that terminal 1 is at virtual ground. By applying KCL at node 1, it can be shown that




which is the negative ratio of the feedback resistance R<sub>F</sub> and input resistance R<sub>IN.</sub>

<em> </em>

This configuration (Figure 2.2) is called an inverting configuration because a minus sign is associated with the closed loop gain, i.e., the input and the output is out of phase. For DC input and output this means they are of opposite polarity. For AC input and output this means there is 180-degree phase shift between them.

<em> </em>

<strong><em>Non-Inverting Amplifier:</em></strong>

<em> </em>

Refer to Figure 2.3 on the next page. In this configuration V<sub>IN</sub> is directly applied to the noninverting terminal and R<sub>IN</sub> is connected to the ground. In order to analyze this circuit, apply KCL at terminal 1 as before. Then it follows that:




The output voltage and the gain can be written as:

<em> </em>

<em> </em>

<h3>Figure 2.3</h3>




This configuration is called a non-inverting configuration because the gain is positive, i.e. the input and the output are in phase. For a DC input and output this means they are of the same polarity. For an AC input and output this means they are in phase.







Determine the values and fill in a Table 2.1. and Table 2.2 for inverting and non-inverting respectively.




<h1>Simulation Part (Multisim)</h1>

Let R<sub>IN</sub> = 1 kΩ, R<sub>F</sub> = 0.5, 1, 2, 3 and 4 kΩ, and the input voltage be a 2 V<sub>pp</sub> (2 volt peak-topeak) sinusoidal waveform at 1kH<sub>Z</sub> frequency.

<em> </em>

For each of the following, plot one example of V<sub>IN</sub> and V<sub>OUT</sub> on the same graph for two complete cycles.

<h2>Inverting Amplifier</h2>

<ul>

 <li>Build the circuits as shown in Figure 2.2. Use the values as defined in Table 2.1.</li>

 <li>Plot the input and the output waveforms using the oscilloscope.</li>

 <li>Determine the gain.</li>

 <li>Measure the voltage using a digital volt meter. Compare and discuss the voltage readings that result from the different Rf. Create your own table.</li>

</ul>

<h2>Noninverting Amplifier</h2>

<ul>

 <li>Build the circuits as shown in Figure 2.3. Use the values as defined in Table 2.2.</li>

 <li>Plot the input and the output waveforms using the oscilloscope.</li>

 <li>Determine the gain.</li>

 <li>Measure the voltage using a digital volt meter. Compare and discuss the voltage readings that result from the different Rf. Create your own table.</li>

</ul>

<h2>Table 2.1 (Inverting Amplifier)</h2>




<table width="511">

 <tbody>

  <tr>

   <td width="83"><strong>V</strong><strong>IN<sub>PP</sub> (V)</strong></td>

   <td width="84"><strong>R</strong><strong>IN (kΩ)</strong></td>

   <td width="84"><strong>R<sub>F</sub> (kΩ)</strong></td>

   <td width="91"><strong>V</strong><strong>OUT<sub>PP </sub>(V)</strong><strong> O-scope</strong></td>

   <td width="84"><strong>Gain (V/V) </strong></td>

   <td width="84"><strong>V</strong><strong>OUT<sub>RMS</sub> (V) </strong><strong>DMM</strong></td>

  </tr>

  <tr>

   <td rowspan="5" width="83">2</td>

   <td rowspan="5" width="84">1</td>

   <td width="84">0.5</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">1</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">2</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">3</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">4</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

 </tbody>

</table>

<h2>Table 2.2 (Non-Inverting Amplifier)</h2>




<table width="511">

 <tbody>

  <tr>

   <td width="83"><strong>V</strong><strong>IN<sub>PP</sub> (V)</strong></td>

   <td width="84"><strong>R</strong><strong>IN (kΩ)</strong></td>

   <td width="84"><strong>R<sub>F</sub> (kΩ)</strong></td>

   <td width="91"><strong>V</strong><strong>OUT<sub>PP </sub>(V)</strong><strong> O-scope</strong></td>

   <td width="84"><strong>Gain (V/V) </strong></td>

   <td width="84"><strong>V</strong><strong>OUT<sub>RMS</sub> (V) DMM</strong></td>

  </tr>

  <tr>

   <td rowspan="5" width="83">2</td>

   <td rowspan="5" width="84">1</td>

   <td width="84">0.5</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">1</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">2</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">3</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

  <tr>

   <td width="84">4</td>

   <td width="91"> </td>

   <td width="84"> </td>

   <td width="84"> </td>

  </tr>

 </tbody>

</table>




These tables are just examples. For the lab report, you will need to create your own tables for theoretical, simulation, and experimental data.

<h1>Laboratory Procedure</h1>

<em> </em>

Build both an Inverting and Noninverting Op-Amp circuit in the lab. Repeat all the steps from the Simulation section. Compare your results with Simulation sections. Comment and explain any discrepancies. Use the same voltage and resistance values that were used in the simulation. <em> </em>




Using the equations from the theory section, calculate by hand the expected output and gain for each input of the inverting and non-inverting circuits. Include example calculations in your lab report and compare to simulation and experiment.




<em>Some exemplary results are shown below for information purpose ONLY.</em>




You can find the function generator and oscilloscope under simulate and then instruments














