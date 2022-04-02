# Anemometer_anemoscope

# Fusion 360 model
https://bit.ly/3wXU4yy

# 3D printing
FDM or resin should both work, so far I printed some prototypes in PLA at 0.2 layer height and tolerances are fine.

Anemometer's cups have to be post-processed after printing by warming with an hot air station (180 C° for PETG) the segment that links each cup to the main triangular body. After 20-25 second, the link gets soft and the cup can be rotated by 90° in the desired direction.

TODO:
- rotation aligment jig

# Electronics

Rotational encoder AS5600 module in I2C mode for the anemoscope. Current version uses a flat telephone 4-wires cable. 
Planning to substitute it with a 5 or 6 wires cable to hook the anemometer's reed switch, that at the moment requires an additional cable. 


# License

This project is licensed under Apache v2 (software, electronics, documentation) and Creative Commons Attribution 4.0 (hardware/mechanical) (see [LICENSE](LICENSE.txt) and [Creative Commons](https://creativecommons.org/licenses/by/4.0/)).

    Copyright 2022 Pierluigi Colangeli
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
