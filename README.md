### SDR Display Luminance Survey
### Native SDR Peak-White 100% Nominal Signal Level in SDR
### Native SDR Midgray after conversion from HDR using NBCU and BBC LUTs
### OPTIONAL: Added Native HDR Test Files for 1,000nits, Graphic White(203nit), MidGray(26nits) (nits=(cd/m<sup>2</sup>))
### UHD single-stream tone-mapped midgray luminance HDR to SDR (Test BT.2408 tone-mapping methods)
---

* **Please place the files in this respository on a USB stick and plug into your TV for playback.**
    * Measure the center image first (peak white)
    * Measure NBCU LUT3 midgray downmap next
    * Measure BBC LUT9C midgray downmap next
    * **[Click Here To Fill Out: SDR Display Luminance Survey for Experts](https://forms.gle/MRcGhh8WgQVUkUSJ9)**
    * **[Click Here To Fill Out: SDR Display Luminance Survey for Consumers](https://forms.gle/7PX7YSNEz3odWzY29)**
    * **[Click Here To Fill Out: HDR Display Luminance Survey for Experts](https://forms.gle/nFKsyX6bWNLTkdKt6)**

* **Spot Meter Measuring**
    * **A spot meter must be used for display measurement accuracy:**
        *  With Calman (or equivalent) using included Calman workflow for nits measurement
        * **[Click here for Handheld SM208 screen luminance meter via Amazon](https://www.amazon.com/gp/product/B00H050VEI/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1).** 

* **SDR Repository Files with 10% Window Size Gray Chips**
    * **Full-Range PNG 16bit** (16bit Black=0; Peak White=65535)
       * PNG-16
    * **Full-Range JPEG 8bit** (8bit Black=0; Peak White=255)
       * PNG-8bit, JPEG-8bit
    * **Narrow-Range QuickTime/MP4 Movie10bit** (Black=0; Peak White=940)(9%, 10%, 11% Peak White Chips)
       * ProRes-Proxy-QuickTime
       * HEVC-Main10-MP4
    * **Narrow-Range MP4 AVC 8bit** (Black=0; Peak White=255)
       * AVC-Main-MP4   

* **HDR Repository Files with 10% Window Size Gray Chip and 5% for 1,000nits (pause movie)**
    * **Narrow-Range QuickTime/MP4 Movie10bit** (Black=0; Peak White=940)(9%, 10%, 11% Peak White Chips)
       * HEVC-Main10-MP4 (This file will work in most HDR TV's)
       * ProRes-Proxy-QuickTime
 
* **Image Descriptions**
    * **Center Image:** Peak white (100% Nominal Video Level)
    * **Left Image:** SDR:BT.709 using NBCU LUT3 converted from HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits(cd/m<sup>2</sup).
    * **Right Image:** SDR:BT.709 using BBC LUT9 converted from HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits(cd/m<sup>2</sup).

* **Reference**
    * **[Click here for LUTs Used In DaVinci Resolve Project Referenced in This Repository](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation/tree/main/LUTS_for_Software/HLG-to-from-SDR%20-%20Type%20III%20and%20Type%20I/For%20DaVinci%20Resolve%2017%20-%20Video%20Level%20Tag%20Added%20-%20Type%20III))**
    * **[Click Here For NBCU UHD HDR/SDR Single-Stream Workflow Recommendation](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation)**
    * **[Click Here For Initial Survey Results From Contributors](https://www.icloud.com/numbers/040HYTS0GVcpkB3gFGE275p_A#SDR_Display_Luminance_Level_Survey_Tallies)**
  
* **SDR Test File Thumbnail Preview**
<p align="center">
  <img width="720" height="405" src="https://raw.githubusercontent.com/digitaltvguy/SDR-Luminance-Survey/main/Artwork/thumbnail720SDR.jpg">
</p>

* **HDR Test File Thumbnail Preview**
<p align="center">
  <img width="720" height="405" src="https://raw.githubusercontent.com/digitaltvguy/SDR-Luminance-Survey/main/Artwork/thumbnail720HDR.jpg">
</p>
