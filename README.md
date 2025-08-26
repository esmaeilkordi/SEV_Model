# SEV_Model
The model quantify the fish responses to suspended sediment in streams and estuaries. The Model is based on method developed by C.P. Newcombe (1994), C. P. Newcombe and J.O.T. Jensen (1996) and C.P. Newcombe (1997).

# Visual Clarity Impact Assessment Model
This model developed based on the Newcombe 2003. In this model, a SEV scale is prsented. The SEV relation is as follows:

Z (SEV) = a + b*(Loge X) +c*(loge Y)

where Z(SEV) = Severity of ill effect; X = Duration of exposure (h); Y = yBD; Black Disk Sighting range (m).

SEV has 15 stages, ranges from 0 to 15. Zero scale represnts the No effect and the 14 scale represents the 100% mortality.

In additional yBD(m) factor the user can utilized other parameters including Beam Attenuation BA(1/m), Secchi disk sighting range zSD (m), a vertical measurment for deep waters, and Nephelometric Turbidity Units (NTU)

SEV Scales: 0: Ideal. Best for adult fishes that must live in a clear water environment most of the time.

1-3: Slightly Impaired. Feeding and other behaviors begin to change.

4-8: Significantly Impaired. Marked increase in water cloudiness could reduce fish growth rate, habitat size, or both.

9-14: Severely Impaired. Profound increases in water cloudiness could cause poor "condition" or habitat alienation.

The calibrated model by Newcombe 2003 is:

SEV = - 4.49 + 0.92(loge X) - 2.59(loge yBD).

Key point:

Turbidity values in this study (NTU) can be calculated from this equation:

NTU = 0.91 + 0.27b

Where b (SSC) is the suspended solid concentration (mg/L) (Johnson and Hines, 1999). According to this correlation, 250 (mg/L) corresponds to 68 NTU, and 2000 (mg/L) corresponds to 541 NTU.

The following are coefficients for conversion amoung zSD (1/m), BA (m), and yBD (M) (Davies-Colley, 1998):

yBD = 4.8/BA

Secchi depth (Kirk, 1988):

zSD = 6.5/BA. and, yBD = 0.74 zSD

NTU respect to the yBD:

Black disk sighting range calculated from NTU data based on following Eq.

ln(y) =a+ b ln(x)

where x represents NTU, y represents (yBD) (cm), and a and b are coefficients for the intercept and slope, 5.57 and -0.8, respectively. (see Figure 7 of Smith et al., 1997):

ln(yBD) = 5.572012 - 0.80137 ln(NTU), r2 = 0.97
