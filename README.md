## Display Luminance Survey<br/>
---
### GOALS
#### <ins>SDR Measurement<ins>
#### Measure Native SDR Peak-White, Midgray after conversion from HDR using NBCU and BBC LUTs (tone-mapped midgray luminance HDR to SDR; the two tone-mapping methods described in ITU-R BT.2408)
#### <ins>HDR Measurement<ins>
#### Measure Native HDR 1,000nits, Graphic White(203nit), MidGray(26nits) (nits=(cd/m<sup>2</sup>))<br/>
---

* **<ins>Test File Usage<ins>**
    * 1. Place media files folders (SDR and HDR)on a USB stick and plug into your TV for testing
    * 2. Set the TV Mode that you normally use (Cinema/Movie, Standard, Sports, Vivid, etc)
    * 3. Select any SDR or HDR image that will open on your TV. You need only find one that works.
    * 4. Measure the peak white image (center image)
    * 5. Measure NBCU LUT3 midgray downmapped image (left image)
    * 6. Measure BBC LUT9C midgray downmapped image (right image)
    * 7. Enter requested information and image luminance values into survey (links below)
    * 8. Repeat the test with each TV display mode (where possible) to see what midtone stretching is occurring
   
   * **<ins>Surveys<ins>**</br>
        1. [SDR Display MODE Consumer Survey for ANYONE](https://forms.gle/7PX7YSNEz3odWzY29)</br>
        2. [SDR Display Luminance Survey for Experts](https://forms.gle/MRcGhh8WgQVUkUSJ9)</br>
        3. [HDR Display Luminance Survey for Experts](https://forms.gle/nFKsyX6bWNLTkdKt6)</br>

* **<ins>Spot Meter Measuring<ins>**
    * **A spot meter must be used for display measurement accuracy:**
        *  With Calman (or equivalent) using included Calman workflow for nits measurement
        * **[Click here for Handheld SM208 screen luminance meter via Amazon](https://www.amazon.com/gp/product/B00H050VEI/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)**

* **<ins>SDR Repository Files with 10% Window Size Gray Chips<ins>**
    * **Full-Range PNG 16bit** (16bit Black=0; Peak White=65535)
       * **PNG-16**
         * 1-SDR-Peak-White-MidGray-38PercentHLG-SDR-2ToneMaps-16bit-PNG-FR.png
    * **Full-Range JPEG 8bit** (8bit Black=0; Peak White=255)
       * **PNG-8bit, JPEG-8bit**
         * 2-SDR-Peak-White-MidGray-38PercentHLG-SDR-2ToneMaps-8bit-JPEG-FR.jpg
    * **Narrow-Range MP4 AVC 8bit** (Black=0; Peak White=255)
       * **AVC-Main-MP4**
         * 3-SDR-MidGray38HLG-SDR-2ToneMaps-1080P-8bit-H264Main-NR.mp4

* **<ins>HDR Repository Files with 10% Window Size Gray Chip and 5% for 1,000nits (pause movie)<ins>**
    * **<ins>Narrow-Range QuickTime/MP4 Movie10bit** (Black=0; Peak White=940)(9%, 10%, 11% Peak White Chips)<ins>**
       * **HEVC-Main10-MP4 (This file will work in most HDR TV's)**
         * 4-PQ_Display_Luminance_Test_HEVC_NR.mp4
         * 5-HLG_Display_Luminance_Test_HEVC.mp4
 
* **<ins>Image Descriptions<ins>**
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

* **<ins>HDR Test File Thumbnail Preview<ins>**
<p align="center">
  <img width="720" height="405" src="https://github.com/digitaltvguy/SDR-Display-Luminance-Survey/blob/main/Additional_ref_files/thumbnail720HDR.jpg?raw=true">
</p>
