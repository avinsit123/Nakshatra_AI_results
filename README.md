# Astronomical Machine Learning Prediction Challenge 

## Description
Astronomical Machine Learning Prediction Challenge was conducted by Nakshatra as a part of its Annual fest Ephemeris.The event saw the participation of 15 teams from all over India.The Participants had to predict if a star was Pulsar given certain feature of its star-profile and DM-SNR Curve.The Dataset has been included in Pulsar_Datasets folder so that everyone can try it out.

## Dataset Description
Pulsars are a rare type of Neutron star that produce radio emission detectable here on Earth. They are of considerable scientific interest as probes of space-time, the inter-stellar medium, and states of matter. 
	As pulsars rotate, their emission beam sweeps across the sky, and when this crosses our line of sight, produces a detectable pattern of broadband radio emission. As pulsars rotate rapidly, this pattern repeats periodically. Thus pulsar search involves looking for periodic radio signals with large radio telescopes.
	Each pulsar produces a slightly different emission pattern, which varies slightly with each rotation. Thus a potential signal detection known as a 'candidate', is averaged over many rotations of the pulsar, as determined by the length of an observation.Machine learning tools are now being used to automatically label pulsar candidates to facilitate rapid analysis. Classification systems in particular are being widely adopted.
	Each candidate in the dataset(row) is described by 8 continuous variables. The first four are simple statistics obtained from the integrated pulse profile (folded profile). This is an array of continuous variables that describe a longitude-resolved version of the signal that has been averaged in both time and frequency. The remaining four variables are similarly obtained from the DM-SNR curve. These are summarised below:
	
	

	
	1. Mean of the integrated profile.(Mean_Profile)
	2. Standard deviation of the integrated profile.(SD_Profile)
	3. Excess kurtosis of the integrated profile.(Excess_kurtosis_Profile)
	4. Skewness of the integrated profile.(Skewness_Profile)
	5. Mean of the DM-SNR curve.(Mean_Curve)
	6. Standard deviation of the DM-SNR curve.(SD_Curve)
	7. Excess kurtosis of the DM-SNR curve.(Excess_kurtosis_Curve)
	8. Skewness of the DM-SNR curve.(Skewness_Curve)
To predict: whether star is pulsar or not(1 means star is pulsar and 0 means star is not pulsar)

The Training Dataset contains 12528 instances and Test Dataset contains 5370 examples.

## Winners 

### First Prize
AeroAstro(IIT Bhubhaneshwar)

Team Members : Murtaza Vohra , Saif Ali Khan 

### Second Prize
Akatsuki(NSUT)

Team Members : Ruchit Rawal

### Third Prize 
Not_Important(GTBIT)

Team Members : Rajat Sharma

### Best Kernel
Coding Botzz(NSUT)

Team Members : Amarjeet Singh,Kush Ghilothia
## LeaderBoard 

<table style="width:100%">
  <tr>
    <th>Rank</th>
    <th> Team Name</th>
    <th> Institute </th>
    <th> F1 Score </th>
  </tr>
  <tr>
    <td>1</td>
    <td>AeroAstro</td>
    <td>IIT Bhubhaneshwar</td>
    <td>0.888</td>
  </tr>
   <tr>
    <td>2</td>
    <td>Akatsuki</td>
    <td>NSUT</td>
    <td>0.874</td>
  </tr>
 <tr>
    <td>3</td>
    <td>Not_Important</td>
    <td>GTBIT</td>
    <td>0.867</td>
  </tr>
   <tr>
    <td>4</td>
    <td>AI-Artist</td>
    <td>Government College Of Engineering And Leather Technology</td>
    <td>0.863(submitted on 11/03/19 7:09 PM)</td>
  </tr>
   <tr>
    <td>5</td>
    <td>Codeword</td>
    <td>Arya Institute of Engineering and Technology</td>
    <td>0.863(submitted on 11/03/19 10:01 PM)</td>
  </tr>
  <tr>
    <td>6</td>
    <td>Bazinga</td>
    <td>NSUT</td>
    <td>0.861</td>
  </tr>
    <tr>
    <td>7</td>
    <td>Coding Botzz</td>
    <td>NSUT</td>
    <td>0.859</td>
  </tr>
    <tr>
    <td>8</td>
    <td>XY12</td>
    <td>NSUT</td>
    <td>0.858</td>
  </tr>
    <tr>
    <td>9</td>
    <td>Ask2Ans</td>
    <td>NSUT</td>
    <td>0.849</td>
  </tr>
    <tr>
    <td>10</td>
    <td>Pacman</td>
    <td>NSUT</td>
    <td>0.804</td>
  </tr>
    <tr>
    <td>11</td>
    <td>FAALTU</td>
    <td>NSUT</td>
    <td>0.585</td>
  </tr>
    <tr>
    <td>12</td>
    <td>AI_wiz</td>
    <td>NIT Kurukshetra</td>
    <td>0.550</td>
  </tr>
    <tr>
    <td>13</td>
    <td>Maverics</td>
    <td> -- </td>
    <td>0.337</td>
  </tr>
    <tr>
    <td>14</td>
    <td>Disco-Disco</td>
    <td>NSUT</td>
    <td>0.002</td>
  </tr>
    <tr>
    <td>15</td>
    <td>Jai Mata Di</td>
    <td>NSUT</td>
    <td>0.000</td>
  </tr>
  </table>
  
## Contact 
For any information or clarification contact <a href="mailto:s.avinash.it.17@nsit.net.in"> Avinash Swaminathan</a> .
