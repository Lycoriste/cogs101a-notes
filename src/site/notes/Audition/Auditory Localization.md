---
{"dg-publish":true,"permalink":"/audition/auditory-localization/","tags":["cognitivescience","audition"]}
---

### **Terminology/Background**
---
Researchers study how sounds are **==localized==** in space:
	- Azimuth: position left to right.
	- Elevation: position up and down.
	- Distance from the observer.

**Auditory localization cues:**
1. Binaural (using both ears)
	- [[Audition/Interaural time difference\|Interaural time difference]] (**ITD**).
	- [[Audition/Interaural level difference\|Interaural level difference]] (**ILD**).
2. Monaural (using one ear)
	- Spectral cues and the head-related transfer function (**HRTF**).

#### **[[Audition/Binaural cues\|Binaural cues]]**
---
Location cues based on the comparison of the signal received by the left and right ears.

**Interaural time difference (ITD):** difference ==between the times== at which sounds reach the two ears.
- When distance to each ear is the same, there are no differences in time (point A).
- When the source is to the side of the observer, the times will differ (point B).
- This cue is better for **low frequency** tones (less than 800 Hz).
	- May use temporal coding.
- This is considered the dominant binaural cue for hearing because ==most environmental sounds have low-frequency components==.

**Interaural level difference (ILD):** difference in ==sound pressure level== reaching the two ears.
- Reduction in intensity occurs for **high frequency** sounds for the far ear (pointed away from sound source).
	- The head casts an **acoustic shadow**, ==blocking out (reflecting) and absorbing some of the high-frequency pressure waves==.
- This effect doesn't occur for low frequency sounds. Works best above 800 Hz.

**ILD** and **ITD** provide useful cues for judging locations along most of the *azimuth* plane. However, they are not effective for detecting differences in elevation.
- Consider point A and B, the level and time differences of signals reaching each ear is zero.
- There is a similar ambiguity at points C and D.
- These points are said to lie on a **cone of confusion**.
- ==Multiple/infinite cones of confusion are possible==.

Requires additional cue for reliable elevation judgment.

#### **[[Audition/Monaural cues\|Monaural cues]]**
---
The pinna and head affect the intensities of frequencies.

This is the **head-related transfer function (HRTF)** and is unique to each head.
- Measurements have been performed by placing small microphones in ears and comparing the intensities of frequencies with those at the sound source.
- This is a **==spectral cue==** since the information for location comes from the spectrum of frequencies.

We are best at localizing sounds in front of us because...
1. It appears that **ITD** and **ILD** azimuth cues are the most effective to the side, but we have difficulty detecting those on the cones of confusion.
2. Perception is an active process. No single observation is used to localize a sound. We orient to make ITD and ILD zero in front of us.
3. Spectral cues (HRTF) are always used.
4. Top-down information to help localize.
5. Visual cues become important when the object is in front of us.

#### **Physiological representation of auditory space**
---
1. **Narrowly tuned ITD neurons:** respond to specific time differences only. One neuron gives a location. This is a form of **specificity coding** (or sparse if more than one neuron).
2. **Broadly tuned ITD neurons:** respond to broad range of time differences. Location is calculated from a range of neural responses. This is a form of **distributed coding**.

**Jeffress Coincidence Model** for narrowly tuned ITD neurons.
- These neurons receive signals from both ears.
- Coincidence detectors only fire when signals arrive from both ears *simultaneously*.
- If signals reach both ears at the same time, then ITD is zero.
- These can be called **ITD detectors**.