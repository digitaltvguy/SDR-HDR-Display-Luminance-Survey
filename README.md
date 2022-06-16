### SDR Display Luminance Survey
### Native SDR Peak-White 100% Nominal Signal Level in SDR
### UHD single-stream tone-mapped midgray luminance HDR to SDR (Test BT.2408 tone-mapping methods)
---

* **Please place the files in this respository on a USB stick and plug into your TV for playback.**
    * Measure the center image first (peak white)
    * Measure NBCU midgray downmap next
    * Measure BBC midgray downmap next
    * **[Click Here To Fill Out: SDR Display Luminance Survey](https://forms.gle/8RBDQEZRWKtDDUE78)**

* **Measuring Methods**
    * **Using a spot meter:**
        *  With Calman (or equivalent) using any workflow that will give you a nit value (cd/m<sup>2</sup>).
        * **[Click here for SM208 Screen Luminance Meter via Amazon](https://www.amazon.com/gp/product/B00H050VEI/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1).** **Experimental-Check Meter Accuracy**
    * **Use a LUX meter with a display that is 55" or above since it is gathering photons based on a specific area.**
        * Convert LUX to nits 200cd/m<sup>2</sup> should equal 628Lux (cd/m<sup>2</sup>=LUX*3.14)
        * Placement of the LUX meter must be right over the pattern and extend past meter sensor several inches on each side. 

* **Repository Files**
    * **Full-Range 16bit** (16bit Black=0; Peak White=65535)
       * PNG-16
    * **Full-Range 8bit** (8bit Black=0; Peak White=255)
       * PNG-8bit, JPEG-8bit
    * **Narrow-Range 10bit** (Black=0; Peak White=940)
       * ProRes-Proxy-QuickTime, HEVC-Main10-MP4
    * **Narrow-Range 8bit** (Black=0; Peak White=255)
       * AVC-Main-MP4   
 
* **Image Descriptions**
    * **Center Image:** Peak white (100% Nominal Video Level)
    * **Left Image:** SDR:BT.709 using NBCU LUT3 converted from HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits.
    * **Right Image:** SDR:BT.709 using BBC LUT9 converted from HLG 38% signal level ("mid-gray" or 26nits when normalized at 1,000nits.

* **Reference**
    * **[Click here for LUTs Used In DaVinci Resolve Project Referenced in This Repository](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation/tree/main/LUTS_for_Software/HLG-to-from-SDR%20-%20Type%20III%20and%20Type%20I/For%20DaVinci%20Resolve%2017%20-%20Video%20Level%20Tag%20Added%20-%20Type%20III))**
    * **[Click Here For NBCU UHD HDR/SDR Single-Stream Workflow Recommendation](https://github.com/digitaltvguy/NBCU-HDR-SDR-Single-Stream_Workflow_Recommendation)**
    * **[Click Here For Initial Survey Results From Contributors](https://www.icloud.com/numbers/040HYTS0GVcpkB3gFGE275p_A#SDR_Display_Luminance_Levels)**
 
* **Image Thumbnail Preview** 
<p align="center">
  <img width="720" height="405" src="https://raw.githubusercontent.com/digitaltvguy/SDR-Luminance-Survey/main/Artwork/thumbnail720.jpg">
</p>
