## Instructions: Display Luminance Survey<br/>
---
### GOALS - Determine the behaviors of Consumer TV's display modes and native tone-mapping behaviors
<br/>
## Measure Native Full-Screen SDR Images (note difference from L32 - 10% pixel area images):<br/>
        1. SDR Native Peak-White<br/>
        2. SDR Mid-Gray from "Gamma-Adjusted"(black to reference-white) down mapping from HLG-to-SDR<br/>
        3. SDR Graphic White for "Linear-scaled" and "Gamma-Adjusted" down mappings from HLG-to-SDR<br/>
<br/>
## Measure Native HDR:<br/>
        1. HDR Mid-Gray (ITU-R BT.2408 @ 38% signal level in HLG and PQ (Full-Screen Size) <br/>
        2. HDR Graphic White (Full-Screen)<br/>
        3. HDR 1,000nit (L32-10% Pixel Area)<br/>
        2. HDR 3,930.5nit (L32-10% & 5% pixel area sizes)<br/>
---

* **<ins>Test File Usage<ins>**<br/>
        1. Place media files folders (SDR and HDR Folders)on a USB stick and plug into your TV for testing<br/>
        2. Set the TV Mode that you normally use (Cinema/Movie, Standard, Sports, Vivid, etc)<br/>
        3. Note DEFAULT/FACTORY settings for AI/Intelligent or Energy Saver / ECO settings (On or OFF)<br/>
                a) After measuring in "factory settings", make Measurement with the all above modes OFF<br/>
        4. Measure SDR Patterns<br/>
        5. Measure HDR Patterns if applicable<br/>
        7. Enter requested information and image luminance values into survey (links below)<br/>
        8. Repeat the test with each TV display mode (where possible) to see what midtone stretching is occurring<br/>
    
* **<ins>Surveys<ins>**<br/>
        1. [SDR Display MODE Consumer Survey for ANYONE](https://forms.gle/7PX7YSNEz3odWzY29)<br/>
        2. [SDR Display Luminance Survey for Experts](https://forms.gle/MRcGhh8WgQVUkUSJ9)<br/>
        3. [HDR Display Luminance Survey for Experts](https://forms.gle/nFKsyX6bWNLTkdKt6)<br/>
    
* **<ins>Spot Meter Measuring<ins>**
    * A spot meter must be used for display measurement accuracy:
        * With Calman (or equivalent) using included Calman workflow (included in Github Repository) for nits measurement
        * [Click here for inexpensive handheld SM208 screen luminance meter via Amazon](https://www.amazon.com/gp/product/B00H050VEI/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)**<br/>
                **Click RANGE button once on SM208 to set correct range for the measurements**

* **<ins>SDR Test Files<ins>**        
    * **Narrow-Range TS AVC and MPEG2 8bit** (Black=16; Peak White=235)
         * 1a Full-Screen SDR Mid-Gray with two tone mappings, SDR Peak White (HEVC)
         * 1b Full-Screen SDR Mid-Gray with two tone mappings, SDR Peak White (AVC)
         * 2a Portrait Display Skin Tone Test Pattern SDR-HLG-SDR Roundtrip (MPEG2)
         * 2b Portrait Display Skin Tone Test Pattern SDR-HLG-SDR Roundtrip (AVC)
        

* **<ins>HDR Test Files<ins>**
    * **Narrow-Range TS HEVC 10bit** (Black=64; Peak White=940)
    * **Full Screen Mid-Gray and Graphics White and L32 for 1,000nits, L32-10%/5% Pixel Area 3,930nits
         * 3- HLG Display Luminance_Test HEVC  (HEVC-Main10 59.94P)
         * 4- PQ Display Luminance Test HEVC 1K-NIT Peak MDCV/CLLI (HEVC-Main10 59.94P)
         * 5- PQ Display Luminance Test HEVC 4K-NIT Peak MDCV/CLLI (HEVC-Main10 59.94P)
         * 6- Portrait Display Skin Tone Test Pattern SDR-to-HLG Upmapping - (HEVC-Main10 59.94P)
 
* **<ins>Image Descriptions for SDR Test Files 1a-b<ins>**
    * Peak white (100% Peak White Nominal Video Level)
    * Hybrid-Linear HDR->SDR Downconvert using NBCU LUT3 - HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits(cd/m<sup>2</sup>)
    * Gamma-Adjusted HDR->SDR Downconvert using BBC LUT9C - HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits(cd/m<sup>2</sup>)

* **<ins>Reference<ins>**
    * **[Click here for LUTs Used In DaVinci Resolve Project Referenced in This Repository](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation/tree/main/LUTS_for_Software/HLG-to-from-SDR%20-%20Type%20III%20and%20Type%20I/For%20DaVinci%20Resolve%2017%20-%20Video%20Level%20Tag%20Added%20-%20Type%20III))**
    * **[Click Here For NBCU UHD HDR/SDR Single-Stream Workflow Recommendation](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation)**
    * **[Click Here For Initial Survey Summary During DTG Testing](https://www.dropbox.com/sh/udbhwgd1gr64yud/AAAB1stA5kQieL3LBgqYwS9qa?dl=0))**
  
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
