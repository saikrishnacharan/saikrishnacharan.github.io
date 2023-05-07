# <span style="color:Blue;">Research Blog</span>
---
* My research lies in the field of beamforming for mmWave Communications.

<img src="images/beamforming.png?raw=true"/><img src="images/Beamforming_analogy_2.JPG?raw=true"/>

* Early spatial filters were designed to form pencil beams in order to receive signal from a specific location and attenuate signals from other directions.
* Beamforming or spatial filtering is a signal processing technique used in sensor arrays for directional signal transmission or reception.


* Now let us consider a Uniform Linear Array 

## Radiation Pattern by tweaking number of Antennas

<img src="images/Antenna_Tweak.gif?raw=true"/>

* From the above graph, we can see that Antenna gain proportional to number of antennas. More the number of antennas, more the beamforming gain and less Half Power Band Width(HPBW).

## Radition Pattern by tweaking d/lamda
<img src="images/Ratio_Tweak.gif?raw=true"/>

* From the above graph, we can see the ratio of 0.5 yields only one main lobe. Ratio of >0.5 creates significant side lobes resulting in power leakage in not desirable directions.


### Additional Resources
[<span style="color:Green;">Slides on Basic Beamforming</span>](/pdf/Beamforming_Slides_New.pdf)

[<span style="color:Grey;">Code for above animation</span>](/Coding_Files/Radiation_Pattern_Antenna.ipynb)

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, world!" << endl;
    return 0;
}
```
