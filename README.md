## Instructions: Display Luminance Survey<br/>
---
### GOALS - Determine the behaviors of Consumer TV's display modes and native tone-mapping behaviors
<br/>
#### Measure Native SDR:<br/>
        1. SDR Mid-Gray from Linear-scaled(black to reference-white) down mapping from HLG-to-SDR<br/>
        2. SDR Peak-White (10% Screen Size)<br/>
        3. SDR Mid-Gray from "Gamma-Adjusted"(black to reference-white) down mapping from HLG-to-SDR<br/>
        2. SDR Peak-White (Full-Screen)<br/>
<br/>
#### Measure Native HDR:<br/>
        1. HDR Mid-Gray (ITU-R BT.2408 @ 38% signal level in HLG and PQ (10% Screen Sizes) <br/>
        2. HDR Graphic White (10% Screen Sizes)<br/>
        3. HDR 1,000nit (10% and 5% Screen Sizes)<br/>
        2. HDR 3,930.5nit (5% screen size)<br/>
---

* **<ins>Test File Usage<ins>**<br/>
        1. Place media files folders (SDR and HDR Folders)on a USB stick and plug into your TV for testing<br/>
        2. Set the TV Mode that you normally use (Cinema/Movie, Standard, Sports, Vivid, etc)<br/>
        3. Note DEFAULT/FACTORY settings for AI/Intelligent or Energy Saver / ECO settings (On or OFF)<br/>
                a) After measureing in "factory settings", make Measurement with the all above modes OFF<br/>
        4. Measure all SDR Patterns<br/>
        5. Measure all HDR Patterns if applicable<br/>
        7. Enter requested information and image luminance values into survey (links below)<br/>
        8. Repeat the test with each TV display mode (where possible) to see what midtone stretching is occurring<br/>
    
* **<ins>Surveys<ins>**<br/>
        1. [SDR Display MODE Consumer Survey for ANYONE](https://forms.gle/7PX7YSNEz3odWzY29)<br/>
        2. [SDR Display Luminance Survey for Experts](https://forms.gle/MRcGhh8WgQVUkUSJ9)<br/>
        3. [HDR Display Luminance Survey for Experts](https://forms.gle/nFKsyX6bWNLTkdKt6)<br/>
    
* **<ins>Spot Meter Measuring<ins>**
    * A spot meter must be used for display measurement accuracy:
        * With Calman (or equivalent) using included Calman workflow for nits measurement
        * [Click here for Handheld SM208 screen luminance meter via Amazon](https://www.amazon.com/gp/product/B00H050VEI/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)**<br/>
                **Click RANGE button once on SM208 to set correct range for the measurements**

* **<ins>SDR Test Files<ins>**        
    * **Narrow-Range TS AVC and MPEG2 8bit** (Black=16; Peak White=235)
         * 1a-b SDR Mid-Gray Left and Right from two tone mappings, Center SDR Peak White
         * 2a-b Portrait Display Skin Tone Test Pattern SDR-HLG-SDR Roundtrip 

* **<ins>HDR Test Files<ins>**
    * **Narrow-Range TS HEVC 10bit** (Black=64; Peak White=940)
    * **10% Window Size Gray and Graphics White and 10%/5% for 1,000nits, 3,930nits
         * 3- HLG Display Luminance_Test HEVC  (HEVC-Main10 59.94P, 50P)
         * 4- PQ Display Luminance Test HEVC (HEVC-Main10 59.94P, 50P)
         * 5- Portrait Display Skin Tone Test Pattern SDR-to-HLG Upmapping
 
* **<ins>Image Descriptions for SDR Test Files 1a-b<ins>**
    * **Center Image:** Peak white (100% Peak White Nominal Video Level)
    * **Left Image:** SDR:BT.709 using NBCU LUT3 converted from HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits(cd/m<sup>2</sup)
    * **Right Image:** SDR:BT.709 using BBC LUT9C converted from HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits(cd/m<sup>2</sup)

* **<ins>Reference<ins>**
    * **[Click here for LUTs Used In DaVinci Resolve Project Referenced in This Repository](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation/tree/main/LUTS_for_Software/HLG-to-from-SDR%20-%20Type%20III%20and%20Type%20I/For%20DaVinci%20Resolve%2017%20-%20Video%20Level%20Tag%20Added%20-%20Type%20III))**
    * **[Click Here For NBCU UHD HDR/SDR Single-Stream Workflow Recommendation](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation)**
    * **[Click Here For Initial Survey Results From Contributors](https://www.icloud.com/numbers/040HYTS0GVcpkB3gFGE275p_A#SDR_Display_Luminance_Level_Survey_Tallies)**
  
* **<ins>SDR Test File Thumbnail Preview<ins>**
<p align="center">
  <img width="720" height="405" src="https://github.com/digitaltvguy/SDR-Display-Luminance-Survey/blob/main/Additional_ref_files/thumbnail720SDR.jpg?raw=true">
</p>

* **<ins>HLG Test File Thumbnail Preview<ins>**
<p align="center">
  <img width="720" height="405" src="https://github.com/digitaltvguy/SDR-Display-Luminance-Survey/blob/main/Additional_ref_files/thumbnail720HLG.jpg?raw=true">
</p>

* **<ins>PQ Test File Thumbnail Preview<ins>**
<p align="center">
  <img width="720" height="405" src="https://github.com/digitaltvguy/SDR-Display-Luminance-Survey/blob/main/Additional_ref_files/thumbnail720PQ.jpg?raw=true">
</p>
